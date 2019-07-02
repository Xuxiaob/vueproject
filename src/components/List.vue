<template>
 
<div class="newsList">
    <ul>
      <li>
        <router-link to="detail/1">
           <h2>1.xx</h2>
          <p>oooo</p>

          
        </router-link>
       
      </li>
      <li>
         <router-link :to="{name:'detail',params:{aid:2}}">
           <h2>2.xx</h2>
           <p>oooo</p>

          
        </router-link>
        
       
      </li>
    </ul>
      
  </div>

</template>
<style>
.content .newsList{width:6.4rem; margin:0 auto;}
.newsList ul{ padding:0 0.4rem;}
.newsList ul li{ color:#494d4d; padding:0.2rem 0; border-bottom:1px dashed #ccc;}
.newsList ul li h2{max-height:0.9rem; font-size:0.33rem; overflow:hidden;}
.newsList ul li p{max-height:1.8rem; margin-top:0.05rem;overflow:hidden;}
.newsList{clear: both;margin-bottom:1rem;}
</style>