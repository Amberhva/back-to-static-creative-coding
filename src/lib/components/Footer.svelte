<script>
</script>

<section class="container">
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="border"></div>

<svg>
  <defs>
    <filter id="bubble">
      <feGaussianBlur in="SourceGraphic"
      stdDeviation="0" />
      <feColorMatrix in="name" mode="matrix"
      values="1 0 0 0 0
              0 1 0 0 0
              0 0 1 0 0
              0 0 0 30 -15" />
      <feBland in="SourceGraphic" />
    </filter>
  </defs>
</svg>

  <article>
    <h2>SPATwater</h2>
    <h3>Een nieuwe generatie hydrologen</h3>
    <svg
      xmlns="http://www.w3.org/2000/svg"
      width="44"
      height="44"
      viewBox="0 0 44 44"
      fill="none"
    >
      <path
        d="M33.6163 33.6215H28.7296V25.964C28.7296 24.138 28.6926 21.7882 26.1831 21.7882C23.6353 21.7882 23.2461 23.7752 23.2461 25.8293V33.6215H18.3593V17.875H23.0536V20.0213H23.1168C23.7728 18.7838 25.3678 17.4776 27.7506 17.4776C32.7021 17.4776 33.6178 20.7365 33.6178 24.9783L33.6163 33.6215ZM12.8401 15.7204C11.2671 15.7204 10.0035 14.4471 10.0035 12.881C10.0035 11.3163 11.2685 10.0444 12.8401 10.0444C14.4076 10.0444 15.6781 11.3163 15.6781 12.881C15.6781 14.4471 14.4063 15.7204 12.8401 15.7204ZM15.2904 33.6215H10.3899V17.875H15.2904V33.6215ZM36.0611 5.5H7.93689C6.59077 5.5 5.50177 6.56425 5.50177 7.87738V36.1227C5.50177 37.437 6.59077 38.5 7.93689 38.5H36.0571C37.4018 38.5 38.5018 37.437 38.5018 36.1227V7.87738C38.5018 6.56425 37.4018 5.5 36.0571 5.5H36.0611Z"
        fill="white"
      />
    </svg>
  </article>

  <article>
    <h2>Over</h2>
    <ul>
      <li><a href="#over">Over ons</a></li>
      <li><a href="#klimaatadaptatie">Klimaatadaptatie</a></li>
      <li><a href="#waterkwaliteit">Waterkwaliteit</a></li>
      <li><a href="#brain">b-RAIN</a></li>
      <li><a href="#projecten">Projecten</a></li>
      <li><a href="#kennisbank">Kennisbank</a></li>
    </ul>
  </article>

  <article>
    <h2>Bedrijf</h2>
    <ul>
      <li><a href="#team">Team</a></li>
    </ul>
  </article>

  <article>
    <h2>Contact</h2>
    <ul>
      <li><a href="#contact">Neem contact op</a></li>
    </ul>
  </article>
</section>

<style>
  :root {
    --spat: #7faec5;
    --lg-bg: #fafafa;
    --green: #4ecd5d;
    --darkblue: #384b61;
  }
  
  h2 {
    color: var(--spat);
    font-size: 1.3rem;
    z-index: 2;
  }

  h3 {
    color: white;
    font-size: 1rem;
  }

  svg {
    width: 1.7rem;
    margin-top: 0.5rem;
    margin-left: -0.3em;
  }

  article {
    z-index: 2;
  }

  ul {
    list-style-type: none;
    text-decoration: none;
    cursor: pointer;
  }

  li,
  a {
    text-decoration: none;
    color: white;
    cursor: pointer;
  }

  section {
    height: 100vh;
    background-color: var(--darkblue);
  }

  .container {
    padding: 2rem;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    width: 100%;
    height: 100%;
    overflow: hidden;
    position: relative;
    filter: url(#bubble);
  }

  .particle {
    width: 100px;
    height: 100px;
    top: -20%;
    background: linear-gradient(180deg, #87ed93 0%, rgb(74, 168, 205) 100%);
    position: absolute;
    border-radius: 50%;
    animation: fall 15s infinite;
  }

  @keyframes fall {
    0% {top: -20%;}
    20% {top: 0%;}
    80% {top: 85%;}
    100% {top: 100%;}
  }

  .particle:nth-of-type(2n) {
    width: 60px;
    height: 60px;
  }

  .particle:nth-of-type(3n) {
    width: 120px;
    height: 120px;
  }

.particle:nth-of-type(1) {
    left: 30%;
    animation-delay: 1s;
  }

  .particle:nth-of-type(2) {
    left: 60%;
    animation-delay: 2s;
  }

  .particle:nth-of-type(3) {
    left: 25%;
    animation-delay: 3s;
  }

  .particle:nth-of-type(4) {
    left: 75%;
    animation-delay: 4s;
  }

  .particle:nth-of-type(5) {
    left: 35%;
    animation-delay: 5s;
  }

  .particle:nth-of-type(6) {
    left: 50%;
    animation-delay: 6s;
  }

  .particle:nth-of-type(7) {
    left: 65%;
    animation-delay: 7s;
  }

  .particle:nth-of-type(8) {
    left: 30%;
    animation-delay: 8s;
  }

  .particle:nth-of-type(9) {
    left: 55%;
    animation-delay: 9s;
  }

  .particle:nth-of-type(10) {
    left: 55%;
    animation-delay: 10s;
  }

  .particle:nth-of-type(11) {
    left: 35%;
    animation-delay: 11s;
  }

  .particle:nth-of-type(12) {
    left: 50%;
    animation-delay: 12s;
  }

   .particle:nth-of-type(13) {
    left: 65%;
    animation-delay: 13s;
  }

  .particle:nth-of-type(14) {
    left: 40%;
    animation-delay: 14s;
  }

  .particle:nth-of-type(15) {
    left: 60%;
    animation-delay: 15s;
  }
  
  @media screen and (min-width: 720px) {
    h2 {
      margin-bottom: 1.5rem;
      margin-top: 2rem;
    }
    section {
      height: 50vh;
    }
    .container {
      flex-direction: row;
    }

    li {
      margin-bottom: 0.5rem;
    }
  }
</style>
