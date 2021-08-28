<template>
  <div>
    <a id="mywork" />
    <div class="mywork text-center">
      <h1>MyWork</h1>
      <br>
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <img class="img-fluid" src="~assets/images/A2G_icon.png" />
          </div>
          <div class="col-md-8">
            <h3>Anywhere2Go</h3>
            <div class="text-left">
              <p>Anywhere2Go an app designed for indecisive people who just can't decide what they want to do! Why stress yourself out? Let the app decide for you!</p>

              <p>Simply select your category, enter your location and how far you're willing travel then our app will pick out a business for you! No longer will you have to spend so long trying to decide where to go!</p>
              <b>Categories:</b>
              <ul>
                <li>Restaurants</li>
                <li>Fast food</li>
                <li>Cafe</li>
                <li>Supermarket</li>
                <li>Pub</li>
                <li>And more to come!</li>
              </ul>
              <p>If you have any support question, please don't hesitate to send them to <a href="mailto:lksoftwaredevelopment@outlook.com">lksoftwaredevelopment@outlook.com</a></p>

              <br />
              <ul class="list-group list-group-horizontal">
                <li class="list-group-item">App Store</li>
                <li class="list-group-item"><a href="/app_privacy_policy">Privacy Policy</a></li>
                <li class="list-group-item"><a href="/app_terms">Terms and Conditions</a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MyWorkBlock'
}
</script>

<style>
  #myWorkBlock {
    background: #eee;
    padding: 2rem;
  }

  a {
    color: #000;
    text-decoration: underline;
  }

  ul {
    width: 100%;
  }

</style>
