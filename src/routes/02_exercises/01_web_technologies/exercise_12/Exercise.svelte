<script>
	let clicked = false;
</script>

<div>
	<button class="btn btn-primary" on:click={() => (clicked = true)}>
		click here
	</button>
	{#if clicked} 
	  <p>You have clicked!</p> 
	{:else} 
	  <p>You have to click!</p> 
    {/if}
	<!--  -->
</div>
