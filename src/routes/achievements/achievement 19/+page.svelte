<script>
import { todo } from './todos.js'
</script>
 

<h1>Achievement 19</h1>

<p>These are Kalebs Morning to do list</p>
<ol>
    {#each todo as todo}
    <li>{todo}</li>
    {/each}
  </ol>
