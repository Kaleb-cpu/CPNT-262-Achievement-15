<script>
  let todoList = [
  'Get out of bed',
  'Make coffee',
  'Read feeds',
  'Have shower',
  'Brush teeth',
  'Get dressed',
  'Leave for work',
  'Get breakfast to go'
]
</script>
<main>
  <h1>Achievement: 16</h1>
  <h2>Kaleb's Morning Todo List</h2>
  <ol>
    {#each todoList as todos}
    <li>{todos}</li>
    {/each}
  </ol>
</main>