<template>
  <footer
    class="footer"
    :class="{ [`footer-${type}`]: type }"
    :data-background-color="backgroundColor"
  >
    <div class="container">
      <nav>
        <ul>
          <li>
            <a href="#">
              Home
            </a>
          </li>
          <li>
            <a href="#">
              About
            </a>
          </li>
        </ul>
      </nav>
      <div class="copyright">
        &copy; {{ year }}
        <!-- made with <md-icon>favorite</md-icon> by
        <a href="#" target="_blank">Jared Nebeker</a>
        for a better web. -->
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  props: {
    backgroundColor: String,
    type: String
  },
  data() {
    return {
      year: new Date().getFullYear()
    };
  }
};
</script>
<style></style>
