<template>
  <div id="header">
    <div id="logo">
      <a href=""><img src="../../assets/images/logo.png" alt="#"></a>
    </div>
    <div id="menu">
      <ul>
        <li><a class="active" href="#">HOME</a></li>
        <li><a href="#">ABOUT US</a></li>
        <li><a href="#">PORTFOLIO</a></li>
        <li><a href="#">SERVICES</a></li>
        <li><a href="#">BLOG</a></li>
        <li><a href="#">CONTACT US</a></li>
      </ul>
    </div>
  </div>
</template>

<script>
	export default {

	}
</script>

<style lang="scss" scoped>
  #header {
    padding: 20px 0 16px 0;
    border-bottom: 1px solid #c0c0c0;
    overflow: hidden;
  }

  #logo {
    width: 183px;
    height: 100px;
    float: left;
  }

  #menu {
    float: right;
    margin-top: 40px;
  }

  #menu ul li {
    float: left;
    margin-left: 63px;
  }
</style>
