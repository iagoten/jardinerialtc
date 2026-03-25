<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jardinería LTC | Profesionales del Jardín</title>
    <style>
        :root {
            --verde: #76b82a;
            --oscuro: #1a1a1a;
            --fondo-gris: #fcfcfc;
        }

        body { 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
            margin: 0; 
            background-color: #ffffff; /* Blanco puro para fundir el fondo de la foto */
            color: var(--oscuro);
        }

        /* Contenedor principal del logo para que parezca que flota */
        .header-logo { 
            padding: 60px 20px;
            text-align: center;
            background: white;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .tarjeta-flotante {
            max-width: 500px;
            width: 100%;
            border-radius: 12px;
            /* Esta sombra crea el efecto de que la tarjeta está levantada */
            box-shadow: 0 20px 40px rgba(0,0,0,0.12), 0 10px 15px rgba(0,0,0,0.08);
            transition: transform 0.3s ease;
            /* Recortamos ligeramente los bordes para limpiar la foto */
            clip-path: inset(2% 2% 2% 2% round 12px);
        }

        .tarjeta-flotante:hover {
            transform: translateY(-10px) scale(1.02);
        }

        .servicios-franja {
            background-color: var(--verde);
            color: white;
            padding: 15px;
            font-size: 1.2em;
            font-weight: bold;
            text-align: center;
            text-transform: uppercase;
            letter-spacing: 3px;
        }

        .contenedor-servicios { 
            display: flex; 
            justify-content: center; 
            gap: 25px; 
            flex-wrap: wrap; 
            padding: 60px 20px;
            background-color: var(--fondo-gris);
        }

        .tarjeta-servicio { 
            background: white; 
            padding: 30px; 
            border-radius: 20px; 
            width: 260px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.03);
            border-top: 6px solid var(--verde);
            text-align: center;
        }

        .tarjeta-servicio h3 { color: var(--verde); margin-top: 0; font-size: 1.6em; }

        .seccion-contacto { padding: 80px 20px; text-align: center; }

        .btn-whatsapp { 
            background: #25d366; 
            color: white; 
            padding: 22px 45px; 
            text-decoration: none; 
            border-radius: 60px; 
            font-weight: bold; 
            font-size: 1.4em;
            display: inline-block;
            box-shadow: 0 8px 20px rgba(37, 211, 102, 0.3);
            transition: all 0.3s ease;
        }

        .btn-whatsapp:hover { 
            background: #128c7e;
            box-shadow: 0 12px 25px rgba(37, 211, 102, 0.4);
            transform: translateY(-3px);
        }

        .num-telefono { 
            font-size: 2.5em; 
            display: block; 
            margin: 25px 0; 
            color: var(--oscuro); 
            font-weight: 800;
            font-family: 'Arial Black', sans-serif;
        }
    </style>
</head>
<body>

    <header class="header-logo">
        <img src="jardineria_ltc_logo.jpg" alt="Jardinería LTC" class="tarjeta-flotante">
    </header>

    <div class="servicios-franja">
        Mantenimiento • Podas • Desbroces
    </div>

    <section class="contenedor-servicios">
        <div class="tarjeta-servicio">
            <h3>🌿 Jardines</h3>
            <p>Mantenimiento profesional para comunidades y particulares.</p>
        </div>
        <div class="tarjeta-servicio">
            <h3>✂️ Podas</h3>
            <p>Especialistas en recorte de setos y poda de árboles.</p>
        </div>
        <div class="tarjeta-servicio">
            <h3>🚜 Fincas</h3>
            <p>Limpieza y desbroce de terrenos con maquinaria propia.</p>
        </div>
    </section>

    <section class="seccion-contacto">
        <h2>¿Necesitas un presupuesto sin compromiso?</h2>
        <p>Llámanos directamente o envía un WhatsApp:</p>
        <span class="num-telefono">629 44 20 13</span>
        <br>
        <a href="https://wa.me/34629442013" class="btn-whatsapp">PEDIR PRESUPUESTO POR WHATSAPP</a>
    </section>

    <footer style="padding: 40px; text-align: center; color: #bbb; font-size: 0.9em; border-top: 1px solid #eee;">
        &copy; 2024 Jardinería LTC | Servicios Profesionales de Jardinería
    </footer>

</body>
</html>
