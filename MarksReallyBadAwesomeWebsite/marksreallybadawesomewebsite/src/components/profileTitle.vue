<template>
   <div class="profile-header">
      <div class="profile-header-right">
        <h1>Mark Hutson</h1>
        <h2>The Other Best Website</h2>
        <h3>Portfolio Edition</h3>
      </div>
    </div> 
</template>


<script>
export default {
  name: 'profileTitle',
}
</script>

<style scoped>
.profile-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .profile-header-right {
    margin: 20px;
    font-family: "Comic Sans MS", cursive, sans-serif;
  }

</style>
