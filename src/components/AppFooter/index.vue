<template>
  <div id="footer">
    <div id="footer-content">
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About us</a></li>
        <li><a href="#">Portfolio</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Blog</a></li>
        <li><a href="#">Contact us</a></li>
      </ul>
      <div class="clear"></div>
      <p>&copy; 2010 CreativeStudio. All Rights Reserved</p>
      <div id="logo-footer">

      </div>
    </div>
  </div>
</template>

<script>
	export default {

	}
</script>

<style lang="scss"scoped>
  #footer {
    background-color: #e2e2e2;
    padding: 32px 0 36px 0;
    margin-top: 33px;
  }

  #footer-content {
    width: 960px;
    margin: 0 auto;
    position: relative;
  }

  #footer-content a {
    color: #5d5d5d;
    font-weight: normal;
    text-transform: capitalize;
  }

  #footer-content a:hover {
    text-decoration: underline;
  }

  #footer-content ul li {
    float: left;
    padding: 0 7px;
    border-left: 1px solid #5d5d5d;
    line-height: 1;
  }

  #footer-content ul li:first-child {
    padding-left: 0;
    border: none;
  }

  #footer-content p {
    margin: 3px 0 0 0;
  }

  .clear {
    clear: both;
  }

  #logo-footer {
    width: 119px;
    height: 64px;
    background: url("../../assets/images/logo-footer.png") no-repeat;
    position: absolute;
    top: -12px;
    right: 0;
  }
</style>
