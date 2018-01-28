<template>
  <div class="hello">
		  
		  <ul id="container">
		      <li v-for="item in list">
		        <img v-lazy.container="item">
		      </li>
		  </ul>
  
 
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
     
//        list:[
//          "https://pic.maizuo.com/usr/movie/1dd5e7d5618edcb603b67b7d85efbe71.jpg",
//      "https://pic.maizuo.com/usr/movie/6f8d3193bc19f9a36e61abacd15b863a.jpg",
//      "https://pic.maizuo.com/usr/movie/e044adec3a400f36c852b4b8061781f4.jpg",
//      "https://pic.maizuo.com/usr/movie/d44e5dfcb60df8ac39c101b21cd8bf9d.jpg",
//      "https://pic.maizuo.com/usr/movie/961391f7479f426b6584691330b2257f.jpg",
//      "https://pic.maizuo.com/usr/movie/fc952ee11cf01366704dba86d94040f9.jpg",
//      "https://pic.maizuo.com/usr/movie/76b217868630ec80a256f091a3619226.jpg"
//    ]
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
/*
img{min-height: 300px;}*/

</style>
