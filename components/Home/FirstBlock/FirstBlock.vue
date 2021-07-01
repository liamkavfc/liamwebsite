<template>
  <div>
    <div class="details">
        <div class="profile_image"></div>
        <div class="profile_name text-center">
            <h1>Liam Kenny</h1>
            <h4>Software Developer</h4>
            <h5>Devon, UK</h5>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FirstBlock'
}
</script>

<style>
  #firstBlock {
    background:url('@/assets/images/block1-bg.jpg');
    background-size: cover;
    background-position: center;
  }

  #firstBlock .details {
    padding-top: 20vh;
    z-index: 99;
  }

  #firstBlock .details .profile_image {
    height: 300px;
    width: 300px;
    border-radius: 45rem;
    background-image: url('@/assets/images/selfimage-2.JPG');
    background-size: 225%;
    background-repeat: no-repeat;
    background-position: 43% 50%;
    margin: auto;
    box-sizing: border-box;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    border: 8px solid rgba(0, 0, 0, 0.75);
  }

  #firstBlock .details .profile_name {
      padding: 2rem 0;
  }

  #firstBlock .details .profile_name * {
    color: #fff;
  }
</style>
