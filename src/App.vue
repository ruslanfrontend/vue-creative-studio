<template>
  <div class="wrapper">
    <div id="container">
      <AppHeader />

      <router-view/>

    </div>

    <AppFooter />
  </div>
</template>

<script>
	import AppHeader from "./components/AppHeader"
  import AppFooter from "./components/AppFooter"

	export default {
		components: {
			AppHeader,
      AppFooter
		}
	}
</script>

<style lang="scss">
  @import url('assets/css/reset.css');

  body {
    font: 12px/1.6 Arial, Verdana, Tahoma, sans-serif;
    color: #5d5d5d;
    background-color: #f4f4f4;
  }

  a {
    color: #fe9b00;
    text-decoration: none;
    font-weight: bold;
    text-transform: uppercase;
  }

  .active, a:hover {
    color: #090909;
  }

  p {
    margin: 8px 0;
  }

  h2 {
    font-size: 18px;
    font-weight: bold;
    color: #090909;
    text-transform: uppercase;
    padding-left: 28px;
    background: url("assets/images/arrow.png") no-repeat 0 10px;
    margin-bottom: 11px;
  }

  h3 {
    font-size: 12px;
    font-weight: bold;
    color: #090909;
    text-transform: uppercase;
    background: url("assets/images/arrow-smol.png") no-repeat 0 8px;
    padding-left: 22px;
    margin-bottom: 20px;
  }

  .wrapper {
    border-top: 16px solid #090909;
  }

  #container {
    width: 960px;
    margin: 0 auto;
  }
</style>
