# Veterinaria-kiin-pets
Clínica Veterinaria Kiin pets 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Veterinaria k'iin Pets DraZaira | Clínica y Pensión 24h</title>
    <style>
        :root {
            --naranja: #f39200; 
            --azul-claro: #a8e3e5; 
            --purpura: #b19cd9;
            --oscuro: #2c3e50;
            --fondo: #fdfdfd;
        }

        body { 
            font-family: 'Segoe UI', Tahoma, sans-serif; 
            margin: 0; 
            color: #333; 
            line-height: 1.6; 
            background-color: var(--fondo); 
            scroll-behavior: smooth; 
        }
        
        header { 
            background: white; 
            padding: 25px 20px; 
            text-align: center; 
            border-bottom: 6px solid var(--azul-claro);
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }
        .logo-main { font-size: 2.2rem; font-weight: 800; color: var(--oscuro); margin: 0; text-transform: uppercase; }
        .logo-sub { color: var(--naranja); font-size: 1.4rem; font-weight: bold; margin-top: -5px; }

        .hero { 
            background: linear-gradient(135deg, var(--azul-claro) 0%, #ffffff 100%);
            padding: 60px 20px; 
            text-align: center;
        }

        .container { max-width: 1100px; margin: auto; padding: 30px 20px; }

        h2 { text-align: center; color: var(--oscuro); font-size: 2rem; margin-bottom: 30px; }

        .grid-servicios { 
            display: grid; 
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); 
            gap: 20px; 
            margin-bottom: 40px;
        }
        .card { 
            background: white; 
            padding: 25px; 
            border-radius: 20px; 
            text-align: center; 
            box-shadow: 0 8px 20px rgba(0,0,0,0.06);
            border-bottom: 5px solid var(--naranja);
            transition: 0.3s;
        }
        .card:hover { transform: translateY(-5px); }

        .pension-24h {
            background: #fff8f0; 
            border: 2px solid var(--naranja);
            padding: 40px; 
            border-radius: 25px; 
            text-align: center; 
            margin: 40px 0;
        }

        .requisitos-lista {
            display: inline-block;
            text-align: left;
            margin: 20px auto;
        }
        .requisitos-lista li { list-style: none; margin-bottom: 10px; font-weight: bold; color: var(--oscuro); }

        .opiniones-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin-top: 20px;
        }
        .review-card {
            background: white;
            padding: 25px;
            border-radius: 20px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.05);
            border: 1px solid #eee;
        }
        .stars { color: #f1c40f; font-size: 1.2rem; margin-bottom: 10px; }
        .review-text { font-style: italic; color: #555; }
        .review-author { display: block; margin-top: 15px; font-weight: bold; color: var(--naranja); text-align: right; }

        .contacto-seccion { 
            background: var(--purpura); 
            color: white; 
            padding: 40px 20px; 
            border-radius: 25px; 
            text-align: center;
            margin-top: 60px;
        }
        
        .btn {
            display: inline-block; 
            padding: 15px 35px; 
            border-radius: 50px;
            text-decoration: none; 
            font-weight: bold; 
            margin: 10px; 
            transition: 0.3s;
            border: none;
        }
        .btn-maps { background: white; color: var(--oscuro); }
        .btn-ws { background: #25d366; color: white; }
        .btn-review { background: var(--naranja); color: white; margin-top: 20px; }
        .btn:hover { transform: scale(1.05); box-shadow: 0 5px 15px rgba(0,0,0,0.2); }

        footer { text-align: center; padding: 40px; color: #888; background: #f4f4f4; margin-top: 50px; }
    </style>
</head>
<body>

    <header>
        <div class="logo-main">Veterinaria k'iin Pets</div>
        <div class="logo-sub">DraZaira</div>
    </header>

    <section class="hero">
        <h1>Cuidado de confianza para tu familia</h1>
        <p><strong>📍 Av. México 544, San Jerónimo Aculco, CDMX</strong></p>
        <a href="https://maps.app.goo.gl/ChIJwR-9nt3_zYUR-ic0mbp8DUU" target="_blank" class="btn btn-maps">📍 Cómo llegar (Google Maps)</a>
    </section>

    <div class="container">
        <div class="grid-servicios">
            <div class="card"><h3>🩺 Consultas</h3><p>Perros y Gatos</p></div>
            <div class="card"><h3>💉 Vacunas</h3><p>Protección Total</p></div>
            <div class="card"><h3>✂️ Estética</h3><p>Baños y Cortes</p></div>
            <div class="card"><h3>🏥 Cirugías</h3><p>Atención Quirúrgica</p></div>
        </div>

        <div class="pension-24h">
            <h2>🏨 Pensión Canina 24 Horas</h2>
            <p>Tu mascota nunca estará sola. Vigilancia y cuidados día y noche para su total seguridad.</p>
            <div class="requisitos-lista">
                <li>✅ Vacunación al corriente</li>
                <li>✅ Desparasitación Interna</li>
                <li>✅ Desparasitación Externa (Pulgas y Garrapatas)</li>
            </div>
        </div>

        <section id="testimonios">
            <h2>Lo que dicen nuestros clientes</h2>
            <div class="opiniones-container">
                <div class="review-card">
                    <div class="stars">★★★★★</div>
                    <p class="review-text">"Excelente atención de la Dra. Zaira. Dejé a mi perrito en la pensión y me mantuvieron informado todo el tiempo. ¡Súper recomendados!"</p>
                    <span class="review-author">- Mariana R.</span>
                </div>
                <div class="review-card">
                    <div class="stars">★★★★★</div>
                    <p class="review-text">"El servicio de estética es impecable, mi gato quedó precioso y lo trataron con mucho cariño. Muy profesionales."</p>
                    <span class="review-author">- Jorge L.</span>
                </div>
            </div>
            <div style="text-align: center;">
                <a href="https://search.google.com/local/writereview?placeid=ChIJwR-9nt3_zYUR-ic0mbp8DUU" target="_blank" class="btn btn-review">✍️ Déjanos tu opinión en Google Maps</a>
            </div>
        </section>

        <div class="contacto-seccion">
            <h2>Horarios de Atención</h2>
            <p>🕒 Lunes a Sábado: <strong>9:00 AM - 8:00 PM</strong></p>
            <p>📞 Teléfono: <strong>55 6158 3958</strong></p>
            <a href="https://wa.me/525561583958" class="btn btn-ws">Enviar mensaje por WhatsApp</a>
        </div>
    </div>

    <footer>
        <p><strong>Veterinaria k'iin Pets DraZaira</strong><br>Av. México 544, San Jerónimo Aculco, CDMX</p>
        <p>© 2026 Todos los derechos reservados.</p>
    </footer>

</body>
</html>
