<script>
  let buttonID = 1;

  const handleClick = function () {
    buttonID++;
    console.log(buttonID);
  };
</script>

<main>
  <h1>Achievement 17 - Push of a Button</h1>
  <div on:click={handleClick}>
    <button>CLICK ME! {buttonID}</button>
  </div>
</main>

<style>
  div {
    text-align: center;
    padding: 2rem;
  }

  h1 {
    text-align: center;
    padding: 7rem;
  }
</style>
