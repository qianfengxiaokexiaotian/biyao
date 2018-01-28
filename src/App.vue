<template>
  <div id="app">
     <common-header></common-header>
    
    <router-view class="content"/>
    
    <div class="nav">
    
    	<router-link to="/">
    		<a>
    			<i></i>
    			<span>首页</span>
    			
    		</a>
    	</router-link>
    	<router-link to="/">
    		<a>
    			<i></i>
    			<span>首页</span>
    			
    		</a>
    	</router-link>
    	<router-link to="/">
    		<a>
    			<i></i>
    			<span>首页</span>
    			
    		</a>
    	</router-link>
    	<router-link to="/">
    		<a>
    			<i></i>
    			<span>首页</span>
    			
    		</a>
    	</router-link>
    	
    	
    	
    	
<!--    	
    	
    	<router-link to="/">发现</router-link>
    	<router-link to="/">订单</router-link>
    	<router-link to"/">我的</router-link>-->
    </div>
    
  </div>
</template>

<script>
	import HelloWorld from './components/HelloWorld';

//	
//import Lunbo from './components/Lunbo';

	
export default {
  name: 'App'
 
}



</script>

<style>
	body,html{
		margin:0;
		padding: 0;
		height: 100%;
	}	
	
	a{text-decoration: none;}
	
	
#app {
  display: flex;
  flex-direction: column;
  height: 100%;
}

.nav{
	/*height: 50px;*/
/*	line-height: 50px;*/
	display: flex;
	flex-direction: row;
	border-top: 1px solid black;
	}





.nav a{
   	width: 100%;
   	padding-left: 20px;
   	padding-right: 20px;
   	flex-direction: column;
   	border-right: 1px solid black;
	flex: 1;
	text-align: center;
	
}

.content{
	
	flex: 1;
	
}


</style>
