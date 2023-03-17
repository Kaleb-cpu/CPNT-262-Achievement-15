<h1>Achievement 17</h1>

<script>
    import { browser } from '$app/environment'

    let billTotal = prompt('How much is your bill total?');
    let Total = '';
    // const tipAmount = calculateTip(billTotal1)
  
    const keydownEnter = function(tipRate = 0.20) {
     return billTotal * tipRate;
    

  //  return `${tipPercentage} tip on ${billTotal} is ${tip}`;

  }
//   
//   const tipAmount = calculateTip(billTotal1)
// // console.log(`${tipPercentage} tip on ${billTotal1} is ${tip}.`);
//   console.log(tipAmount);

</script>

<div on:keydown={keydownEnter}>
<label for="text-input">How much would you like to tip?</label>: 
<input type="text" id="text-input">
<p>Your total is {Total}</p>
</div>

