<template>
  <div class="row">
    <div class="col-4">
      <div class="list-group">
        <router-link
          to="/newpage/a"
          class="list-group-item list-group-item-action active"
          aria-current="true"
        >
          選單A
        </router-link>
        <router-link
          to="/newpage/b"
          class="list-group-item list-group-item-action active"
          aria-current="true"
        >
          選單B
        </router-link>
        <router-link
          to="/newpage/namedView/c2a"
          class="list-group-item list-group-item-action active"
          aria-current="true"
        >
          命名路由c2a
        </router-link>
        <router-link
          to="/newpage/namedView/a2b"
          class="list-group-item list-group-item-action active"
          aria-current="true"
        >
          命名路由a2b
        </router-link>
      </div>
    </div>
    <div class="col-8">
      <router-view></router-view>
    </div>
  </div>
</template>
