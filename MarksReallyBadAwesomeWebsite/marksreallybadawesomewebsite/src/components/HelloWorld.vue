<template>
  <div class="profile">
    <div class="profile-about">
      <h3>About me</h3>
      <p>If you need me I'll be in my tower of solitude.</p>
      <p>My other car is a minivan #daddywagon.</p>
      <p>Pop punk is dead.</p>
      <p>Good at growing plants.</p>
      <p>Less good at career growing.</p>
    </div>
    <div class="profile-favorites">
      <h3>Favorite Movies</h3>
      <ul>
        <li>Red Dawn</li>
        <li>Harold and Maude</li>
        <li>The Lord of the Rings Exented Editions</li>
      </ul>
      <br>
      <h3>Favorite Music</h3>
      <ul>
        <li>Motion City Soundtrack</li>
        <li>Eminem</li>
        <li>Miles Davis</li>
      </ul>
      <ul>
        <li></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  .profile {
    display: flex;
    align-content: left;
    background-color: #ffffff;
    border: 2px solid #000000;
    border-radius: 10px;
    box-shadow: 5px 5px 10px #888888;
    font-family: "Comic Sans MS", cursive, sans-serif;
    padding: 20px;
    width: 600px;
    margin: 20px;
  }

  .profile-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .profile-header-left img {
    border: 2px solid #000000;
    border-radius: 50%;
    height: 100px;
    width: 100px;
  }

  .profile-about {
    margin-top: 20px;
  }

  .profile-about h3 {
    font-size: 18px;
    font-weight: bold;
    margin-top: 0;
  }

  .profile-about p {
    font-size: 14px;
    line-height: 1.5;
    margin-bottom: 5px;
  }

  .profile-favorites {
    margin-top: 20px;
  }

  .profile-favorites h3 {
    font-size: 18px;
    font-weight: bold;
    margin-top: 0;
  }

  .profile-favorites ul {
    list-style: none;
    margin: 0;
    padding: 0;
  }

  .profile-favorites li {
    font-size: 14px;
    line-height: 1.5;
  }
</style>