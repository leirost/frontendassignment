<script>
	import { base } from '$app/paths';
	import Dog from '$lib/Dog.svelte';
</script>

<div class="interests">
	<p style="color:blue; font-weight: bold;">My interests!</p>
	<div class="cats" style="font-weight: bold;">
		I love animals! My family even have 5 cats: Lisa, Sonya, Lexus, Vesta and Tucha 😍 Look at them!
		<div class="pictures">
			<img src="{base}/source/lisa.jpg" alt="lisa" style="width: 18%; border: 4px solid #87CEEB;" />
			<img
				src="{base}/source/sonya.jpg"
				alt="sonya"
				style="width: 18%; border: 4px solid #87CEEB;"
			/>
			<img
				src="{base}/source/lexus.jpg"
				alt="lexus"
				style="width: 18%; border: 4px solid #87CEEB;"
			/>
			<img
				src="{base}/source/vesta.jpg"
				alt="vesta"
				style="width: 18%; border: 4px solid #87CEEB;"
			/>
			<img
				src="{base}/source/tucha.jpg"
				alt="tucha"
				style="width: 18%; border: 4px solid #87CEEB;"
			/>
		</div>
		I used to have a dog but... I don't have any now, so I like to look at virtual dogs 😌
		<Dog />
	</div>
</div>

<style>
	.interests {
		width: 97%;
		font-size: 26px;
		line-height: 20px;
		font-family: 'My Custom Font';
	}

	.cats {
		font-size: 20px;
		display: flexbox;
	}

	.pictures {
		text-align: center;
		display: flexbox;
		padding: 25px;
	}
</style>
