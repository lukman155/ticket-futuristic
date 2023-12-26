<nav>

  <div class="item one">
    <a href="/"><img src="home-2.svg" alt="home"></a>
    <a href="/"><img src="story.svg" alt="home"></a>
  </div>

  <div class="item-logo">
    <a href="/">
      <div class="logo-con">
      <svg width="257" height="55" viewBox="0 0 257 55" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M204.881 54.2286L224.397 26.3815L205.807 0H218.226L231.031 18.8219L243.528 0H255.407L237.434 26.0729L256.333 54.2286H244.068L230.723 33.5554L216.76 54.2286H204.881Z" fill="black"/>
        <path d="M176.249 39.1092V29.9297H202.939V39.1092H176.249Z" fill="black"/>
        <path d="M148.335 55C137.073 55 128.356 46.5147 128.356 35.4839C128.356 24.6073 136.996 16.1221 148.258 16.1221C159.597 16.1221 168.237 24.5302 168.237 35.4839C168.237 46.5147 159.597 55 148.335 55ZM148.258 45.5891C153.966 45.5891 157.9 41.4236 157.9 35.561C157.9 29.6985 153.889 25.6101 148.258 25.6101C142.627 25.6101 138.693 29.7756 138.693 35.561C138.693 41.4236 142.627 45.5891 148.258 45.5891Z" fill="black"/>
        <path d="M103.612 54.2287L87.1819 16.9707H98.2899L107.315 40.498L116.495 16.9707H127.217L110.863 54.2287H103.612Z" fill="black"/>
        <path d="M61.7346 55C51.5523 55 43.8384 46.669 43.8384 35.6382C43.8384 24.6073 51.5523 16.1992 61.6574 16.1992C66.1315 16.1992 69.9113 17.8191 72.534 20.519V16.9706H82.562V54.2286H72.534V50.6803C69.9113 53.3801 66.1315 55 61.7346 55ZM63.5859 45.6662C69.217 45.6662 73.074 41.5007 73.074 35.5611C73.074 29.6985 69.217 25.533 63.5859 25.533C58.0319 25.533 54.175 29.6985 54.175 35.5611C54.175 41.5007 58.0319 45.6662 63.5859 45.6662Z" fill="black"/>
        <path d="M0 54.2286V0H21.2132C31.704 0 38.8008 6.63393 38.8008 15.8134C38.8008 24.3759 33.0925 30.2384 24.2216 31.3955L42.3492 54.2286H29.6213L12.2651 31.5498H10.4909V54.2286H0ZM20.2875 8.5624H10.4909V23.373H20.2875C25.4558 23.373 28.3871 20.5961 28.3871 15.9677C28.3871 11.8022 25.4558 8.5624 20.2875 8.5624Z" fill="black"/>
        </svg>
      </div>
      </a>
  </div>

  <div class="item two">
    <a class="overlap" href="/"><img src="paypal.svg" alt="home"></a>
    <a href="/"><img src="apple.svg" alt="home"></a>
  </div>

</nav>


<main>
  <img class="bg-img-center" src="girlBackground.svg" alt="background">
  <img class="girl" src="animeGirl.png" alt="background">
  <img class="decal one" src="decal.svg" alt="random">
  <img class="decal two" src="decal.svg" alt="random">
  <img class="decal three" src="decal.svg" alt="random">
  <img class="decal four" src="decal.svg" alt="random">
  <button class="yellow-button"> <span>Discover </span><svg class="hidden" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
    <path d="M14.4299 5.93018L20.4999 12.0002L14.4299 18.0702" stroke="#0B0C10" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
    <path d="M3.5 12H20.33" stroke="#0B0C10" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
    </svg>
    </button>
</main>



<style>

  main {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-end;
    position: relative;
    overflow: hidden;
    width: 100%;
    min-height: 100vh;
    height: 773px;
  }

  .decal {
    position: absolute;
    object-fit: cover;
    z-index: 0;
  }

  .decal.one{
    bottom: 435px;
    right: 608px;
  }

  .decal.two{
    bottom: 482px;
    right: 663px;
    transform: rotate(-8.523deg);
  }

  .decal.three{
    bottom: 490px;
    right: 800px;
    transform: rotate(8.523deg);
    transform: scaleX(-1)
  }

  .decal.four{
    bottom: 460px;
    right: 864px;
    transform: rotate(-8.523deg);
    transform: scaleX(-1)

  }

  button {
    position: relative;
    bottom: 54px;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 76px;
    border-radius: 100px;
background: #BBFF1A;
box-shadow: 0px 0px 60px 20px rgba(187,255,26,0.75);
width: 194px;
height: 82px;
z-index: 1;
color: #0F0F15;
font-size: 28px;
font-style: normal;
font-weight: 600;
line-height: normal;
border: none;
  }

  .hidden {
    display: none;
  }




  .girl {
    position: absolute;
    width: 434px;
    height: 650px;
    bottom: 0;
    right: 32%;
    object-fit: cover;
    z-index: 0;
  }

  .bg-img-center {
    position: absolute;
    top: 35px;
    left: -3%;
    width: 106%;
    object-fit: cover;
    z-index: 0;
    filter: blur(2px);
  }

  nav {
    display: flex;
    justify-content: space-between;
    padding: 45px 71px;
  }

  .item {
    position: relative;
    display: flex;
  }

  .item-logo {
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .logo-con > svg {
    width: 80px;
    height: 17px;
  }

  .one {
    gap: 8px;
  }

  .two {
    gap: 0px;
  }

  .overlap {
    position: relative;
    right: -12px;
  }

  .item > a {
    width: 48px;
    height: 48px;
    border-radius: 50%;
    background-color: #E0E2F0;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .item.two > a {
    width: 56px;
    height: 56px;
  }

  .item > a:hover {
    background-color: #d7d7e5;
  }

  .item > a:active {
    background-color: #c5c5d1;
  }

</style>