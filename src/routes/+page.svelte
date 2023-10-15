<script>
  let recorder;
  let player;
</script>

<h1>ClimbUp</h1>
<h2>Upload your vid</h2>
<input bind:this={recorder} type="file" accept="video/*" capture />
<!-- svelte-ignore a11y-media-has-caption -->
<video bind:this={player} id="player" controls />
