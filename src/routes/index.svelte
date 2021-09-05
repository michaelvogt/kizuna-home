<script>
	import wide from './under_construction_w.svg';
	import narrow from './under_construction_n.svg';
</script>

<style>
    .center-me {
        width: 100vw;
        height: 100vh;
				object-fit: cover;
        margin: auto;
    }
</style>


<section>
	<picture>
		<source srcset="{wide}" media="(min-width: 600px)">
		<img class='center-me' src="{narrow}" alt="site under construction">
	</picture>
</section>
