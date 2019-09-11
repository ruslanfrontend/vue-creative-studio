<template>
  <div id="header">
    <div id="logo">
      <a href=""><img src="../../assets/images/logo.png" alt="#"></a>
    </div>
    <div id="menu">
      <ul>
        <li
          v-for="(item, index) in menu"
          :key="index"
        >
          <router-link
            :to="item.link"
            exact
          >{{ item.text }}</router-link>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
	export default {
		data() {
			return {
				menu: [
          {
          	link: '/',
            text: 'HOME'
          },
          {
          	link: '/about',
            text: 'ABOUT US'
          },
          {
          	link: '/portfolio',
            text: 'PORTFOLIO'
          },
          {
          	link: '/services',
            text: 'SERVICES'
          },
          {
          	link: '/blog',
            text: 'BLOG'
          },
          {
          	link: '/contact',
            text: 'CONTACT US'
          }
        ]
      }
    }
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
