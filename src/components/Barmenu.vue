<template>
  <div class="navbar-container">
    <div class="navbar-content">
      <a href="" >
        <i class="bx bx-home-circle bx-sm" color="#ffffff"></i>
      </a>
      <a href="/box">
        <i class="bx bx-basket bx-sm" color="#ffffff"></i>
      </a>
      <a href="/favorites">
        <i class="bx bx-heart-circle bx-sm" color="#ffffff"></i>
      </a>
      <a href="/history">
        <i class="bx bx-history bx-sm" color="#ffffff"></i>
      </a>
    </div> 
  </div>
</template>
<script>
	export default {
		name: 'Barmenu'
	}
</script>

<style lang="less">

.navbar-container {
  width: 100%;
  background-color: white;
  position: fixed;
  bottom: 0;
  .navbar-content {
    padding: 20px;
    display: flex;
    justify-content: space-between;
    a {
      color: #5a5756;
      &:hover {
      color: rgba(255,131,62);
    }
    }
    
  }
}
</style>