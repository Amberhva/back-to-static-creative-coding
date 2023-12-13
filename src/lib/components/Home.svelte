<script> 
</script>

<main>
  <h2 class="title">// SPATWATER</h2>
  <h2 class="title-down">SPATWATER \\</h2>
  <h3 class="sub-title">EEN <span>NIEUWE GENERATIE</span> HYDROLOGEN</h3>
  <h3 class="sub-sub-title">CONCREET OP WATER EN BODEM</h3>
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
    animation: holo 12s ease infinite;
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

.title-down {
    color: black;
    font-family: 'Montserrat', sans-serif;
    font-size: 1.5em;
    font-weight: 500;
    grid-row: 3; 
    grid-column: 3; 
    padding: 1.5em;
}

.sub-sub-title {
    grid-row: 1;
    grid-column: 1;
    transform: rotate(-90deg);
    justify-self: start; 
    align-self: end;
    margin-left: -5.6em;
}

@keyframes holo {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 100%;
  }
  100% {
    background-position: 0% 50%;
  }
}
</style>
