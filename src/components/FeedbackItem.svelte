<script>
  import Card from './ui/Card.svelte';
  export let item;
</script>

<Card>
  <h3>Rating: {item.rating}</h3>
  <p>{item.text}</p>
</Card>
