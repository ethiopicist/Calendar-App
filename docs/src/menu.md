<aside class="menu columns is-mobile is-multiline">
  <div class="column is-half-mobile is-full-tablet">
    <p class="menu-label">
      General
    </p>
    <ul class="menu-list">
      <li><a href="./">Welcome</a></li>
      <li><a href="./about.html">About</a></li>
    </ul>
  </div>
  <div class="column is-half-mobile is-full-tablet">  
    <p class="menu-label">
      Using the App
    </p>
    <ul class="menu-list">
      <li><a href="./basic-features.html">Basic Features</a></li>
      <li><a href="./preferences.html">Preferences</a></li>
      <li><a href="./date-converter.html">Date Converter</a></li>
      <li><a href="./computus.html">Computus</a></li>
    </ul>
  </div>
  <div class="column is-hidden-mobile is-full-tablet">
    <p class="menu-label">
      Developers
    </p>
    <ul class="menu-list">
      <li><a href="./devs.html">Overview</a></li>
      <li><a href="./conversion-js.html">conversion.js</a></li>
      <li><a href="./calendar-js.html">calendar.js</a></li>
      <li><a href="./computus-js.html">computus.js</a></li>
    </ul>
  </div>
</aside>
<script src="../scripts/jquery.min.js"></script>
<script>
$(document).ready(function(){
  $('ul li a').each(function() {
    if($(this).attr('href') == './' + location.href.split("/").slice(-1)){
      $(this).addClass('is-active');
    }
  });
});
</script>
