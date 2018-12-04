<template>
  <div class="m-nav">
    <ul class="nav">
      <li class="list">
        <nuxt-link to="/my">我的美团</nuxt-link>
        <dl>
          <dd><nuxt-link to="/order">我的美团</nuxt-link></dd>
          <dd><nuxt-link to="/order">我的美团</nuxt-link></dd>
          <dd><nuxt-link to="/order">我的美团</nuxt-link></dd>
          <dd><nuxt-link to="/order">我的美团</nuxt-link></dd>
        </dl>
      </li>
      <li>
        <nuxt-link to="/order">手机APP</nuxt-link>
      </li>
      <li class="list bd">
        <nuxt-link to="/center">商家中心</nuxt-link>
        <dl>
          <dd><nuxt-link to="/order">登录商家中心</nuxt-link></dd>
          <dd><nuxt-link to="/order">我想合作</nuxt-link></dd>
          <dd><nuxt-link to="/order">免费手机开店</nuxt-link></dd>
          <dd><nuxt-link to="/order">发票</nuxt-link></dd>
        </dl>
      </li>
      <li class="list bd">
        <nuxt-link to="/site">网站导航</nuxt-link>
        <div class="subContainer">
          <dl class="hotel">
            <dt>酒店旅游</dt>
            <dd>国际机票</dd>
            <dd>国际机票</dd>
            <dd>国际机票</dd>
            <dd>国际机票</dd>
          </dl>
          <dl class="food">
            <dd>2</dd>
          </dl>
          <dl class="movie">
            <dd>3</dd>
          </dl>
          <dl class="app">
            <dd>4</dd>
          </dl>
        </div> 
      </li>
    </ul>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
</style>