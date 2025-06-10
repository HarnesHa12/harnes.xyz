<script lang="ts">
import '../app.css';

// biome-ignore lint/style/useConst: svelte
let { children } = $props();
</script>

{@render children()}
