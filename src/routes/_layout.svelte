<script>
</script>

<div>
  <main>
    <div class="homepage">
      <div class="container">
        <div class="small">
          <div class="page-title">
            <div class="name">
              <h1>Fauzi Shurendra</h1>
            </div>
            <div>
              <a href=".">Home /</a>
              <a href="about">About /</a>
              <a href="portfolio">Portfolio</a>
            </div>
            <hr />
          </div>
        </div>
      </div>
      <slot />
    </div>
  </main>

  <footer class="container" style="margin-top: 100px;">
    <div class="footer">
      <div class="container">
        <div class="small">
          <div class="social">
            <span>
              &copy; {new Date().getFullYear()} fshurendra.com &bull; Powered by
              <a
                href="https://sapper.svelte.dev"
                target="_blank"
                rel="noopener noreferrer"
                class="powered-by">Sapper</a
              >
            </span>
          </div>
        </div>
      </div>
    </div>
  </footer>
</div>

<!-- <Nav {segment}/> -->

<!-- <main>
	<slot></slot>
</main> -->
<style>
  .page-title {
    padding-top: 150px;
    text-align: center;
  }

  .page-title a {
    color: blue;
  }
</style>
