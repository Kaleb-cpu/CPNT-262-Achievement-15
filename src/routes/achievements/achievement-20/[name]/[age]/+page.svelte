<script>
  import { page } from '$app/stores'
  console.log($page.params.age);
</script>



<h1>{$page.params.name}'s age is {$page.params.age}</h1>
<p></p>

<style>
    h1{
      text-align: center;
      margin-top: 10vh;
    }
   </style>

