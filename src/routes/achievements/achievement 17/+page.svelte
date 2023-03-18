<h1>Achievement 17</h1>

<script>
  import { browser } from '$app/environment'

  let number = prompt("What's your favourite number?");

const handleClick = function(){
  return number++;
  console.log(number);

}

</script>
<div on:click={handleClick}>
  <h3>Your Favourite Number</h3>
  <button>Click on the Button to add one number</button>
  <h1>{number}</h1>
</div>


