<script lang="ts">
	import Reveal from 'reveal.js';
	import Markdown from 'reveal.js/plugin/markdown/markdown';
	import { onMount } from 'svelte';

	import 'reveal.js/dist/reveal.css';
	import 'reveal.js/dist/theme/black.css';

	onMount(() => {
		let deck = new Reveal({
			autoAnimate: true,
			autoAnimateDuration: 1,
			autoAnimateEasing: 'ease',
			plugins: [Markdown]
		});
		deck.initialize({ plugins: [Markdown] });
	});
</script>

<div class="reveal">
	<div class="slides">
		<section data-auto-animate>
			<h1>Lingbis Kelompok xx 🤯</h1>
		</section>
		<section data-auto-animate>
			<h1>Lingbis Kelompok xx 🤯</h1>
			<p>Oleh</p>
		</section>
		<section data-auto-animate>
			<h1>Lingbis Kelompok xx 🤯</h1>
			<p>Oleh</p>
			<p>Miku</p>
		</section>
		<section data-auto-animate>
			<h1>Lingbis Kelompok xx 🤯</h1>
			<p>Oleh</p>
			<p>Miku</p>
			<p>Rin</p>
		</section>
		<section data-auto-animate>
			<p>Oke Lanjut 😎</p>
		</section>
		<section data-auto-animate>
			<p>jadi</p>
		</section>
		<section data-auto-animate>
            <p>Gini Dek 😏</p>
        </section>
        <section data-auto-animate>
            <p>aku</p>
        </section>
        <section data-auto-animate>
            <p>aku</p>
            <h1>Mumet 🤕</h1>
        </section>
        <section data-auto-animate>
            <p>aku</p>
            <h1>Mumet 🤕</h1>
            <p>tolong riset buat materi, ppt biar ku handle 😋</p>
        </section>
	</div>
</div>
