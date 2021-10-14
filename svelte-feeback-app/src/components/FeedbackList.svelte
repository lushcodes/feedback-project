<script>

import FeedbackItem from "./FeedbackItem.svelte";
export let feedback = [];


</script>

{#each feedback as feedbackRecord (feedbackRecord.id)}
  <FeedbackItem item={feedbackRecord} />
{/each}