<!DOCTYPE html>

<html>

<head>

	<title>Miguel calculatrice web</title>

	<style type="text/css">

		button{

			width: 50px;

			height: 50px;

		}

		input{

			height: 50px;

			width: 260px;

		}

	</style>

	<script type="text/javascript">

		function act(val){

			var number = val;

			document.getElementById('out').value += number;

		}	



		function egal(){

			var reponse = eval(document.getElementById('out').value);

			document.getElementById('out').style= 'text-align:right;font-size:30px';

			document.getElementById('out').value = reponse;



		}



		

	</script>

</head>

<body>

	<Center>

	<h1> MiguelGarros caculator </h1>

	<table>

		<tr>

			<td colspan="5"><input type="text" name="" id="out" value=""></td>

		</tr>

		<tr>

			<td><button onclick="act(1)">1</button></td>

			<td><button onclick="act(2)">2</button></td>

			<td><button onclick="act(3)">3</button></td>

			<td><button onclick="act(4)">4</button></td>

			<td><button onclick="act(5)">5</button></td>

		</tr>

		<tr>

			<td><button onclick="act(6)">6</button></td>

			<td><button onclick="act(7)">7</button></td>

			<td><button onclick="act(8)">8</button></td>

			<td><button onclick="act(9)">9</button></td>

			<td><button onclick="act(0)">0</button></td>

		</tr>

		<tr>

			<td><button onclick="act('+')">+</button></td>

			<td><button onclick="act('-')">-</button></td>

			<td><button onclick="act('*')">*</button></td>

			<td><button onclick="act('/')">/</button></td>

			<td><button onclick="egal()">=</button></td>

		</tr>

		<tr>

			<td colspan="5"><a href="index.html"><button style="width: 100%;">Effacer</button></a></td>

		</tr>

	</table>

</Center>



</body>

</html>
