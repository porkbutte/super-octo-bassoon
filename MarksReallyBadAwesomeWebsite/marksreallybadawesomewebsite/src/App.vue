<template>
<body>
<div class ="backing">
  <div class="container">
    <div class="profile-container">
      <div class="profile-pic">
        <profilePic></profilePic>
      </div>
      <div class="profile-Title">
        <profileTitle></profileTitle>
      </div>
      <div class="logo-container">
        <logoContainer></logoContainer>
      </div>
    </div>
    <div class="hello-world">
      <HelloWorld msg="Welcome to Your Vue.js App"/>
    </div>
    <div class="potato-gif">
    </div>
  </div>
</div>
</body>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import ProfileTitle from './components/profileTitle.vue'
import ProfilePic from './components/profilePic.vue'
import LogoContainer from './components/logoContainer.vue'
// import potatoGif from './components/potatogif.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    ProfileTitle,
    ProfilePic,
    LogoContainer,
    // potatoGif
  }
}
</script>

<style>
body {
  background: url('https://media.giphy.com/media/oSYflamt3IEjm/giphy.gif') no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}

.container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.profile-container {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  margin-top: 20px;

}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.logo-container {
  max-height: 300px;
  display: flex;
  flex-direction: row;
  align-items: right;
  justify-content: right;
  margin-top: 20px;
  

}

.profile-title {
  max-height: 300px;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  margin-top: 20px;


}

.profile-pic {
  max-height: 300px;
  display: flex;
  flex-direction: row;
  align-items: left;
  justify-content: left;
  margin-top: 20px;

}

.hello-world {
  display: flex;
  flex-direction: row;
  align-items: left;
  justify-content: left;
  margin-top: 20px;

}

.backing {
  background-color: #ffffff;
  border: 2px solid #000000;
  border-radius: 10px;
  box-shadow: 5px 5px 10px #888888;
}

</style>
