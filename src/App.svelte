<div class="wrapper">
	<div class="typing">
	  keii.dev
	</div>
  </div>
  
  <style>
  :root {
	background-color: #131516;
	color: white;
  }
  
  .wrapper {
	height: 98vh;
	/*This part is important for centering*/
	display: grid;
	place-items: center;
  }
  
  .typing {
	width: 8ch;
	animation: typing 2s steps(8), blink .5s step-end infinite alternate;
	white-space: nowrap;
	overflow: hidden;
	border-right: 3px solid;
	font-family: monospace;
	font-size: 2em;
  }
  
  @keyframes typing {
	from {
	  width: 0
	}
  }
	
  @keyframes blink {
	50% {
	  border-color: transparent
	}
  }
  </style>