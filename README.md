<svg
  version="1.1"
  id="kitty"
  xmlns="http://www.w3.org/2000/svg"
  xmlns:xlink="http://www.w3.org/1999/xlink"
  x="0px"
  y="0px"
  viewBox="0 0 600 300"
  style="
    background-size: 0.2em 100%;
    font: 7em Open Sans, Impact;
    text-transform: uppercase;
    margin: 0;
  "
  xml:space="preserve"
>
  <style>
    @import url(https://fonts.googleapis.com/css?family=Open+Sans:800);
    .text {
      fill: none;
      stroke-width: 3;
      stroke-linejoin: round;
      stroke-dasharray: 70 330;
      stroke-dashoffset: 0;
      -webkit-animation: stroke 5s infinite linear;
      animation: stroke 5s infinite linear;
    }
    .text:nth-child(5n + 1) {
      stroke: #ee6352;
      -webkit-animation-delay: -1s;
      animation-delay: -1s;
    }
    .text:nth-child(5n + 2) {
      stroke: #59cd90;
      -webkit-animation-delay: -2s;
      animation-delay: -2s;
    }
    .text:nth-child(5n + 3) {
      stroke: #3fa7d6;
      -webkit-animation-delay: -3s;
      animation-delay: -3s;
    }
    .text:nth-child(5n + 4) {
      stroke: #fac05e;
      -webkit-animation-delay: -4s;
      animation-delay: -4s;
    }
    .text:nth-child(5n + 5) {
      stroke: #f79d84;
      -webkit-animation-delay: -5s;
      animation-delay: -5s;
    }
    @-webkit-keyframes stroke {
      100% {
        stroke-dashoffset: -400;
      }
    }
    @keyframes stroke {
      100% {
        stroke-dashoffset: -400;
      }
    }
  </style>
  <!-- Symbol-->
  <symbol id="s-text">
    <text text-anchor="middle" x="50%" y="50%" dy=".35em">H T G</text>
  </symbol>
  <!-- Duplicate symbols-->
  <use class="text" xlink:href="#s-text"></use>
  <use class="text" xlink:href="#s-text"></use>
  <use class="text" xlink:href="#s-text"></use>
  <use class="text" xlink:href="#s-text"></use>
  <use class="text" xlink:href="#s-text"></use>
</svg>
