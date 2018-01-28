<template>
	
	
	<div class="lunbo">
		
		
		
		
      <div class="swiper-container">
      	<div class="swiper-wrapper">
      		<div class="swiper-slide" v-for="item in list">
      			<img :src="item.imageUrl">
      		</div>
      		
      	</div>
      </div>
  
  
  
  
  </div>
	
	
	
	
	
	
</template>

<script>
//	import axios from 'axios';
	
	import Swiper from 'swiper';
	
		
export default {
  name: 'Lunbo',
  data () {
  	
    return {
     
     list:[
     
     
     
     
     ]
     
    }
  },
  mounted(){	
  	
  	
  	axios.get('/v4/api/billboard/home?__t=1516883595099')
  	.then((response)=>{
  		
  		console.log(response)
  		this.list = response.data.data.billboards;
  		
  		
  		
  		this.$nextTick(function(){
  			var sp = new Swiper(".swiper-container",{
  				autoplay:true
  			})
  			
  		})
  		
  		
  		
  	})
  	.catch(function(error){
  		
  		console.log(error)
  		
  	})
  	
  
  	
  }
  
  
}



	
	
	
	
	
	
	
	
</script>



<style scoped>
	
	@import '../assets/css/swiper.min.css';
	
	
	
	
	
	
</style>