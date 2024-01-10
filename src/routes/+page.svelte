<script>
  import { inview } from 'svelte-inview';
  import { goto } from '$app/navigation'

  let bottomEnter = false;
  let bottomLeave = false;
  let firstEnter = false


  const options = {
    rootMargin: '-91px',
    unobserveOnEnter: false,
  };

  const options1 = {
    rootMargin: '-100px',
    unobserveOnEnter: false,
  };


</script>


<main>

  <nav>

    <div class="item one">
      <a href="/"><img src="home-2.svg" alt="home"></a>
      <a href="/"><img src="story.svg" alt="home"></a>
    </div>
  
    <div class="item-logo">
      <a href="/">
        <div class="logo-con">
          <svg
          class:animate={bottomEnter}
          class="{firstEnter && bottomLeave? 'animateFromBottom' : ''}"     
          
          width="80" height="17" viewBox="0 0 257 55" fill="none" xmlns="http://www.w3.org/2000/svg"
        >
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

  

  

  <img class:animate={bottomEnter} class="{firstEnter && bottomLeave? 'black-line animateFromBottom' : 'black-line'}"     
  src="black-line.svg" alt="background">

  <img class:animate={bottomEnter} class="{firstEnter && bottomLeave? 'bg-img-center animateFromBottom' : 'bg-img-center'}"     
      src="girlBackground.svg" alt="background">
  <img class:animate={bottomEnter} class="{firstEnter && bottomLeave? 'girl animateFromBottom' : 'girl'}"     
      src="animeGirl.png" alt="background">
  <img class:animate={bottomEnter} class="{firstEnter && bottomLeave? 'decal one animateFromBottom' : 'decal one'}"  src="decal.svg" alt="random">
  <img class:animate={bottomEnter} class="{firstEnter && bottomLeave? 'decal two animateFromBottom' : 'decal two'}" src="decal.svg" alt="random">
  <img class:animate={bottomEnter} class="{firstEnter && bottomLeave? 'decal three animateFromBottom' : 'decal three'}" src="decal.svg" alt="random">
  <img class:animate={bottomEnter} class="{firstEnter && bottomLeave? 'decal four animateFromBottom' : 'decal four'}" src="decal.svg" alt="random">
  <svg class:animate={bottomEnter} class="{firstEnter && bottomLeave? 'v-svg animateFromBottom' : 'v-svg'}" 
    xmlns="http://www.w3.org/2000/svg" width="14" height="48" viewBox="0 0 14 48" fill="none">
    <path d="M14 19.1875L-6.09041e-07 5.25427L-8.22321e-07 0.374996L14 14.2585L14 19.1875Z" fill="black"/>
    <path d="M0 27.5L-3.0598e-07 20.5L3.5 23.9997L0 27.5Z" fill="black"/>
    <path d="M-2.15171e-07 32.64L8.4634 23.9486L-9.86185e-07 15.0012L-1.18567e-06 10.4375L13.5625 23.9486L0 37.5625L-2.15171e-07 32.64Z" fill="black"/>
    <path d="M0 47.625L-2.16642e-07 42.6688L14 28.8125L14 33.87L0 47.625Z" fill="black"/>
    </svg>
  <svg class:animate={bottomEnter} class="{firstEnter && bottomLeave? 'dv-svg animateFromBottom' : 'dv-svg'}"  xmlns="http://www.w3.org/2000/svg" width="16" height="160" viewBox="0 0 16 160" fill="none">
    <path d="M0.57383 3.8986L0.573831 -5.52225e-07L13.2073 0L13.2073 4.07133C13.2073 5.29683 12.9544 6.34551 12.4485 7.21735C11.9468 8.08919 11.2251 8.75746 10.2833 9.22217C9.34568 9.68687 8.22299 9.91923 6.91523 9.91923C5.59924 9.91923 4.46626 9.68482 3.51629 9.216C2.57043 8.74718 1.84252 8.06451 1.33258 7.168C0.826747 6.27149 0.57383 5.18169 0.57383 3.8986ZM1.93094 1.52983L1.93094 3.7999C1.93094 4.84446 2.13245 5.71014 2.53547 6.39691C2.93849 7.08369 3.51218 7.59569 4.25653 7.93291C5.00088 8.27013 5.88712 8.43875 6.91523 8.43875C7.93511 8.43875 8.81312 8.27219 9.54925 7.93908C10.2895 7.60598 10.857 7.10837 11.2518 6.44626C11.6507 5.78416 11.8502 4.95961 11.8502 3.97263L11.8502 1.52983L1.93094 1.52983Z" fill="black"/>
    <path d="M13.2073 24.683L2.57248 28.4335L2.57248 28.5816L13.2073 32.3321L13.2073 33.936L0.57383 29.2971L0.57383 27.7179L13.2073 23.0791L13.2073 24.683Z" fill="black"/>
    <path d="M10.049 55.254C10.6741 55.18 11.1594 54.8798 11.5048 54.3534C11.8503 53.827 12.023 53.1813 12.023 52.4164C12.023 51.8571 11.9325 51.3677 11.7516 50.9483C11.5706 50.5329 11.3218 50.208 11.0052 49.9736C10.6885 49.7433 10.3287 49.6282 9.92567 49.6282C9.58845 49.6282 9.29852 49.7084 9.05589 49.8688C8.81736 50.0332 8.61791 50.243 8.45752 50.498C8.30125 50.7529 8.17171 51.0202 8.0689 51.2999C7.9702 51.5795 7.89001 51.8366 7.82832 52.071L7.48287 53.3541C7.39651 53.683 7.27725 54.0491 7.12509 54.4521C6.97293 54.8592 6.76525 55.2478 6.50205 55.618C6.24297 55.9922 5.90986 56.3006 5.50273 56.5433C5.0956 56.7859 4.59593 56.9072 4.00374 56.9072C3.32108 56.9072 2.70421 56.7283 2.15314 56.3705C1.60207 56.0169 1.1641 55.4987 0.839212 54.816C0.514329 54.1375 0.351887 53.3129 0.351887 52.3424C0.351887 51.4377 0.497878 50.6542 0.789863 49.9921C1.08185 49.3341 1.48898 48.816 2.01126 48.4376C2.53354 48.0634 3.14013 47.8516 3.83102 47.8022L3.83102 49.3814C3.35397 49.4226 2.95918 49.5829 2.64663 49.8626C2.3382 50.1463 2.1079 50.5041 1.95574 50.9359C1.80769 51.3719 1.73367 51.8407 1.73367 52.3424C1.73367 52.9264 1.82826 53.4507 2.01743 53.9154C2.21071 54.3801 2.47802 54.7482 2.81936 55.0196C3.1648 55.291 3.56782 55.4267 4.02842 55.4267C4.44789 55.4267 4.78922 55.3095 5.05242 55.0751C5.31561 54.8407 5.52946 54.5323 5.69396 54.1498C5.85846 53.7674 6.00239 53.3541 6.12577 52.9099L6.56991 51.3554C6.85367 50.3684 7.25875 49.587 7.78514 49.0113C8.31153 48.4356 9.00037 48.1477 9.85165 48.1477C10.559 48.1477 11.1759 48.3389 11.7022 48.7214C12.2328 49.1079 12.644 49.6261 12.936 50.2759C13.2321 50.9298 13.3801 51.6597 13.3801 52.4658C13.3801 53.28 13.2341 54.0038 12.9422 54.6371C12.6543 55.2705 12.2595 55.7722 11.7578 56.1423C11.256 56.5165 10.6865 56.7139 10.049 56.7345L10.049 55.254Z" fill="black"/>
    <path d="M11.8502 70.6196L13.2073 70.6196L13.2073 80.0947L11.8502 80.0947L11.8502 76.1221L0.57383 76.1221L0.57383 74.5923L11.8502 74.5923L11.8502 70.6196Z" fill="black"/>
    <path d="M0.573831 94.4146L13.2073 94.4146L13.2073 98.6833C13.2073 99.6703 13.0387 100.48 12.7014 101.114C12.3683 101.747 11.9098 102.216 11.3258 102.52C10.7419 102.825 10.0777 102.977 9.33335 102.977C8.58899 102.977 7.92895 102.825 7.3532 102.52C6.77746 102.216 6.32509 101.749 5.99609 101.12C5.67121 100.491 5.50877 99.6867 5.50877 98.7079L5.50877 95.2535L6.89055 95.2535L6.89055 98.6586C6.89055 99.333 6.98925 99.8759 7.18665 100.287C7.38405 100.702 7.66369 101.003 8.02559 101.188C8.3916 101.377 8.82752 101.472 9.33335 101.472C9.83918 101.472 10.2813 101.377 10.6596 101.188C11.038 100.999 11.3299 100.696 11.5356 100.281C11.7453 99.8656 11.8502 99.3166 11.8502 98.6339L11.8502 95.9444L0.573831 95.9444L0.573831 94.4146ZM6.24901 100.361L0.57383 103.47L0.57383 101.694L6.24901 98.6339L6.24901 100.361Z" fill="black"/>
    <path d="M13.2073 118.66L0.573831 118.66L0.573831 117.13L13.2073 117.13L13.2073 118.66Z" fill="black"/>
    <path d="M15.8552 160L0.36956 160L0.36956 158.215L15.8552 158.215L15.8552 160Z" fill="black"/>
    <path d="M5.00232 139.578L-2.07364e-06 137.876L-1.90735e-06 134.072L13.48 139.057L13.48 142.236L-2.48214e-06 147.221L-2.31585e-06 143.417L5.00232 141.715M5.00232 141.715L8.56301 140.656L5.00232 139.578" fill="black"/>
    <path d="M9.73742 132.769C9.73742 133.89 10.646 134.798 11.7669 134.798C12.8878 134.798 13.7964 133.89 13.7964 132.769C13.7964 131.648 12.8878 130.739 11.7669 130.739C10.646 130.739 9.73742 131.648 9.73742 132.769Z" fill="black"/>
  </svg>

<div class="controls">
  <div class="trigger" use:inview={options} 
  on:inview_enter={() => {
    bottomEnter = true;
    bottomLeave = false;
    firstEnter = true
  }} 
  on:inview_leave={() => {
    bottomEnter = false;
    bottomLeave = true;
  }}>
    <button on:click={() => goto('/about')} class:animate={bottomEnter} class="{firstEnter && bottomLeave? 'animateFromBottom' : ''}"> <span>Discover </span>
      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M14.4299 5.93018L20.4999 12.0002L14.4299 18.0702" stroke="#0B0C10" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M3.5 12H20.33" stroke="#0B0C10" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </button>
  </div>

  <div class="links" class:slide-left-content={bottomEnter} class:animate={bottomEnter} >
    <a href="/">Home</a>
    <a href="/">Guide book</a>
    <a href="/">Settings</a>
  </div>
</div>
<div class:animate={bottomEnter}
    class="{firstEnter && bottomLeave? 'bottom-bars animateFromBottom' : 'bottom-bars'}"  >
  <svg class="white-bar" xmlns="http://www.w3.org/2000/svg" width="984" height="94" viewBox="0 0 984 94" fill="none">
    <path d="M-555.93 2.78992H980.25L889.87 92.0499H-649L-557.26 1.43994" fill="white"/>
    <path d="M-555.93 2.78992H980.25L889.87 92.0499H-649L-557.26 1.43994" stroke="white" stroke-width="3" stroke-miterlimit="10"/>
  </svg>

  <svg class="black-bar" xmlns="http://www.w3.org/2000/svg" width="626" height="285" viewBox="0 0 626 285" fill="none">
    <path d="M441.09 223.08H533.29V99.08L624.44 4V172.14L487.709 311.55H4L96.29 220.4H182.08V131.93L271.46 41.67V223.08H348.3V132.38L441.09 39.43" fill="black"/>
    <path d="M441.09 223.08H533.29V99.08L624.44 4V172.14L487.709 311.55H4L96.29 220.4H182.08V131.93L271.46 41.67V223.08H348.3V132.38L441.09 39.43" stroke="white" stroke-width="3" stroke-miterlimit="10"/>
  </svg>

  <svg class="vertical-bars" xmlns="http://www.w3.org/2000/svg" width="129" height="45" viewBox="0 0 129 45" fill="none">
    <path d="M127.813 26.23L109.16 44.8391H123.15L127.813 39.7176V26.23Z" fill="black"/>
    <path d="M127.813 0L121.9 0L76.936 44.8392H90.3435L128.25 6.99608L127.813 0Z" fill="black"/>
    <path d="M101.298 0L89.4674 0L44.9617 44.8392H57.8139L101.298 0Z" fill="black"/>
    <path d="M68.859 0L56.315 0L11.9888 44.8392H25.0627L68.859 0Z" fill="black"/>
    <path d="M35.7194 0L23.4794 0L0 23.7306L0 36.6588L35.7194 0Z" fill="black"/>
    <path d="M5.75268 0L0 0L0 5.99544L5.75268 0Z" fill="black"/>
  </svg>

  <svg class:animate={bottomEnter} class="{firstEnter && bottomLeave? 'white-line one animateFromBottom' : 'white-line one'}"
    xmlns="http://www.w3.org/2000/svg" width="101" height="545" viewBox="0 0 101 545" fill="none">
    <path d="M99.3501 1.81006C61.8201 39.3401 1.49023 113.07 1.49023 155.97V544.71" stroke="white" stroke-width="3" stroke-miterlimit="10"/>
  </svg>
  
    <svg class:animate={bottomEnter} class="{firstEnter && bottomLeave? 'white-line two animateFromBottom' : 'white-line two'}"
      xmlns="http://www.w3.org/2000/svg" width="612" height="811" viewBox="0 0 612 811" fill="none">
      <path d="M610.781 -91.8896C610.781 -91.8896 75.9309 431.35 42.4209 464.86C8.9109 498.37 2.21094 537.25 2.21094 585.5V810.7" stroke="white" stroke-width="3" stroke-miterlimit="10"/>
    </svg>


    <svg class:animate={bottomEnter} class="{firstEnter && bottomLeave? 'white-line three animateFromBottom' : 'white-line three'}"
      xmlns="http://www.w3.org/2000/svg" width="167" height="627" viewBox="0 0 167 627" fill="none">
      <path d="M165.601 1.22021C126.831 39.9902 74.0605 94.8702 74.0605 153.85V497.01C74.0605 534.54 34.2305 582.8 2.06055 625.7" stroke="white" stroke-width="3" stroke-miterlimit="10"/>
    </svg>

    <svg class:animate={bottomEnter} class="{firstEnter && bottomLeave? 'white-line four animateFromBottom' : 'white-line four'}"
      xmlns="http://www.w3.org/2000/svg" width="371" height="315" viewBox="0 0 371 315" fill="none">
      <path d="M221.95 1.9502C221.95 1.9502 43.7402 185.34 19.7402 209.34C-4.26985 233.35 3.45011 309.43 3.45011 334.45C3.45011 359.47 41.4301 413.09 75.3901 429.18C109.35 445.27 134.37 454.2 154.93 454.2H1092.37V220.06H756.36" stroke="white" stroke-width="3" stroke-miterlimit="10"/>
    </svg>
    
</div>
</main>



<style>

  .animate {
    animation-timing-function: cubic-bezier(.29,.63,.7,1.05);
  }



  .white-line {
    position: absolute;
    z-index: 2;
  }

  .white-line.one {
    bottom: 80px;
    left: 65px;
    
  }

  .white-line.two {
    bottom: 100px;
    right: 0px;
  }

  .white-line.three {
    bottom: 100px;
    right: 340px;
  }

  .white-line.four {
    bottom: 0px;
    right: 30px;
  }


  .black-line {
    position: absolute;
    top: 200px;
    right: 50px;
    height: 200px;
    width: 3px;
    object-fit: cover;
  }

  .black-line.animate {
    animation: longline 1s   0s 1 forwards;
  }

  .black-line.animateFromBottom {
    animation: shortline 1s 0s 1 forwards;
  }

  @keyframes longline {
    0% {
      height: 200px;
    width: 3px;
    }
    100% {
      height: 592px;
    width: 3px;

    }
  }

  @keyframes shortline {
    0% {
      height: 592px;
    width: 3px;

    }
    100% {
      height: 200px;
    width: 3px;

    }
  }

  .v-svg {
    position: absolute;
    bottom: 600px;
    left: 70px;
    opacity: 0;
  }

  .v-svg.animate {
    animation: svgSlide 1s   0s 1 forwards;
  }

  .v-svg.animateFromBottom {
    animation: reverseSvgSlide 1s 0s 1 forwards;
  }

  .dv-svg {
    position: absolute;
    bottom: 349px;
    left: 70px;
    opacity: 0;
  }

  .dv-svg.animate {
    animation: svgSlide 1s   0s 1 forwards;
  }

  .dv-svg.animateFromBottom {
    animation: reverseSvgSlide 1s 0s 1 forwards;
  }

  @keyframes svgSlide {
    0% {
      transform: translateX(-20px);
      opacity: 0;
    }
    100% {
      transform: translateX(0);
      opacity: 1;
    }
  }

  @keyframes reverseSvgSlide {
    0% {
      transform: translateX(0);
      opacity: 1;
    }
    100% {
      transform: translateX(-20px);
      opacity: 0;
    }
  }



  .vertical-bars {
    position: absolute;
    bottom: 62px;
    left: 92px;
    z-index: 3;
  }

  .bottom-bars {
    position: absolute;
    bottom: 0;
    right: 0;
    width: 100%;
    height: 280px;
    z-index: 2;
    transform: translateY(100%);
  }

  .bottom-bars.animate {
    animation: barSlide 1s   0s 1 forwards;
  }

  @keyframes barSlide {
    0% {
      transform: translateY(100%);
      opacity: 0;
    }
    100% {
      transform: translateY(0);
      opacity: 1;
    }
  }

  .bottom-bars.animateFromBottom {
    animation: reverseBarSlide 1s 0s 1 forwards;
  }

  @keyframes reverseBarSlide {
    0% {
      transform: translateY(0);
      opacity: 1;
    }
    100% {
      transform: translateY(100%);
      opacity: 0;
    }
  }

  .white-bar {
    position: absolute;
    bottom: 38px;
    right: 386px;
    z-index: 2;
  }

  .black-bar {
    position: absolute;
    bottom: -20px;
    right: 424px;
    z-index: 1;
  }

  .controls {
    align-self: center;
  }

  .controls {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }

  .links {
    position: absolute;
    display: none;
    margin-bottom: 74px;
    align-items: center;
    justify-content: center;
    gap: 64px;
    z-index: 3;
  }

  .links.animate {
    display: flex;
    animation: linksSlide 1s   0s 1 forwards;
  }

  @keyframes linksSlide {
    0% {
      transform: translateY(100%);
    }
    100% {
      transform: translateY(0);
    }
  }

  .slide-left-content > * {
  --stagger: 0;
  --delay: 300ms;
  --start: .5s;
  animation: slide-left 1s both 1;
  animation-delay: calc(var(--start) + var(--stagger) * var(--delay));
}

.slide-left-content > *:nth-child(1) { --stagger: 1; }
.slide-left-content > *:nth-child(2) { --stagger: 2; }
.slide-left-content > *:nth-child(3) { --stagger: 3; }
.slide-left-content > *:nth-child(4) { --stagger: 4; }

@keyframes slide-left {
  0% {
    transform: translateX(-20px);
    opacity: 0
  }

  to {
    transform: translateX(0);
    opacity: 100
  }
}



button.animate:hover > svg {
    animation: shake 1s infinite;
  }

  @keyframes shake {
  0% { transform: translate(1px, 1px) scale(3) rotate(0deg); }
  10% { transform: translate(-1px, 1px) rotate(-1deg); }
  20% { transform: translate(-1px, -1px) rotate(1deg); }
  30% { transform: translate(1px, 1px) scale(2) rotate(0deg); }
  40% { transform: translate(1px, -1px) rotate(1deg); }
  50% { transform: translate(-1px, 1px) scale(1) rotate(-1deg); }
  60% { transform: translate(-1px, 1px) rotate(0deg); }
  70% { transform: translate(1px, 1px) scale(2) rotate(-1deg); }
  80% { transform: translate(-1px, -1px) rotate(1deg); }
  90% { transform: translate(-1px, 1px) rotate(0deg); }
  100% { transform: translate(1px, 1px) scale(2) rotate(-1deg); }
}



  main {
    display: flex;
    flex-direction: column;
    align-items: stretch;
    justify-content: space-between;
    position: relative;
    width: 100%;
    overflow: hidden;
    min-height: 100vh;
    height: 850px;
  }

  .decal {
    position: absolute;
    object-fit: cover;
    z-index: 1;
  }

  .decal.one{
    bottom: 435px;
    right: 508px;
  }

  .decal.one.animate {
    animation: decalSlide 1s forwards;
}

.decal.one.animateFromBottom {
    animation: reverseDecalSlide 1s forwards;
}

@keyframes decalSlide {
    0% {
        transform: rotate(0deg) translate(0, 0) scale(1);
    }
    100% {
        transform: translate(220px, -158px) rotate(210deg)  scale(2.5);
    }
}

  @keyframes reverseDecalSlide {
    0% {
        transform: translate(220px, -158px) rotate(210deg)  scale(2.5);

    }
    100% {
      transform: rotate(0deg) translate(0, 0) scale(1);
    }
  }


  .decal.two{
    bottom: 482px;
    right: 563px;
    transform: rotate(-8.523deg);
  }

  .decal.two.animate {
    animation: decalSlide2 1s forwards;
}

.decal.two.animateFromBottom {
    animation: reverseDecalSlide2 1s forwards;
}

@keyframes decalSlide2 {
    0% {
        transform: rotate(0deg) translate(0, 0) scale(1);
    }
    100% {
        transform: translate(180px, -110px) rotate(210deg)  scale(2.5);
    }
}

  @keyframes reverseDecalSlide2 {
    0% {
      transform: translate(180px, -110px) rotate(210deg)  scale(2.5);
    }
    100% {
      transform: rotate(0deg) translate(0, 0) scale(1);
    }
  }


  .decal.three{
    bottom: 490px;
    right: 680px;
    transform: rotate(8.523deg);
    transform: scaleX(-1)
  }


  
  .decal.three.animate {
    animation: decalSlide3 1s forwards;
}

.decal.three.animateFromBottom {
    animation: reverseDecalSlide3 1s forwards;
}

@keyframes decalSlide3 {
    0% {
      transform: translate(0, 0) rotate(0deg) scaleX(-1) scale(1);
      
    }
    100% {
        transform: translate(-180px, -100px) rotate(150deg) scaleX(-1) scale(2.5);
    }
}

  @keyframes reverseDecalSlide3 {
    0% {
      transform: translate(-180px, -100px) rotate(150deg) scaleX(-1) scale(2.5);
    }
    100% {
      transform: translate(0, 0) rotate(0deg) scaleX(-1) scale(1);
    }
  }

  .decal.four{
    bottom: 460px;
    right: 734px;
    transform: rotate(-8.523deg);
    transform: scaleX(-1)
  }

  .decal.four.animate {
    animation: decalSlide4 1s forwards;
}

.decal.four.animateFromBottom {
    animation: reverseDecalSlide4 1s forwards;
}

@keyframes decalSlide4 {
    0% {
      transform: translate(0, 0) rotate(0deg) scaleX(-1) scale(1);
      
    }
    100% {
      transform: translate(-230px, -130px) rotate(150deg) scaleX(-1) scale(2.5);
    }
}

  @keyframes reverseDecalSlide4 {
    0% {
      transform: translate(-230px, -130px) rotate(150deg) scaleX(-1) scale(2.5);
    }
    100% {
      transform: translate(0, 0) rotate(0deg) scaleX(-1) scale(1);
    }
  }


  .trigger {
    z-index: 3;
  }

  button {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: -10px;
    border-radius: 100px;
    background: #BBFF1A;
    box-shadow: 0px 0px 60px 20px rgba(187,255,26,0.75);
    padding: 30px;
    color: #0F0F15;
    font-size: 28px;
    font-weight: 600;
    border: none;
    z-index: 4;
    position: relative;
    cursor: pointer;
    transform: translateY(-54px);
  }

  button > svg {
    opacity: 0;;
  }

  button.animate {
    animation: buttonSlide 1s   0s 1 forwards;
  }
  button.animate > svg {
    opacity: 1;

    animation: buttonSvgAppear 1s   0s 1 forwards;
  }

  @keyframes buttonSvgAppear {
    0% {
      opacity: 0;
    }
    100% {
      opacity: 1;
    }
  }

  button.animateFromBottom {
    animation: reverseSlide 1s 0s 1 ;

  }

  button.animateFromBottom > svg {
    animation: reverseButtonSvgAppear 1s   0s 1 forwards;
  }
  @keyframes reverseButtonSvgAppear {
    0% {
      opacity: 1;
    }
    100% {
      opacity: 0;
    }
  }


  @keyframes buttonSlide {
    0% {
      gap: 0px;
      transform: translateY(-54px);
    }
    100% {
      transform: translateY(-190px);
      gap: 76px;
    }
  }

  @keyframes reverseSlide {
    0% {
      gap: 76px;
      transform: translateY(-190px);
    }
    100% {
      gap: 0px;
      transform: translateY(-54px);
    }
  }


  .girl {
    position: absolute;
    width: 434px;
    height: 650px;
    bottom: 0;
    right: 28%;
    object-fit: contain;
    z-index: 1;
  }

  .girl.animate {
    animation: scale 1s   1 forwards;
  }

  .girl.animateFromBottom {
    animation: reverse-scale 1s   0s 1 forwards;
  }

  @keyframes scale {
    0% {
      transform: scale(1);
    }
    100% {
      transform: scale(1.3);
      
    }
  }

  @keyframes reverse-scale {
    0% {
      transform: scale(1.3);
    }
    100% {
      transform: scale(1);
      
    }
  }

  .bg-img-center {
    position: absolute;
    top: 173px;
    width: 100%;
    object-fit: cover;
    z-index: 0;
    filter: blur(2px);
  }

  .bg-img-center.animate {
    animation: blur 1s   1 forwards;
  }

  .bg-img-center.animateFromBottom {
    animation: reverse-blur 1s   0s 1 forwards;
  }

  @keyframes reverse-blur {
    0% {
      transform: scale(0.6);
      filter: blur(0px);
    }
    100% {
      transform: scale(1);
      filter: blur(2px);
    }
  }

  @keyframes blur {
    0% {
      transform: scale(1);
      filter: blur(2px);
    }
    100% {
      transform: scale(0.6);
      filter: blur(0px);
    }
  }



  nav {
    display: flex;
    justify-content: space-between;
    padding: 45px 71px;
    position: relative;
    z-index: 0;

  }

  .links > a {
    color: #0F0F15;
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
  text-decoration: none;
  z-index: 2;

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

  .logo-con > svg.animate {
    animation: enlarge 1s   0s 1 forwards;
  }

  .logo-con > svg.animateFromBottom  {
    animation: mini 1s   0s 1 ;
  }

  @keyframes enlarge {
    0% {
      transform: scale(1);
    }
    100% {
      transform: scale(3);
    }
  }

  @keyframes mini {
    0% {
      transform: scale(3);
    }
    100% {
      transform: scale(1);
    }
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