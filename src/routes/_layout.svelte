<script>
	import Nav from '../components/Nav.svelte';
	import Bio from '../components/Bio.svelte';

	// export let segment;
</script>

<div>
	<main>
		<div class="homepage">
			<div class="container">
				<div class="small">
					<div class="page-title">
						<Bio />
						<div class="name">
							<h1>Fauzi Shurendra</h1>
						</div>
						<div>
							<a href=".">Home /</a>
							<a href="about">About /</a>
							<a href="karya">Karya</a>
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
							&copy; 2020 fshurendra.id Powered by
							<a href="https://sapper.svelte.dev/" target="_blank">Sapper</a>
						</span>
					</div>
				</div>
			</div>
		</div>
	</footer>
</div>

<style>
	.page-title {
		padding-top: 150px;
		text-align: center;
	}

	.page-title a {
		color: blue;
	}

</style>





<!-- <Nav {segment}/> -->
<!-- <main>
	<slot></slot>
</main> -->