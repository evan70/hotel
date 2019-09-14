<style lang="scss">
  footer {
    box-shadow: 0px 0px 8px rgba(0, 0, 0, 0.3);
    background: #444b57;
    padding: 0.5rem 3.2rem;
    font-size: 0.7rem;
    color: #dfdfdf;
    text-align: center;
    @media (min-width: 500px) {
      text-align: right;
    }
  }
  a {
    font-weight: 700;
    color: inherit;
    display: block;
    @media (min-width: 500px) {
      float: left;
    }
  }
  span {
    white-space: nowrap;
  }
  i {
    text-shadow: 0 0 3px #2172eb;
  }
</style>

<footer>
  <a href="https://github.com/evan70/sapper-svelte-hotel" target="_blank">
    GIT
  </a>
  <span>
    Made for some fun
    <i class="far fa-copyright" />
    Evan70
  </span>
</footer>
