<script>
  import Header from "./lib/header/Header.svelte";
</script>

<Header />
<main max-w-5xl text-center mx-auto>
  <h1>Hello world!</h1>
  <p>Start your svelte project! </p>
</main>
<footer text-sm c-gray-400 w-full text-center>Powered by <a href="https://svelte.dev">Svelte</a></footer>

<style lang="scss">
  :global(html, body) {
    margin: 0;
    padding: 0;
  }

  :global(html) {
    color: rgb(34, 34, 34);
    background-color: rgb(246, 246, 246);
  }

  :global(html.dark) {
    color: rgb(246, 246, 246);
    background-color: rgb(34, 34, 34);
  }

  :global(#app) {
    font-family: Arial, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu,
      Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }

  a {
    color: #ff3e00;
  }

	@media (min-width: 480px) {
		footer {
			padding: 40px 0;
		}
	}
</style>
