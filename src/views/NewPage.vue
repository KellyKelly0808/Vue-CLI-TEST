<template>
   <div class="row">
      <div class="col-4">
         <div class="list-group">
  <router-link  to="/newpage/a" class="list-group-item list-group-item-act">
    The current link item a
  </router-link>
  <router-link  to="/newpage/b" class="list-group-item list-group-item-act">
    The current link item b
  </router-link>
   <router-link  to="/newpage/namedView/a2b" class="list-group-item list-group-item-act">
    The current link item 命名視圖 a2b
  </router-link>
   <router-link  to="/newpage/namedView/c2a" class="list-group-item list-group-item-act">
    The current link item 命名視圖 c2a
  </router-link>
</div>
      </div>

      <div class="col-8">
      <router-view></router-view>
      </div>
   </div>
</template>
