<script>
	import FeedbackList from './components/FeedbackList.svelte';
	let feedback = [
		{
			id: 1,
			rating: 10,
			text: 'Lorem ad eu ut cillum ad do excepteur elit. Irure elit labore adipisicing minim. Lorem non consectetur et eiusmod elit magna nisi commodo laborum velit. Nulla esse esse eu labore duis consectetur nisi est veniam ad reprehenderit aliquip sint. Consequat consequat nisi et sint nulla eiusmod aliqua aute fugiat magna. Nostrud nostrud sunt aliqua laboris exercitation magna.',
		},
		{
			id: 2,
			rating: 9,
			text: 'Lorem ad eu ut cillum ad do excepteur elit. Irure elit labore adipisicing minim. Lorem non consectetur et eiusmod elit magna nisi commodo laborum velit. Nulla esse esse eu labore duis consectetur nisi est veniam ad reprehenderit aliquip sint. Consequat consequat nisi et sint nulla eiusmod aliqua aute fugiat magna. Nostrud nostrud sunt aliqua laboris exercitation magna.',
		},
		{
			id: 3,
			rating: 8,
			text: 'Lorem ad eu ut cillum ad do excepteur elit. Irure elit labore adipisicing minim. Lorem non consectetur et eiusmod elit magna nisi commodo laborum velit. Nulla esse esse eu labore duis consectetur nisi est veniam ad reprehenderit aliquip sint. Consequat consequat nisi et sint nulla eiusmod aliqua aute fugiat magna. Nostrud nostrud sunt aliqua laboris exercitation magna.',
		},
	]
</script>

<main>
	<FeedbackList {feedback} />
</main>
