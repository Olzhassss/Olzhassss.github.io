<script>
	import { default as img1, default as img2 } from '$lib/images/blog_top_img2.png';
	import Entry from './Entry.md.svelte';
</script>

<svelte:head>
	<title>Blog</title>
</svelte:head>

<div class="">
	<img class="max-h-[595px] w-full object-cover" src={img1} alt="" />
	<div class="h-60 gradient-btw" />
</div>

<section>
	<h1 class="mb-2">
		Analysis of <b class="">Tokyo Ghoul</b>
	</h1>
	<div class="text-center">
		<a
			class="text-base hover:text-myGreen transition"
			href="https://ww9.tokyoghoulre.com/chapter/tokyo-ghoulre-chapter-053/"
		>
			[Access the source here &larr;]
		</a>
		<a
			class="text-base hover:text-myGreen transition"
			href="https://github.com/Olzhassss/Olzhassss.github.io/blob/master/src/routes/projects/blog/Entry.md.svelte"
		>
			[Access the markdown here &larr;]
		</a>
	</div>
</section>

<section class="pt-0">
	<div class="mx-auto container text-lg [&_h2]:mb-2 [&_p]:mb-4 [&_em]:italic">
		<Entry />
	</div>
</section>

<div class="mt-24">
	<div class="h-60 gradient-btw rotate-180" />
	<img class="max-h-[595px] w-full object-cover" src={img2} alt="" />
</div>

<style>
	.gradient-btw {
		background: rgb(0, 0, 0);
		background: linear-gradient(
			180deg,
			rgba(0, 0, 0, 1) 10%,
			rgba(242, 242, 242, 1) 95%,
			rgba(255, 255, 255, 1) 100%
		);
	}
</style>
