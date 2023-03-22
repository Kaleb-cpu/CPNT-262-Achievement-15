<script>
  import { page } from '$app/stores'
  console.log($page.params.name);
</script>

  <h1>Your name is {$page.params.name} </h1>

   
   <style>
    h1{
      text-align: center;
      margin-top: 10vh;
    }
   </style>
