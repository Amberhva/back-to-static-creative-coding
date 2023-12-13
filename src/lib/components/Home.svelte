<script> 
</script>

<main>
  <h1 class="sub-title">EEN <span>NIEUWE GENERATIE</span> HYDROLOGEN</h1>

  <h2 class="title">// SPATWATER</h2>
  <h2 class="title-down">SPATWATER \\</h2>
  
  <h3 class="sub-sub-title">CONCREET OP WATER EN BODEM</h3>

  <div class="dots-right">
    <div class="dot-right"></div>
    <div class="dot-right"></div>
    <div class="dot-right"></div>
    <div class="dot-right"></div>
    <div class="dot-right"></div>

    <div class="dot-right"></div>
    <div class="dot-right"></div>
    <div class="dot-right"></div>
    <div class="dot-right"></div>
    <div class="dot-right"></div>

    <div class="dot-right"></div>
    <div class="dot-right"></div>
    <div class="dot-right"></div>
    <div class="dot-right"></div>
    <div class="dot-right"></div>
  </div>

  <div class="dots-left">
    <div class="dot-left"></div>
    <div class="dot-left"></div>
    <div class="dot-left"></div>
    <div class="dot-left"></div>
    <div class="dot-left"></div>

    <div class="dot-left"></div>
    <div class="dot-left"></div>
    <div class="dot-left"></div>
    <div class="dot-left"></div>
    <div class="dot-left"></div>

    <div class="dot-left"></div>
    <div class="dot-left"></div>
    <div class="dot-left"></div>
    <div class="dot-left"></div>
    <div class="dot-left"></div>
  </div>
  
</main>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700;800&display=swap');
main {
    display: grid;
    grid-template-rows: 1fr 1fr; 
    grid-template-columns: 1fr 1fr; 
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    background: radial-gradient(at 30% -5%, #92f2f2, #d6cff1, rgba(255, 255, 255, 0) 25%), radial-gradient(at 50% 70%, #c4f2e5, rgba(255, 255, 255, 0) 30%), radial-gradient(at 70% 0%, #d6cff1, rgba(255, 255, 255, 0) 20%), linear-gradient(75deg, #92f2f2 5%, rgba(255, 255, 255, 0), #a8d0f0, rgba(255, 255, 255, 0), #eed5f2, rgba(255, 255, 255, 0), #d6cff1, rgba(255, 255, 255, 0), #c4f2e5 90%), radial-gradient(at 30% 50%, #92f2f2, rgba(255, 255, 255, 0) 30%), radial-gradient(at 30% 50%, #9cb9fc, rgba(255, 255, 255, 0) 30%), radial-gradient(at 100% 50%, #92f2f2, #c2dcf2, rgba(255, 255, 255, 0) 50%), linear-gradient(115deg, #92f2f2 5%, #a8d0f0 10%, #d6cff1, #eed5f2 20%, #a8d0f0, #a8d0f0 30%, #d6cff1, #c2dcf2 40%, #92f2f2, #a8d0f0 70%);
}

.title {
    color: black;
    font-family: 'Montserrat', sans-serif;
    font-size: 1.5em;
    font-weight: 500;
    grid-row: 1; 
    grid-column: 1;
    padding: 1.5em;
}

.title-down {
    color: black;
    font-family: 'Montserrat', sans-serif;
    font-size: 1.5em;
    font-weight: 500;
    grid-row: 3; 
    grid-column: 3; 
    padding: 1.5em;
}

.sub-title {
  color: black;
    text-align: center;
    font-family: 'Montserrat', sans-serif;
    font-size: 4em;
    font-weight: 500;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

span {
  font-weight: 800;
}

.sub-sub-title {
    grid-row: 1;
    grid-column: 1;
    transform: rotate(-90deg);
    justify-self: start; 
    align-self: end;
    margin-left: -5.6em;
}

/* For the top right corner dots */
.dots-right {
  position: fixed;
  top: 0;
  right: 0;
  display: grid;
  grid-template-columns: repeat(5, 1em);
  grid-template-rows: 1em 1em 1em;
  grid-gap: 1em;
  margin-right: 2em;
}

.dot-right {
  background-color: black;
  width: .5em;
  height: .5em;
  border-radius: 50%;
  margin-top: 2em;
}

/* For the bottom left corner dots */
.dots-left {
  position: fixed;
  bottom: 0; 
  left: 0; 
  display: grid;
  grid-template-columns: repeat(5, 1em);
  grid-template-rows: 1em 1em 1em;
  grid-gap: 1em;
  margin-left: 2.6em; 
  margin-bottom: 2em;
}

.dot-left {
  background-color: black;
  width: .5em;
  height: .5em;
  border-radius: 50%;
}
</style>
