<script>
  import { page } from '$app/stores'
  console.log($page.params.age);

  const capitalizeFirstSentence = ($page.params.name)[0].toUpperCase() + ($page.params.name).slice(1)

</script>

<h1>{capitalizeFirstSentence}'s age is {$page.params.age}</h1>

<style>
    h1{
      text-align: center;
      margin-top: 10vh;
    }
   </style>

