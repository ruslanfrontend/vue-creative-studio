<template>
  <div>
    <div id="header-image">
      <div id="black-box">
        <p>Here’s some nice work <a href="#">view portfolio &raquo;</a></p>
      </div>
    </div>
    <div id="content">
      <div class="content-box">
        <h2>About us</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque quis nulla id orci
          malesuada porta posuere quis massa. Nunc vitae purus non augue scelerisque ultricies vitae et
          velit. Sed vitae lectus id sem lobortis scelerisque. Praesent eget consequat libero. </p>
        <p><a href="#">read MORE</a></p>
      </div>
      <div class="content-box">
        <h2>our Benefits</h2>
        <ul>
          <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque quis nulla id orci
            malesuada porta posuere quis massa.
          </li>
          <li>
            Nunc vitae purus non augue scelerisque ultricies vitae et velit. Sed vitae lectus id sem
            lobortis scelerisque. Praesent eget consequat
          </li>
          <li>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque quis nulla id orci
            malesuada porta posuere quis massa.
          </li>
        </ul>
      </div>
      <div class="content-box" id="content-box">
        <h2>testimonials</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque quis nulla id orci
          malesuada porta posuere quis massa. Nunc vitae purus non augue scelerisque ultricies vitae et
          velit. Sed vitae lectus id sem lobortis scelerisque.
        </p>
        <p class="italic-text">Rafi, Graphicsfuel.com</p>
      </div>
    </div>
    <div id="portfolio">
      <h2>our portfolio</h2>
      <div class="portfolio-image">
        <img src="../assets/images/portfolio1.jpg" alt="#">
        <a href="#">View &raquo;</a>
      </div>
      <div class="portfolio-image">
        <img src="../assets/images/portfolio2.jpg" alt="#">
        <a href="#">View &raquo;</a>
      </div>
      <div class="portfolio-image">
        <img src="../assets/images/portfolio3.jpg" alt="#">
        <a href="#">View &raquo;</a>
      </div>
      <div class="portfolio-image" id="portfolio-image">
        <img src="../assets/images/portfolio4.jpg" alt="#">
        <a href="#">View &raquo;</a>
      </div>
    </div>
    <div id="bottom-row">
      <div id="blog">
        <h3>blog updates</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque quis nulla id orci
          malesuada porta posuere quis massa. Nunc vitae purus non augue scelerisque ultricies vitae et
          velit. Sed vitae lectus id sem lobortis scelerisque. Praesent eget consequat libero. </p>
      </div>
      <div id="social">
        <h3> connect with us</h3>
        <ul>
          <li><a href="#"><img src="../assets/images/twitter.png" alt="#"></a></li>
          <li><a href="#"><img src="../assets/images/facebook.png" alt="#"></a></li>
          <li><a href="#"><img src="../assets/images/flickr.png" alt="#"></a></li>
          <li><a href="#"><img src="../assets/images/rss.png" alt="#"></a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
	export default {
		name: 'home',
		components: {}
	}
</script>

<style lang="scss" scoped>

  #header-image {
    height: 380px;
    background: url("../assets/images/header-image.jpg") no-repeat;
    margin-top: 20px;
    border-bottom: 1px solid #c0c0c0;
    padding-bottom: 20px;
    position: relative;
  }

  #black-box {
    width: 443px;
    height: 43px;
    background-color: #090909;
    text-transform: uppercase;
    font-weight: bold;
    font-size: 15px;
    color: #999898;
    position: absolute;
    left: 35px;
    bottom: 68px;
  }

  #black-box p {
    margin: 13px 12px;
    line-height: 1;
  }

  #black-box a {
    float: right;
  }

  #black-box a:hover {
    color: #fe9b00;
  }

  #content {
    margin-top: 20px;
    border-bottom: 1px solid #c0c0c0;
    overflow: hidden;
    padding-bottom: 24px;
  }

  .content-box {
    width: 285px;
    float: left;
    margin-right: 52px;
  }

  #content-box {
    margin-right: 0;
  }

  .content-box h2 {
    font-size: 18px;
    font-weight: bold;
    color: #090909;
    text-transform: uppercase;
    border-bottom: 5px solid #090909;
    padding-bottom: 3px;
    margin-bottom: 16px;
  }

  .content-box ul li {
    background: url("../assets/images/check.png") 0 3px no-repeat;
    padding-left: 28px;
    margin-bottom: 12px;
    line-height: 1.3;
  }

  .italic-text {
    font-style: italic;
    color: #090909;
    margin-top: 20px;
  }

  #portfolio {
    margin-top: 20px;
    padding-bottom: 33px;
    border-bottom: 1px solid #c0c0c0;
    overflow: hidden;
  }

  .portfolio-image {
    width: 215px;
    height: 135px;
    float: left;
    margin-right: 33px;
    position: relative;
  }

  .portfolio-image a {
    position: absolute;
    right: 0;
    bottom: 0;
    color: #090909;
    display: block;
    background-color: #fe9b00;
    padding: 4px 10px;
    line-height: 1;
  }

  #portfolio-image {
    margin-right: 0;
  }

  #bottom-row {
    margin-top: 20px;
    overflow: hidden;
  }

  #blog {
    width: 670px;
    float: left;
  }

  #social {
    float: right;
    width: 220px;
  }

  #social ul li {
    float: left;
    margin-right: 12px;
  }
</style>
