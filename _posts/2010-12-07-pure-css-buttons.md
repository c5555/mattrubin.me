---
layout: post
title: Pure CSS Buttons
status: archived
---

<div class="demo">
	<div id="button-demo"><div class="centered-cell">
		<a class="green arrow button">Click Me!<div>▸</div></a>
		<br><br>
		<a class="blue arrow button">Click Me!<div>▸</div></a>
		<br><br>
		<a class="red arrow button">Click Me!<div>▸</div></a>
	</div></div>
</div>

Inspired by [Chad Hietala](http://drbl.in/GgX) over at [Dribbble](http://dribbble.com/).

Code:

	<a class="red arrow button">Click Me!<div>▸</div></a>

Don’t want the arrow in the rollover state? Then the code becomes even simpler:

	<a class="red button">Click Me!</a>




<style>
div.demo{
	display:block;
	padding:3px;
	border:1px solid #CCC;
	background:white;
	border-radius:3px;
	-moz-border-radius:3px;
	overflow:hidden;
	-webkit-box-shadow:1px 1px 3px rgba(0,0,0,.2);
	margin:10px;
	max-width:460px;
}

div.demo::selection{
	background:transparent;
}

#button-demo {
  display: table;
  width: 100%;
  height: 300px;
  padding: 30px;
  background-color: #dddddd;
  background-image: -moz-linear-gradient(top, #eeeeee 0%, #f0f0f0 20%, #eeeeee 100%);
  background-image: -webkit-gradient(linear, left top, left bottom, color-stop(0, #eeeeee), color-stop(0.2, #f0f0f0), color-stop(1, #eeeeee));
  font: 13px/1.231 sans-serif;
  *font-size: small;
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
  -webkit-user-select: none;
  -moz-user-select: none;
  user-select: none; }
  #button-demo .centered-cell {
    width: 125px;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
    margin: auto;
    vertical-align: middle;
    display: table-cell;
    text-align: center; }
  #button-demo .button {
    -webkit-box-shadow: 0px 1px 2px red;
    -moz-box-shadow: 0px 1px 2px red;
    box-shadow: 0px 1px 2px red;
    display: inline-block;
    position: relative;
    overflow: hidden;
    border: 1px solid;
    padding: 7px 15px;
    margin: auto;
    cursor: pointer;
    text-transform: uppercase;
    letter-spacing: 0.07em;
    font-weight: bold;
    text-decoration: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    user-select: none;
    -webkit-border-radius: 6px;
    -moz-border-radius: 6px;
    border-radius: 6px;
    -webkit-box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.2);
    -moz-box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.2);
    box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.2);
    -webkit-transition: padding 0.2s linear;
    -moz-transition: padding 0.2s linear;
    -o-transition: padding 0.2s linear;
    transition: padding 0.2s linear; }
    #button-demo .button.blue {
      color: #103661;
      border-color: #133e6f;
      text-shadow: 0px 1px 0px #3f78b2;
      background-image: -moz-linear-gradient(top, #306bb3, #245188);
      background-image: -webkit-gradient(linear, left top, left bottom, color-stop(0, #306bb3), color-stop(1, #245188));
      -webkit-box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.2), inset 0px 1px 0px #98b5d9;
      -moz-box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.2), inset 0px 1px 0px #98b5d9;
      box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.2), inset 0px 1px 0px #98b5d9; }
      #button-demo .button.blue:active {
        background-image: -moz-linear-gradient(top, #2d64a7, #275894);
        background-image: -webkit-gradient(linear, left top, left bottom, color-stop(0, #2d64a7), color-stop(1, #275894)); }
    #button-demo .button.green {
      color: #455e10;
      border-color: #405c01;
      text-shadow: 0px 1px 0px #8fb541;
      background-image: -moz-linear-gradient(top, #8ab62f, #698a24);
      background-image: -webkit-gradient(linear, left top, left bottom, color-stop(0, #8ab62f), color-stop(1, #698a24));
      -webkit-box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.2), inset 0px 1px 0px #c3db99;
      -moz-box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.2), inset 0px 1px 0px #c3db99;
      box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.2), inset 0px 1px 0px #c3db99; }
      #button-demo .button.green:active {
        background-image: -moz-linear-gradient(top, #81aa2c, #729627);
        background-image: -webkit-gradient(linear, left top, left bottom, color-stop(0, #81aa2c), color-stop(1, #729627)); }
    #button-demo .button.red {
      color: #612010;
      border-color: #5f1b02;
      text-shadow: 0px 1px 0px #ba4b42;
      background-image: -moz-linear-gradient(top, #b44a2f, #8c3a25);
      background-image: -webkit-gradient(linear, left top, left bottom, color-stop(0, #b44a2f), color-stop(1, #8c3a25));
      -webkit-box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.2), inset 0px 1px 0px #dea599;
      -moz-box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.2), inset 0px 1px 0px #dea599;
      box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.2), inset 0px 1px 0px #dea599; }
      #button-demo .button.red:active {
        background-image: -moz-linear-gradient(top, #a8452c, #983f28);
        background-image: -webkit-gradient(linear, left top, left bottom, color-stop(0, #a8452c), color-stop(1, #983f28)); }
    #button-demo .button.arrow > div {
      display: block;
      position: absolute;
      top: 5px;
      right: -8px;
      width: 19px;
      height: 19px;
      -webkit-border-radius: 9px;
      -moz-border-radius: 9px;
      border-radius: 9px;
      opacity: 0;
      -webkit-transition: opacity .2s linear, right .2s linear;
      -moz-transition: opacity .2s linear, right .2s linear;
      -o-transition: opacity .2s linear, right .2s linear;
      transition: opacity .2s linear, right .2s linear;
      text-align: center;
      color: white;
      text-shadow: 0px 1px 0px rgba(0, 0, 0, 0.4);
      font-size: 110%;
      font-weight: bold;
      padding-right: -1px;
      -webkit-box-shadow: inset 0 1px 0 rgba(0,0,0,.2), inset 0 -1px 0 rgba(255,255,255,.2);
      -moz-box-shadow: inset 0 1px 0 rgba(0,0,0,.2), inset 0 -1px 0 rgba(255,255,255,.2);
      box-shadow: inset 0 1px 0 rgba(0,0,0,.2), inset 0 -1px 0 rgba(255,255,255,.2); }
    #button-demo .button.arrow:hover {
      padding-right: 40px; }
      #button-demo .button.arrow:hover > div {
        opacity: 1;
        right: 10px; }

</style>
