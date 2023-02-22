<script>
	import { marked } from 'marked';
	let value = `Some words are *italic*, some are **bold**`;
</script>

{@html marked(value)}

<textarea bind:value></textarea>

<style>
	textarea { width: 100%; height: 200px; }
</style>
<!-- There is no difference in the output betweeen the 'show me' and the 'reset' outputs. I think if you want to show that there is a two-way binding between
 the value and textarea, there should be an option to change the value in both places. I'm new to this and hope this is a valuable input. -->
