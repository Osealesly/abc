<!IDOCTYPE HTML>
<HTML lang="es">
<HEAD>
	<meta charset="UTF-8">	
	<Title> servicios contables</title>
	<style>
		body {
			font-family: 'segoe UI', sans-serif;
			background-color: #f0f0f0;
			margin: 0;
		}
		header {
			background-image: url('C:\Users\USUARIO\Downloads\WhatsApp Image 2025-07-17 at 18.15.32.jpeg'); 
			background-size: cpver;
			background-position: center;
			color: white;
			padding: 60px 20px;
			text-align: center;
		 }
        header h1 {
            background-color: rgba(0, 0, 0, 0.5);
            display: inline-block;
            padding: 10px 20px;
            border-radius: 10px;
        }
        .contenedor {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 20px;
        }
        .producto {
            background-color: white;
            width: 300px;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            transition: transform 0.3s ease;
        }
        .producto:hover {
            transform: scale(1.03);
        }
        img {
            width: 100%;
            border-radius: 10px;
        }
        h2 {
            font-size: 20px;
            color: #333;
        }
        p {
            font-size: 14px;
            color: #555;
        }
        .boton-solicitar {
            background-color: #27ae60;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            width: 100%;
            cursor: pointer;
            font-size: 16px;
            transition: background-color 0.3s ease;
        }
        .boton-socilitar {
            background-color: #27ae60;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            width: 100%;
            cursor: pointer;
            font-size: 16px;
            transition: background-color 0.3s ease;
        }
        .boton-socilitar:hover {
            background-color: #219150;
        }
        .contacto {
            text-align: center;
            padding: 20px;
            background-color: #ecf0f1;
        }
        .contacto a {
            text-decoration: none;
            margin: 0 15px;
            color: #2c3e50;
            font-weight: bold;
            font-size: 18px;
            transition: color 0.3s ease;
        }
        .contacto a:hover {
            color: #2980b9;
        }

        /* Estilos para ventana emergente */
        .popup {
            display: none;
            position: fixed;
            top: 0; left: 0;
            width: 100%; height: 100%;
            background-color: rgba(0,0,0,0.6);
            justify-content: center;
            align-items: center;
            z-index: 999;
        }
        .popup-contenido {
            background: white;
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            max-width: 400px;
            box-shadow: 0 0 15px rgba(0,0,0,0.5);
            animation: entrada 0.5s ease;
        }
        .popup-contenido img {
            width: 80px;
            margin-bottom: 15px;
        }
        .popup-contenido h2 {
            margin: 0 0 10px 0;
        }
        .cerrar {
            margin-top: 15px;
            padding: 8px 20px;
            background-color: #27ae60;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        @keyframes entrada {
            from { transform: scale(0.7); opacity: 0; }
            to { transform: scale(1); opacity: 1; }
        }
	</style>
</head>
<body>

<header>
	<h1>servicios contables, NEBAJ</H1>
</header>

<section class="contenedor">
	
	<div class="producto">
		<img src=t="https://www.pngwing.com/es/free-png-vsbxz>
		<h2>servicios contables</h2>
		 <p><strong>servicios contables</strong></p>
		<p>SEGURO, CONFIABLE Y RAPIDO</p>
		 <button class="boton-socilitar" onclick="mostrarPopup(servicios)">solicitar</button>
    </div>
	
</section>
<div class="contacto">
<h3>Contáctanos</h3>
<a href="https://wa.me/50255226501" target="_blank">📱 WhatsApp</a>
<a href="diegoraymundo551@gmail.com">📧 Correo</a>
<a href="tel:+50255226501">📞 Llamada</a>
</div>
<div class="popup" id="popup">
<div class="popup-contenido">
<h2>¡solicitud realizada!</h2>
<p id="mensajeProducto"></p>
<button class="cerrar" onclick="cerrarPopup()">Aceptar</button>
</div>
</div>

</div>
</div>

<script>
function mostrarPopup(producto) {
    document.getElementById("mensajeProducto").innerText = "Has solicitado: " + producto + ". Te contactaremos pronto.";
    document.getElementById("popup").style.display = "flex";
}

function cerrarPopup() {
    document.getElementById("popup").style.display = "none";
}
</script>

</body>
</html>
