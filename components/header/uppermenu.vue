<template>
    <div class="uppermenu_wrapper">
      <ul>
        <li><nuxt-link to="/" exact> home page </nuxt-link></li>
        <li><nuxt-link to="/search" exact> search page </nuxt-link></li>
        <li><nuxt-link to="/gallery" exact> gallery page </nuxt-link></li>
      </ul>
    </div>
</template>

<script>
export default {
	name: 'uppermenu',
    data() {
        return {

        }
    }
}
</script>

<style  scoped>
.uppermenu_wrapper {
	float: left;
	width: 80%;
}
.uppermenu_wrapper  ul {
    padding:8px;
  }
 .uppermenu_wrapper  li {
      float:left;
      padding-right: 12px;
    }
    .uppermenu_wrapper  a {
        color:#fff;
        font-size: 16px;
      }
.router-link-active {
	background-color: #4dc0a0;
	padding: 2px 4px;
  border-radius: 3px;

}
</style>


