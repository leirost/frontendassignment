<script lang="ts">

	interface ApiResult {
		message: string;
	}
	const dogreq = fetch('https://dog.ceo/api/breeds/image/random');
	const json: Promise<ApiResult> = (async () => await (await dogreq).json())();
</script>

<style>
.center {
	padding: 15px;
	display: block;
  	margin-left: auto;
  	margin-right: auto;
  	width: 50%;
}
</style>

{#await json then dog}
  <img src={dog.message} class="center" />
{/await}