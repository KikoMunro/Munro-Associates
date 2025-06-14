# Munro-Associates
Law Firm Site
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Munro & Associates Legal Services</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Trebuchet+MS&display=swap');
        body {
            font-family: 'Trebuchet MS', sans-serif;
            color: #000000;
        }
        .bg-light {
            background-color: #f8f9fa;
        }
        .text-dark {
            color: #000000;
        }
        .en, .es {
            display: none;
        }
        body.lang-en .en {
            display: block;
        }
        body.lang-es .es {
            display: block;
        }
        body.lang-en a .en {
            display: inline;
        }
        body.lang-es a .es {
            display: inline;
        }
    </style>
</head>
<body class="bg-light">
    <!-- Encabezado -->
    <header class="bg-white shadow">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <h1 class="text-3xl font-bold text-dark">Munro & Associates Legal Services</h1>
            <nav>
                <ul class="flex space-x-4">
                    <li><a href="#inicio"><span class="en">Home</span><span class="es">Inicio</span></a></li>
                    <li><a href="#acerca"><span class="en">About</span><span class="es">Acerca</span></a></li>
                    <li><a href="#servicios"><span class="en">Services</span><span class="es">Servicios</span></a></li>
                    <li><a href="#alianzas"><span class="en">Alliances</span><span class="es">Alianzas</span></a></li>
                    <li><a href="#proceso"><span class="en">Buying Process</span><span class="es">Proceso de Compra</span></a></li>
                    <li><a href="#mitos"><span class="en">Myths vs Facts</span><span class="es">Mitos vs Hechos</span></a></li>
                    <li><a href="#testimonios"><span class="en">Testimonials</span><span class="es">Testimonios</span></a></li>
                    <li><a href="#oficina"><span class="en">Our Office</span><span class="es">Nuestra Oficina</span></a></li>
                    <li><a href="#clientes"><span class="en">Clients</span><span class="es">Clientes</span></a></li>
                    <li><a href="#contacto"><span class="en">Contact</span><span class="es">Contacto</span></a></li>
                    <li><a href="javascript:void(0)" onclick="setLanguage('lang-en')">English</a></li>
                    <li><a href="javascript:void(0)" onclick="setLanguage('lang-es')">Español</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Sección Inicio -->
    <section id="inicio" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-4xl font-bold mb-4 en">Relax, we're here to guide you</h2>
            <h2 class="text-4xl font-bold mb-4 es">Relájate, estamos aquí para guiarte</h2>
            <p class="text-lg mb-8 en">Specialized in legal and real estate services for foreign clients buying properties in Mexico.</p>
            <p class="text-lg mb-8 es">Especializados en servicios legales y de bienes raíces para clientes extranjeros que compran propiedades en México.</p>
            <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e" alt="Puerto Peñasco Beach" class="mx-auto rounded-lg shadow-lg">
        </div>
    </section>

    <!-- Sección Acerca -->
    <section id="acerca" class="py-20 bg-light">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold mb-4 en">About Us</h2>
            <h2 class="text-3xl font-bold mb-4 es">Acerca de Nosotros</h2>
            <p class="text-lg mb-4 en">Munro & Associates is a leading firm in legal and real estate services, dedicated to assisting foreign clients in purchasing properties in Mexico. With over 100 years of combined experience, we guarantee a smooth, secure, and efficient process.</p>
            <p class="text-lg mb-4 es">Munro & Associates es una firma líder en servicios legales y de bienes raíces, dedicada a asistir a clientes extranjeros en la compra de propiedades en México. Con más de 100 años de experiencia combinada, garantizamos un proceso fluido, seguro y eficiente.</p>
            <p class="text-lg mb-4 en">Our strategic alliances with notaries, banks, and international law firms allow us to offer comprehensive support, from title searches to closing services.</p>
            <p class="text-lg mb-4 es">Nuestras alianzas estratégicas con notarios, bancos y firmas legales internacionales nos permiten ofrecer un soporte integral, desde búsquedas de títulos hasta servicios de cierre.</p>
            <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c" alt="Office Interior" class="mt-4 rounded-lg shadow-lg">
        </div>
    </section>

    <!-- Sección Servicios -->
    <section id="servicios" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold mb-4 en">Our Services</h2>
            <h2 class="text-3xl font-bold mb-4 es">Nuestros Servicios</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-light p-6 rounded-lg shadow">
                    <i class="fas fa-search text-3xl mb-2"></i>
                    <h3 class="text-xl font-semibold mb-2 en">Title Search</h3>
                    <h3 class="text-xl font-semibold mb-2 es">Búsqueda de Títulos</h3>
                    <p class="en">We verify ownership, liens, and legal issues to ensure a clear title.</p>
                    <p class="es">Verificamos la propiedad, gravámenes y problemas legales para garantizar un título claro.</p>
                </div>
                <div class="bg-light p-6 rounded-lg shadow">
                    <i class="fas fa-handshake text-3xl mb-2"></i>
                    <h3 class="text-xl font-semibold mb-2 en">Trust Management</h3>
                    <h3 class="text-xl font-semibold mb-2 es">Gestión de Fideicomisos</h3>
                    <p class="en">We assist in the creation and management of trusts for foreign buyers.</p>
                    <p class="es">Asistimos en la creación y gestión de fideicomisos para compradores extranjeros.</p>
                </div>
                <div class="bg-light p-6 rounded-lg shadow">
                    <i class="fas fa-file-contract text-3xl mb-2"></i>
                    <h3 class="text-xl font-semibold mb-2 en">Contract Review</h3>
                    <h3 class="text-xl font-semibold mb-2 es">Revisión de Contratos</h3>
                    <p class="en">We ensure all contracts are legal and protect your interests.</p>
                    <p class="es">Aseguramos que todos los contratos sean legales y protejan tus intereses.</p>
                </div>
                <div class="bg-light p-6 rounded-lg shadow">
                    <i class="fas fa-check-circle text-3xl mb-2"></i>
                    <h3 class="text-xl font-semibold mb-2 en">Due Diligence</h3>
                    <h3 class="text-xl font-semibold mb-2 es">Debida Diligencia</h3>
                    <p class="en">We conduct thorough investigations to identify potential risks.</p>
                    <p class="es">Realizamos investigaciones exhaustivas para identificar riesgos potenciales.</p>
                </div>
                <div class="bg-light p-6 rounded-lg shadow">
                    <i class="fas fa-key text-3xl mb-2"></i>
                    <h3 class="text-xl font-semibold mb-2 en">Closing Services</h3>
                    <h3 class="text-xl font-semibold mb-2 es">Servicios de Cierre</h3>
                    <p class="en">We coordinate with all parties for a smooth closing process.</p>
                    <p class="es">Coordinamos con todas las partes para un proceso de cierre fluido.</p>
                </div>
                <div class="bg-light p-6 rounded-lg shadow">
                    <i class="fas fa-calculator text-3xl mb-2"></i>
                    <h3 class="text-xl font-semibold mb-2 en">Tax Advisory</h3>
                    <h3 class="text-xl font-semibold mb-2 es">Asesoría Fiscal</h3>
                    <p class="en">We calculate and manage taxes related to property transactions.</p>
                    <p class="es">Calculamos y gestionamos impuestos relacionados con transacciones de propiedades.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Sección Alianzas -->
    <section id="alianzas" class="py-20 bg-light">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold mb-4 en">Our Strategic Alliances</h2>
            <h2 class="text-3xl font-bold mb-4 es">Nuestras Alianzas Estratégicas</h2>
            <p class="text-lg mb-4 en">Munro & Associates is proud to have an exclusive commercial alliance with <a href="https://www.coldwellbanker.com/company/coldwell-banker-seaside-realty/cid-P00500000FDdqTMzEDeGzpzDiHxls9py32ozw7bg" class="text-blue-600 hover:underline">Coldwell Banker Seaside Realty</a> and <a href="https://www.armoursecure.com/" class="text-blue-600 hover:underline">ArmSec Title Insurance & Escrow Services</a>. This partnership allows us to offer comprehensive, one-stop shop real estate services, ensuring that our clients receive seamless support throughout their property transactions. From expert legal advice and title searches to secure escrow services and real estate brokerage, our alliance provides all the necessary resources under one roof, making the process of buying or selling property in Mexico straightforward and stress-free.</p>
            <p class="text-lg mb-4 es">Munro & Associates se enorgullece de tener una alianza comercial exclusiva con <a href="https://www.coldwellbanker.com/company/coldwell-banker-seaside-realty/cid-P00500000FDdqTMzEDeGzpzDiHxls9py32ozw7bg" class="text-blue-600 hover:underline">Coldwell Banker Seaside Realty</a> y <a href="https://www.armoursecure.com/" class="text-blue-600 hover:underline">ArmSec Title Insurance & Escrow Services</a>. Esta asociación nos permite ofrecer servicios inmobiliarios integrales de ventanilla única, asegurando que nuestros clientes reciban un apoyo sin fisuras durante todo el proceso de transacción de propiedades. Desde asesoramiento legal experto y búsquedas de títulos hasta servicios de escrow seguros y corretaje inmobiliario, nuestra alianza proporciona todos los recursos necesarios bajo un mismo techo, haciendo que el proceso de compra o venta de propiedades en México sea sencillo y sin estrés.</p>
        </div>
    </section>

    <!-- Sección Proceso de Compra -->
    <section id="proceso" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold mb-4 en">Buying Process</h2>
            <h2 class="text-3xl font-bold mb-4 es">Proceso de Compra</h2>
            <ol class="list-decimal list-inside space-y-4 en">
                <li><strong>Initial Consultation:</strong> We assess your case and explain the entire process.</li>
                <li><strong>Property Analysis:</strong> We investigate the property to ensure a safe investment.</li>
                <li><strong>Comprehensive Legal Management:</strong> We draft contracts and handle permits or trusts if necessary.</li>
                <li><strong>Notarial Coordination:</strong> We work with notaries to comply with the law.</li>
                <li><strong>Secure Delivery:</strong> We finalize the purchase with all documents in order for your peace of mind.</li>
                <li><strong>Ongoing Support:</strong> We are here to assist you at all times.</li>
            </ol>
            <ol class="list-decimal list-inside space-y-4 es">
                <li><strong>Consulta Inicial:</strong> Evaluamos tu caso y explicamos el proceso completo.</li>
                <li><strong>Análisis de Propiedad:</strong> Investigamos la propiedad para asegurar una inversión segura.</li>
                <li><strong>Gestión Legal Completa:</strong> Redactamos contratos y manejamos permisos o fideicomisos si es necesario.</li>
                <li><strong>Coordinación Notarial:</strong> Trabajamos con notarios para cumplir con la ley.</li>
                <li><strong>Entrega Segura:</strong> Finalizamos la compra con todos los documentos en orden para tu tranquilidad.</li>
                <li><strong>Soporte Continuo:</strong> Estamos aquí para ayudarte en todo momento.</li>
            </ol>
        </div>
    </section>

    <!-- Sección Mitos vs Hechos -->
    <section id="mitos" class="py-20 bg-light">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold mb-4 en">Myths vs Facts</h2>
            <h2 class="text-3xl font-bold mb-4 es">Mitos vs Hechos</h2>
            <div class="space-y-4">
                <div>
                    <p class="en"><strong>Myth:</strong> Buying property in Mexico is complicated and risky.</p>
                    <p class="es"><strong>Mito:</strong> Comprar una propiedad en México es complicado y riesgoso.</p>
                    <p class="en"><strong>Fact:</strong> With the right legal guidance, the process is safe and structured.</p>
                    <p class="es"><strong>Hecho:</strong> Con la guía legal adecuada, el proceso es seguro y estructurado.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Sección Testimonios -->
    <section id="testimonios" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold mb-4 en">Testimonials</h2>
            <h2 class="text-3xl font-bold mb-4 es">Testimonios</h2>
            <div class="space-y-4">
                <blockquote class="italic en">"I just called them and they took care of everything. Seven years later, my property doubled in value." - Satisfied Client</blockquote>
                <blockquote class="italic es">"Solo los llamé y se encargaron de todo. Siete años después, mi propiedad duplicó su valor." - Cliente Satisfecho</blockquote>
            </div>
        </div>
    </section>

    <!-- Sección Nuestra Oficina -->
    <section id="oficina" class="py-20 bg-light">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold mb-4 en">Our Office</h2>
            <h2 class="text-3xl font-bold mb-4 es">Nuestra Oficina</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                <img src="https://via.placeholder.com/600x300?text=Office+Image+1" alt="Office Image 1" class="rounded-lg shadow-lg">
                <img src="https://via.placeholder.com/600x300?text=Office+Image+2" alt="Office Image 2" class="rounded-lg shadow-lg">
                <img src="https://via.placeholder.com/600x300?text=Office+Image+3" alt="Office Image 3" class="rounded-lg shadow-lg">
                <img src="https://via.placeholder.com/600x300?text=Office+Image+4" alt="Office Image 4" class="rounded-lg shadow-lg">
                <img src="https://via.placeholder.com/600x300?text=Office+Image+5" alt="Office Image 5" class="rounded-lg shadow-lg">
                <img src="https://via.placeholder.com/600x300?text=Office+Image+6" alt="Office Image 6" class="rounded-lg shadow-lg">
                <img src="https://via.placeholder.com/600x300?text=Office+Image+7" alt="Office Image 7" class="rounded-lg shadow-lg">
            </div>
            <p class="text-sm mt-4 en">Note: Replace these placeholder images with the actual office photos provided in attachments (ids 6-12).</p>
            <p class="text-sm mt-4 es">Nota: Reemplace estas imágenes de marcador con las fotos reales de la oficina proporcionadas en los adjuntos (ids 6-12).</p>
        </div>
    </section>

    <!-- Sección Clientes -->
    <section id="clientes" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold mb-4 en">Notable Clients</h2>
            <h2 class="text-3xl font-bold mb-4 es">Clientes Destacados</h2>
            <p class="text-lg mb-4 en">We are honored to have worked with distinguished clients such as <a href="https://www.penascodelsolhotel.com/es" class="text-blue-600 hover:underline">Hotel Peñasco del Sol</a>, providing expert legal and real estate services to support their operations and growth in Puerto Peñasco.</p>
            <p class="text-lg mb-4 es">Nos sentimos honrados de haber trabajado con clientes distinguidos como el <a href="https://www.penascodelsolhotel.com/es" class="text-blue-600 hover:underline">Hotel Peñasco del Sol</a>, proporcionando servicios legales y inmobiliarios expertos para apoyar sus operaciones y crecimiento en Puerto Peñasco.</p>
        </div>
    </section>

    <!-- Sección Contacto -->
    <section id="contacto" class="py-20 bg-light">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-3xl font-bold mb-4 en">Contact Us</h2>
            <h2 class="text-3xl font-bold mb-4 es">Contáctanos</h2>
            <p class="text-lg mb-4 en">Blvd. Fremont 101, Col. Benito Juárez, 83554 Puerto Peñasco, Son., Mexico</p>
            <p class="text-lg mb-4 es">Blvd. Fremont 101, Col. Benito Juárez, 83554 Puerto Peñasco, Son., México</p>
            <p class="text-lg mb-4 en">Phone: 623 404 0650</p>
            <p class="text-lg mb-4 es">Teléfono: 623 404 0650</p>
            <p class="text-lg mb-4 en">Email: kikomunro@m&a.com</p>
            <p class="text-lg mb-4 es">Correo: kikomunro@m&a.com</p>
            <a href="https://maps.app.goo.gl/6z1z1z1z1z1z1z1z1" target="_blank" class="text-blue-600 hover:underline en">View on Google Maps</a>
            <a href="https://maps.app.goo.gl/6z1z1z1z1z1z1z1z1" target="_blank" class="text-blue-600 hover:underline es">Ver en Google Maps</a>
            <br>
            <a href="mailto:kikomunro@m&a.com" class="bg-black text-white px-6 py-2 rounded hover:bg-gray-800 mt-4 inline-block en">Schedule a Free Consultation</a>
            <a href="mailto:kikomunro@m&a.com" class="bg-black text-white px-6 py-2 rounded hover:bg-gray-800 mt-4 inline-block es">Programa una Consulta Gratuita</a>
        </div>
    </section>

    <!-- Pie de página -->
    <footer class="bg-black text-white py-4">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <p class="en">© 2025 Munro & Associates Legal Services. All rights reserved.</p>
            <p class="es">© 2025 Munro & Associates Legal Services. Todos los derechos reservados.</p>
        </div>
    </footer>

    <script>
        function setLanguage(lang) {
            document.body.className = lang;
            localStorage.setItem('language', lang);
        }

        // On load, set to stored language or default to lang-es
        window.onload = function() {
            var lang = localStorage.getItem('language') || 'lang-es';
            setLanguage(lang);
        }
    </script>
</body>
</html>
