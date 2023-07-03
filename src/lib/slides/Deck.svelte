<script lang="ts">
	import Reveal from 'reveal.js';
	import Markdown from 'reveal.js/plugin/markdown/markdown';
	import { onMount } from 'svelte';

	import 'reveal.js/dist/reveal.css';
	import 'reveal.js/dist/theme/dracula.css';

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
			<h2>Bingung mau belajar + buat portofolio ? 🤯</h2>
		</section>
		<section data-auto-animate>
			<h1>Solusi ?? 🤕</h1>
		</section>
		<section data-auto-animate>
			<h2>Buat Blog Ajahh 😎</h2>
		</section>
		<section data-auto-animate>
			<p>jadi</p>
		</section>
		<section data-auto-animate>
			<p>kenapa 😏</p>
		</section>
		<section data-auto-animate>
			<p>Buat</p>
		</section>
		<section data-auto-animate>
			<p>Buat</p>
			<h4>Blog ? 🧐</h4>
		</section>
		<section data-auto-animate>
			<p>ya</p>
		</section>
		<section data-auto-animate>
			<p>ya</p>
			<p>Karena</p>
		</section>
		<section data-auto-animate>
			<p>ya</p>
			<p>Karena</p>
			<p>...</p>
		</section>
		<section data-auto-animate>
			<p>ya</p>
			<p>Karena</p>
			<h3>1. Bisa buat progress belajar mu rapi 🤓</h3>
		</section>
		<section data-auto-animate>
			<h3>1. Bisa buat progress belajar mu rapi 🤓</h3>
			<h3>2. Bisa buat portofolio 😎</h3>
		</section>
		<section data-auto-animate>
			<h3>1. Bisa buat progress belajar mu rapi 🤓</h3>
			<h3>2. Bisa buat portofolio 😎</h3>
			<h3>3. Bisa buat nambah koneksi 🤗</h3>
		</section>
		<section data-auto-animate>
			<h2>Final Project PPW 🤖</h2>
			<h3>Personal Blog 📈</h3>
			<p>Claudio Hans Figo</p>
		</section>
		<section data-auto-animate>
			<h2>Live Demo Project ⚡</h2>
			<a target="_blank" href="https://blog-figo.vercel.app">blog-figo.vercel.app</a>
		</section>
		<section data-auto-animate>
			<a target="_blank" href="https://blog-figo.vercel.app">...</a>
		</section>
		<section data-auto-animate>
			<h2>Astro `🚀`</h2>
			<a target="_blank" href="https://docs.astro.build/en/concepts/why-astro/">apa itu ?</a>
		</section>
		<section data-auto-animate>
			<h2>SSG 😱</h2>
			<img
				src="	https://miro.medium.com/v2/resize:fit:720/format:webp/1*JnrcYDCjuFw2hIx_iPY06g.png"
				alt=""
			/>
		</section>
		<section data-auto-animate>
			<h2>Sekian aja cuy 😅</h2>
			<p>Takut besok ga bangun, jam 2 pagi ini njirr 😖</p>
		</section>
	</div>
</div>
