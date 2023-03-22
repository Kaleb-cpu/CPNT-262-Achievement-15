<script>
  import { page } from '$app/stores'
  console.log($page.params.name);

   const capitalizeFirstSentence = ($page.params.name)[0].toUpperCase() + ($page.params.name).slice(1)

   export const nameCapital = capitalizeFirstSentence
</script>

  <h1>Your name is {capitalizeFirstSentence} </h1>

   
   <style>
    h1{
      text-align: center;
      margin-top: 10vh;
      
    }
   </style>
