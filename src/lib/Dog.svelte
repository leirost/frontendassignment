<script lang="ts">
	interface ApiResult {
		message: string;
	}
	const dogreq = fetch('https://dog.ceo/api/breeds/image/random');
	const json: Promise<ApiResult> = (async () => await (await dogreq).json())();
</script>

{#await json then dog}
	<img src={dog.message} class="center" />
{/await}

<style>
	.center {
		padding: 15px;
		display: block;
		margin-left: auto;
		margin-right: auto;
		width: 50%;
	}
</style>
