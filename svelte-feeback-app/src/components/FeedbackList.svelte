<script>
export let feedback = [];


</script>

{#each feedback as feedbackRecord (feedbackRecord.id)}
  <h3>{feedbackRecord.text}</h3>
{/each}