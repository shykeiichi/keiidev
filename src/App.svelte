<div class="wrapper" style="height: 98vh">
	<div class="wrapper" style="height: 30vh">
		<div class="typing">
		keii.dev
		</div>

		<a class="button" href="https://shykeiichi.com">Return to my Homepage</a>
	</div>
</div>
  
<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');


:root {
background-color: #131516;
color: white;
}

.wrapper {
/* height: 50vh; */
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

.button {
	margin: 10px;
	color: white;
	text-align: center;
	width: 250px;
	padding-top: 15px;
	padding-bottom: 15px;
	padding-left: 32px;
	padding-right: 32px;
	border-radius: 15px;
	font-family: monospace;
	font-size: 18px;
	font-weight: bold;
	align-content: center;
	align-items: center;
	background-color: #F8EDE3;
	box-shadow: 0 5px 0 #DFD3C3;
	color: #131516;
}

a {
	text-decoration: none;
}

.button:hover {
	background-color: #f9f1e9;
	box-shadow: 0 5px 0 #e1d9d0;
}

.button:active {
	transform: translateY(5px);
	box-shadow: 0 0 0 #e98686;
}


  </style>