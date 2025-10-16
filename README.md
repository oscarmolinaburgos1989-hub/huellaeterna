# huellaeterna
un santuario virtual de amor y respeto
[index.html](https://github.com/user-attachments/files/22938380/index.html)
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <meta name="description" content="Huella Eterna - Crea memoriales digitales personalizados para tus mascotas. Preserva su recuerdo con amor y homenaje."/>
    <title>Huella Eterna - Inmortalizamos a tu mascota</title>

    <!-- Tailwind CDN (kept for original styling) -->
    <script src="https://cdn.tailwindcss.com/3.4.16"></script>

    <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css" rel="stylesheet">

    <link rel="icon" type="image/svg+xml" href="img/logo.svg">

    <script>tailwind.config={theme:{extend:{colors:{primary:'#d97706',secondary:'#f59e0b'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>

    <link rel="stylesheet" href="css/style.css">
</head>
<body class="bg-white text-gray-900">

    <!-- Header -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <!-- Logo -->
                <div class="flex items-center space-x-3">
                    <div class="w-10 h-10 flex items-center justify-center bg-primary text-white rounded-full">
                        <img src="img/logo.svg" alt="Huella Eterna logo" class="w-6 h-6">
                    </div>
                    <span class="font-['Pacifico'] text-2xl text-primary">Huella Eterna</span>
                </div>

                <!-- Navigation -->
                <nav class="hidden md:flex items-center space-x-8">
                    <a href="#inicio" class="text-gray-700 hover:text-primary transition-colors duration-300">Inicio</a>
                    <a href="#como-funciona" class="text-gray-700 hover:text-primary transition-colors duration-300">Cómo funciona</a>
                    <a href="#galeria" class="text-gray-700 hover:text-primary transition-colors duration-300">Galería</a>
                    <a href="#testimonios" class="text-gray-700 hover:text-primary transition-colors duration-300">Testimonios</a>
                    <a href="#blog" class="text-gray-700 hover:text-primary transition-colors duration-300">Blog</a>
                    <a href="#contacto" class="text-gray-700 hover:text-primary transition-colors duration-300">Contacto</a>
                </nav>

                <!-- CTA Button -->
                <button class="bg-primary hover:bg-secondary text-white px-6 py-2 !rounded-button transition-all duration-300 glow-hover whitespace-nowrap">
                    Inmortaliza a tu peludo
                </button>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="inicio" class="hero-bg min-h-screen flex items-center relative">
        <div class="absolute inset-0 bg-black bg-opacity-40"></div>
        <div class="relative z-10 w-full max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center text-white fade-in">
                <h1 class="text-5xl md:text-6xl font-light mb-6 leading-tight">
                    Porque la memoria de<br>quienes amamos<br>nunca se apaga
                </h1>
                <p class="text-xl md:text-2xl mb-8 text-gray-200 max-w-3xl mx-auto">
                    Crea un homenaje eterno para tu mascota con nuestro memorial digital personalizado
                </p>
                <button class="bg-primary hover:bg-secondary text-white px-8 py-4 text-lg !rounded-button transition-all duration-300 pulse-gentle whitespace-nowrap">
                    Inmortaliza a tu peludo hoy
                </button>
            </div>
        </div>
    </section>

    <!-- Cómo Funciona Section -->
    <section id="como-funciona" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-light text-gray-900 mb-4">Cómo inmortalizar a tu mascota</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">
                    En tres simples pasos, crea un memorial único y personalizado
                </p>
            </div>

            <div class="grid md:grid-cols-3 gap-12">
                <!-- Step 1 -->
                <div class="text-center bounce-in">
                    <div class="w-20 h-20 flex items-center justify-center bg-primary text-white rounded-full mx-auto mb-6">
                        <i class="ri-image-line text-2xl"></i>
                    </div>
                    <h3 class="text-2xl font-medium text-gray-900 mb-4">Selecciona la foto</h3>
                    <p class="text-gray-600 leading-relaxed">
                        Elige la fotografía más especial de tu mascota. Nosotros nos encargamos del resto para crear algo único.
                    </p>
                </div>

                <!-- Step 2 -->
                <div class="text-center bounce-in" style="animation-delay: 0.2s;">
                    <div class="w-20 h-20 flex items-center justify-center bg-primary text-white rounded-full mx-auto mb-6">
                        <i class="ri-edit-line text-2xl"></i>
                    </div>
                    <h3 class="text-2xl font-medium text-gray-900 mb-4">Personaliza</h3>
                    <p class="text-gray-600 leading-relaxed">
                        Agrega el nombre, fechas importantes y un mensaje especial que capture la esencia de tu compañero.
                    </p>
                </div>

                <!-- Step 3 -->
                <div class="text-center bounce-in" style="animation-delay: 0.4s;">
                    <div class="w-20 h-20 flex items-center justify-center bg-primary text-white rounded-full mx-auto mb-6">
                        <i class="ri-share-line text-2xl"></i>
                    </div>
                    <h3 class="text-2xl font-medium text-gray-900 mb-4">Guarda y comparte</h3>
                    <p class="text-gray-600 leading-relaxed">
                        Descarga tu homenaje digital o compártelo con familia y amigos para mantener viva su memoria.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Galería Section -->
    <section id="galeria" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-light text-gray-900 mb-4">Recuerdos que viven para siempre</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">
                    Descubre algunos de los hermosos homenajes creados por nuestra comunidad
                </p>
            </div>

            <!-- Filter Buttons -->
            <div class="flex justify-center mb-12">
                <div class="flex space-x-4 bg-gray-100 p-1 rounded-full">
                    <button class="px-6 py-2 bg-primary text-white !rounded-button whitespace-nowrap">Todos</button>
                    <button class="px-6 py-2 text-gray-600 hover:text-primary transition-colors !rounded-button whitespace-nowrap">Perros</button>
                    <button class="px-6 py-2 text-gray-600 hover:text-primary transition-colors !rounded-button whitespace-nowrap">Gatos</button>
                    <button class="px-6 py-2 text-gray-600 hover:text-primary transition-colors !rounded-button whitespace-nowrap">Otros</button>
                </div>
            </div>

            <!-- Gallery Grid -->
            <div class="grid md:grid-cols-3 lg:grid-cols-4 gap-6 mb-12">
                <div class="group cursor-pointer" data-category="perros">
                    <div class="relative overflow-hidden rounded-lg">
                        <img src="img/dog1.svg" alt="Max" class="w-full h-64 object-cover object-top group-hover:scale-105 transition-transform duration-300" loading="lazy">
                        <div class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-20 transition-all duration-300"></div>
                    </div>
                    <div class="mt-3">
                        <h3 class="font-medium text-gray-900">Max</h3>
                        <p class="text-sm text-gray-600">Mi fiel compañero de aventuras</p>
                    </div>
                </div>

                <div class="group cursor-pointer" data-category="gatos">
                    <div class="relative overflow-hidden rounded-lg">
                        <img src="img/cat1.svg" alt="Luna" class="w-full h-64 object-cover object-top group-hover:scale-105 transition-transform duration-300" loading="lazy">
                        <div class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-20 transition-all duration-300"></div>
                    </div>
                    <div class="mt-3">
                        <h3 class="font-medium text-gray-900">Luna</h3>
                        <p class="text-sm text-gray-600">Siempre en nuestros corazones</p>
                    </div>
                </div>

                <div class="group cursor-pointer" data-category="perros">
                    <div class="relative overflow-hidden rounded-lg">
                        <img src="img/dog2.svg" alt="Rocky" class="w-full h-64 object-cover object-top group-hover:scale-105 transition-transform duration-300" loading="lazy">
                        <div class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-20 transition-all duration-300"></div>
                    </div>
                    <div class="mt-3">
                        <h3 class="font-medium text-gray-900">Rocky</h3>
                        <p class="text-sm text-gray-600">Alegría pura en cuatro patas</p>
                    </div>
                </div>

                <div class="group cursor-pointer" data-category="perros">
                    <div class="relative overflow-hidden rounded-lg">
                        <img src="img/dog3.svg" alt="Bella" class="w-full h-64 object-cover object-top group-hover:scale-105 transition-transform duration-300" loading="lazy">
                        <div class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-20 transition-all duration-300"></div>
                    </div>
                    <div class="mt-3">
                        <h3 class="font-medium text-gray-900">Bella</h3>
                        <p class="text-sm text-gray-600">Un ángel de cuatro patas</p>
                    </div>
                </div>

                <div class="group cursor-pointer" data-category="perros">
                    <div class="relative overflow-hidden rounded-lg">
                        <img src="img/dog4.svg" alt="Thor" class="w-full h-64 object-cover object-top group-hover:scale-105 transition-transform duration-300" loading="lazy">
                        <div class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-20 transition-all duration-300"></div>
                    </div>
                    <div class="mt-3">
                        <h3 class="font-medium text-gray-900">Thor</h3>
                        <p class="text-sm text-gray-600">Nuestro guardián eterno</p>
                    </div>
                </div>

                <div class="group cursor-pointer" data-category="gatos">
                    <div class="relative overflow-hidden rounded-lg">
                        <img src="img/cat2.svg" alt="Mimi" class="w-full h-64 object-cover object-top group-hover:scale-105 transition-transform duration-300" loading="lazy">
                        <div class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-20 transition-all duration-300"></div>
                    </div>
                    <div class="mt-3">
                        <h3 class="font-medium text-gray-900">Mimi</h3>
                        <p class="text-sm text-gray-600">Ronroneos que perduran</p>
                    </div>
                </div>

                <div class="group cursor-pointer" data-category="otros">
                    <div class="relative overflow-hidden rounded-lg">
                        <img src="img/other1.svg" alt="Coco" class="w-full h-64 object-cover object-top group-hover:scale-105 transition-transform duration-300" loading="lazy">
                        <div class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-20 transition-all duration-300"></div>
                    </div>
                    <div class="mt-3">
                        <h3 class="font-medium text-gray-900">Coco</h3>
                        <p class="text-sm text-gray-600">Pequeño en tamaño, grande en amor</p>
                    </div>
                </div>

                <div class="group cursor-pointer" data-category="perros">
                    <div class="relative overflow-hidden rounded-lg">
                        <img src="img/dog5.svg" alt="Simba" class="w-full h-64 object-cover object-top group-hover:scale-105 transition-transform duration-300" loading="lazy">
                        <div class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-20 transition-all duration-300"></div>
                    </div>
                    <div class="mt-3">
                        <h3 class="font-medium text-gray-900">Simba</h3>
                        <p class="text-sm text-gray-600">Inteligencia y lealtad infinita</p>
                    </div>
                </div>
            </div>

            <div class="text-center">
                <button class="bg-primary hover:bg-secondary text-white px-8 py-3 !rounded-button transition-all duration-300 whitespace-nowrap">
                    Crea tu homenaje ahora
                </button>
            </div>
        </div>
    </section>

    <!-- Testimonios Section -->
    <section id="testimonios" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-light text-gray-900 mb-4">Lo que dicen nuestras familias</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">
                    Testimonios reales de personas que han encontrado consuelo en nuestros memoriales
                </p>
            </div>

            <div class="max-w-4xl mx-auto">
                <div class="testimonial-container">
                    <div class="testimonial-slide bg-white rounded-xl p-8 shadow-lg">
                        <div class="flex items-center mb-6">
                            <img src="img/dog1.svg" alt="Max" class="w-16 h-16 rounded-full object-cover object-top mr-4">
                            <div>
                                <h3 class="font-medium text-gray-900">María González</h3>
                                <p class="text-gray-600">Con Max, su Golden Retriever</p>
                            </div>
                        </div>
                        <blockquote class="text-lg text-gray-700 italic leading-relaxed">
                            "Gracias a Huella Eterna, siento que Max sigue conmigo cada día. El memorial digital que crearon capturó perfectamente su esencia alegre y juguetona. Cada vez que lo veo, sonrío recordando todos los momentos hermosos que compartimos juntos."
                        </blockquote>
                    </div>
                </div>

                <div class="flex justify-center mt-8 space-x-2">
                    <button class="w-3 h-3 bg-primary rounded-full"></button>
                    <button class="w-3 h-3 bg-gray-300 rounded-full"></button>
                    <button class="w-3 h-3 bg-gray-300 rounded-full"></button>
                </div>

                <div class="text-center mt-8">
                    <button class="text-primary hover:text-secondary transition-colors duration-300 whitespace-nowrap">
                        Leer más testimonios
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Blog Section -->
    <section id="blog" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-light text-gray-900 mb-4">Consejos y artículos para el recuerdo</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">
                    Recursos útiles para honrar la memoria de tu mascota y procesar el duelo
                </p>
            </div>

            <div class="grid md:grid-cols-3 gap-8 mb-12">
                <article class="group cursor-pointer">
                    <div class="relative overflow-hidden rounded-lg mb-4">
                        <img src="img/blog1.svg" alt="Artículo 1" class="w-full h-48 object-cover object-top group-hover:scale-105 transition-transform duration-300" loading="lazy">
                    </div>
                    <div class="space-y-2">
                        <p class="text-sm text-gray-500">15 de Octubre, 2024</p>
                        <h3 class="text-xl font-medium text-gray-900 group-hover:text-primary transition-colors">
                            Cómo crear un memorial en casa para tu mascota
                        </h3>
                        <p class="text-gray-600 leading-relaxed">
                            Ideas creativas y emotivas para honrar la memoria de tu compañero en tu hogar, creando un espacio especial de recuerdo.
                        </p>
                    </div>
                </article>

                <article class="group cursor-pointer">
                    <div class="relative overflow-hidden rounded-lg mb-4">
                        <img src="img/blog2.svg" alt="Artículo 2" class="w-full h-48 object-cover object-top group-hover:scale-105 transition-transform duration-300" loading="lazy">
                    </div>
                    <div class="space-y-2">
                        <p class="text-sm text-gray-500">12 de Octubre, 2024</p>
                        <h3 class="text-xl font-medium text-gray-900 group-hover:text-primary transition-colors">
                            Procesando el duelo por la pérdida de una mascota
                        </h3>
                        <p class="text-gray-600 leading-relaxed">
                            Consejos profesionales para atravesar el proceso de duelo y encontrar formas saludables de recordar a tu mascota.
                        </p>
                    </div>
                </article>

                <article class="group cursor-pointer">
                    <div class="relative overflow-hidden rounded-lg mb-4">
                        <img src="img/blog3.svg" alt="Artículo 3" class="w-full h-48 object-cover object-top group-hover:scale-105 transition-transform duration-300" loading="lazy">
                    </div>
                    <div class="space-y-2">
                        <p class="text-sm text-gray-500">8 de Octubre, 2024</p>
                        <h3 class="text-xl font-medium text-gray-900 group-hover:text-primary transition-colors">
                            Preservando recuerdos: consejos de fotografía
                        </h3>
                        <p class="text-gray-600 leading-relaxed">
                            Técnicas y consejos para capturar los mejores momentos con tu mascota y crear recuerdos que perduren para siempre.
                        </p>
                    </div>
                </article>
            </div>

            <div class="text-center">
                <button class="bg-gray-100 hover:bg-gray-200 text-gray-800 px-8 py-3 !rounded-button transition-all duration-300 whitespace-nowrap">
                    Ver más artículos
                </button>
            </div>
        </div>
    </section>

    <!-- Contacto Section -->
    <section id="contacto" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-light text-gray-900 mb-4">Contáctanos</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">
                    Estamos aquí para ayudarte a crear el memorial perfecto para tu mascota
                </p>
            </div>

            <div class="grid lg:grid-cols-2 gap-12">
                <!-- Contact Form -->
                <div class="bg-white rounded-xl p-8 shadow-lg">
                    <!-- Using FormSubmit.co for immediate functional delivery.
                         To use Formspree instead, replace the action with your Formspree endpoint. -->
                    <form class="space-y-6" id="contactForm" method="POST" action="https://formsubmit.co/omb89@icloud.com">
                        <input type="hidden" name="_subject" value="Nuevo mensaje - Huella Eterna">
                        <input type="hidden" name="_captcha" value="false">
                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">Nombre completo</label>
                            <input name="name" required type="text" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent transition-all duration-300" placeholder="Tu nombre">
                        </div>

                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">Correo electrónico</label>
                            <input name="email" required type="email" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent transition-all duration-300" placeholder="tu@email.com">
                        </div>

                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">Teléfono</label>
                            <input name="phone" type="tel" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent transition-all duration-300" placeholder="+34 600 000 000">
                        </div>

                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">Mensaje</label>
                            <textarea name="message" rows="4" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent transition-all duration-300" placeholder="Cuéntanos sobre tu mascota y cómo podemos ayudarte..."></textarea>
                        </div>

                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">Foto de tu mascota (opcional)</label>
                            <div class="border-2 border-dashed border-gray-300 rounded-lg p-6 text-center hover:border-primary transition-colors duration-300">
                                <div class="w-12 h-12 flex items-center justify-center bg-gray-100 rounded-full mx-auto mb-3">
                                    <i class="ri-upload-line text-xl text-gray-600"></i>
                                </div>
                                <p class="text-gray-600">Arrastra una foto aquí o haz clic para seleccionar</p>
                                <input id="fileInput" name="photo" type="file" class="hidden" accept="image/*">
                            </div>
                        </div>

                        <button type="submit" class="w-full bg-primary hover:bg-secondary text-white py-3 !rounded-button transition-all duration-300 whitespace-nowrap">
                            Enviar mensaje
                        </button>
                    </form>
                </div>

                <!-- Contact Info -->
                <div class="space-y-8">
                    <div class="bg-white rounded-xl p-8 shadow-lg">
                        <h3 class="text-2xl font-medium text-gray-900 mb-6">Información de contacto</h3>

                        <div class="space-y-6">
                            <div class="flex items-center">
                                <div class="w-12 h-12 flex items-center justify-center bg-primary text-white rounded-full mr-4">
                                    <i class="ri-mail-line text-lg"></i>
                                </div>
                                <div>
                                    <p class="font-medium text-gray-900">Email</p>
                                    <p class="text-gray-600">contacto@huellaterna.com</p>
                                </div>
                            </div>

                            <div class="flex items-center">
                                <div class="w-12 h-12 flex items-center justify-center bg-primary text-white rounded-full mr-4">
                                    <i class="ri-phone-line text-lg"></i>
                                </div>
                                <div>
                                    <p class="font-medium text-gray-900">Teléfono</p>
                                    <p class="text-gray-600">+34 900 123 456</p>
                                </div>
                            </div>

                            <div class="flex items-center">
                                <div class="w-12 h-12 flex items-center justify-center bg-primary text-white rounded-full mr-4">
                                    <i class="ri-time-line text-lg"></i>
                                </div>
                                <div>
                                    <p class="font-medium text-gray-900">Horario de atención</p>
                                    <p class="text-gray-600">Lunes a Viernes: 9:00 - 18:00</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white rounded-xl p-8 shadow-lg">
                        <h3 class="text-xl font-medium text-gray-900 mb-4">Síguenos</h3>
                        <div class="flex space-x-4">
                            <a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-100 hover:bg-primary hover:text-white rounded-full transition-all duration-300">
                                <i class="ri-facebook-fill"></i>
                            </a>
                            <a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-100 hover:bg-primary hover:text-white rounded-full transition-all duration-300">
                                <i class="ri-instagram-fill"></i>
                            </a>
                            <a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-100 hover:bg-primary hover:text-white rounded-full transition-all duration-300">
                                <i class="ri-twitter-fill"></i>
                            </a>
                            <a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-100 hover:bg-primary hover:text-white rounded-full transition-all duration-300">
                                <i class="ri-youtube-fill"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-4 gap-8">
                <div>
                    <div class="flex items-center space-x-3 mb-4">
                        <div class="w-8 h-8 flex items-center justify-center bg-primary text-white rounded-full">
                            <img src="img/logo.svg" alt="logo" class="w-5 h-5">
                        </div>
                        <span class="font-['Pacifico'] text-xl text-primary">Huella Eterna</span>
                    </div>
                    <p class="text-gray-400 leading-relaxed">
                        Preservamos el amor y los recuerdos de tus mascotas para toda la eternidad.
                    </p>
                </div>

                <div>
                    <h3 class="font-medium mb-4">Servicios</h3>
                    <ul class="space-y-2 text-gray-400">
                        <li><a href="#" class="hover:text-white transition-colors">Memoriales digitales</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Álbumes personalizados</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Videos homenaje</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Certificados conmemorativos</a></li>
                    </ul>
                </div>

                <div>
                    <h3 class="font-medium mb-4">Recursos</h3>
                    <ul class="space-y-2 text-gray-400">
                        <li><a href="#" class="hover:text-white transition-colors">Guía de duelo</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Consejos de fotografía</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Testimonios</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Preguntas frecuentes</a></li>
                    </ul>
                </div>

                <div>
                    <h3 class="font-medium mb-4">Legal</h3>
                    <ul class="space-y-2 text-gray-400">
                        <li><a href="#" class="hover:text-white transition-colors">Política de privacidad</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Términos de servicio</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Cookies</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Contacto</a></li>
                    </ul>
                </div>
            </div>

            <div class="border-t border-gray-800 mt-12 pt-8 text-center text-gray-400">
                <p>&copy; 2024 Huella Eterna. Todos los derechos reservados. Hecho con ❤️ para las familias que aman a sus mascotas.</p>
            </div>
        </div>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
[style.css](https://github.com/user-attachments/files/22938440/style.css)

/* Minimal additional styles to preserve original animations and utilities */
.hero-bg {
    background-image: url('img/hero-bg.svg');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
}
.fade-in {
    animation: fadeIn 0.8s ease-in-out;
}
@keyframes fadeIn {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
}
.pulse-gentle {
    animation: pulseGentle 2s infinite;
}
@keyframes pulseGentle {
    0%, 100% { transform: scale(1); }
    50% { transform: scale(1.05); }
}
.bounce-in {
    animation: bounceIn 0.6s ease-out;
}
@keyframes bounceIn {
    0% { opacity: 0; transform: translateY(30px); }
    60% { opacity: 1; transform: translateY(-5px); }
    100% { opacity: 1; transform: translateY(0); }
}
.glow-hover:hover {
    box-shadow: 0 0 20px rgba(217, 119, 6, 0.3);
}
![cat1](https://github.com/user-attachments/assets/673f7475-4c06-47eb-950d-c560f29bfb69)
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 200 200"><rect width="100%" height="100%" fill="#f7f7fb"/><circle cx="100" cy="90" r="40" fill="#f59e0b"/><path d="M60 130c25-30 70-30 80 0v30H60z" fill="#d97706"/></svg>
[script.js](https://github.com/user-attachments/files/22938464/script.js)

document.addEventListener('DOMContentLoaded', function() {
    // Smooth nav scroll (for anchor links)
    const links = document.querySelectorAll('a[href^="#"]');
    links.forEach(link => {
        link.addEventListener('click', function(e) {
            e.preventDefault();
            const targetId = this.getAttribute('href');
            const targetSection = document.querySelector(targetId);
            if (targetSection) {
                targetSection.scrollIntoView({ behavior: 'smooth' });
            }
        });
    });

    // Gallery filters
    const filterButtons = document.querySelectorAll('#galeria .flex button');
    const galleryItems = document.querySelectorAll('#galeria [data-category]');

    filterButtons.forEach(button => {
        button.addEventListener('click', function() {
            filterButtons.forEach(btn => {
                btn.classList.remove('bg-primary', 'text-white');
                btn.classList.add('text-gray-600');
            });
            this.classList.add('bg-primary', 'text-white');
            this.classList.remove('text-gray-600');

            const category = this.textContent.trim().toLowerCase();
            galleryItems.forEach(item => {
                const itemCat = item.getAttribute('data-category') || '';
                if (category === 'todos' || itemCat === category) {
                    item.style.display = 'block';
                } else {
                    item.style.display = 'none';
                }
            });
        });
    });

    // Testimonial carousel
    const testimonials = [
        {
            name: 'María González',
            pet: 'Con Max, su Golden Retriever',
            image: 'img/dog1.svg',
            text: 'Gracias a Huella Eterna, siento que Max sigue conmigo cada día. El memorial digital que crearon capturó perfectamente su esencia alegre y juguetona. Cada vez que lo veo, sonrío recordando todos los momentos hermosos que compartimos juntos.'
        },
        {
            name: 'Carlos Mendoza',
            pet: 'Con Luna, su gata persa',
            image: 'img/cat1.svg',
            text: 'Luna fue mi compañera durante 15 años. Cuando la perdí, pensé que nunca podría superar el dolor. Huella Eterna me ayudó a crear un homenaje que celebra su vida y me trae paz cada día.'
        },
        {
            name: 'Ana Rodríguez',
            pet: 'Con Rocky, su labrador',
            image: 'img/dog2.svg',
            text: 'El servicio fue excepcional. No solo crearon un memorial hermoso para Rocky, sino que me acompañaron en todo el proceso con mucha sensibilidad.'
        }
    ];

    let currentTestimonial = 0;
    const testimonialContainer = document.querySelector('.testimonial-slide');
    const dots = document.querySelectorAll('#testimonios button');

    function updateTestimonial(index) {
        const testimonial = testimonials[index];
        testimonialContainer.innerHTML = `
            <div class="flex items-center mb-6">
                <img src="${testimonial.image}" alt="${testimonial.name}" class="w-16 h-16 rounded-full object-cover object-top mr-4">
                <div>
                    <h3 class="font-medium text-gray-900">${testimonial.name}</h3>
                    <p class="text-gray-600">${testimonial.pet}</p>
                </div>
            </div>
            <blockquote class="text-lg text-gray-700 italic leading-relaxed">
                "${testimonial.text}"
            </blockquote>
        `;
        dots.forEach((dot, i) => {
            if (i === index) {
                dot.classList.add('bg-primary');
                dot.classList.remove('bg-gray-300');
            } else {
                dot.classList.add('bg-gray-300');
                dot.classList.remove('bg-primary');
            }
        });
    }

    dots.forEach((dot, index) => {
        dot.addEventListener('click', () => {
            currentTestimonial = index;
            updateTestimonial(currentTestimonial);
        });
    });

    setInterval(() => {
        currentTestimonial = (currentTestimonial + 1) % testimonials.length;
        updateTestimonial(currentTestimonial);
    }, 5000);

    // File upload area
    const uploadArea = document.querySelector('#contacto .border-dashed');
    const fileInput = document.querySelector('#fileInput');

    if (uploadArea) {
        uploadArea.addEventListener('click', () => fileInput.click());
        uploadArea.addEventListener('dragover', (e) => {
            e.preventDefault();
            uploadArea.classList.add('border-primary', 'bg-primary', 'bg-opacity-5');
        });
        uploadArea.addEventListener('dragleave', () => {
            uploadArea.classList.remove('border-primary', 'bg-primary', 'bg-opacity-5');
        });
        uploadArea.addEventListener('drop', (e) => {
            e.preventDefault();
            uploadArea.classList.remove('border-primary', 'bg-primary', 'bg-opacity-5');
            const files = e.dataTransfer.files;
            if (files.length > 0) {
                fileInput.files = files;
                updateUploadText(files[0].name);
            }
        });
        fileInput.addEventListener('change', (e) => {
            if (e.target.files.length > 0) updateUploadText(e.target.files[0].name);
        });
    }

    function updateUploadText(fileName) {
        const textElement = document.querySelector('#contacto .border-dashed p');
        if (textElement) textElement.textContent = `Archivo seleccionado: ${fileName}`;
    }

    // Simple form validation + UX
    const form = document.querySelector('#contactForm');
    if (form) {
        form.addEventListener('submit', function(e) {
            // basic check: ensure required fields are filled (HTML also enforces)
            const name = form.querySelector('[name="name"]').value.trim();
            const email = form.querySelector('[name="email"]').value.trim();
            const message = form.querySelector('[name="message"]').value.trim();
            if (!name || !email || !message) {
                e.preventDefault();
                alert('Por favor completa los campos obligatorios: Nombre, Email y Mensaje.');
                return false;
            }
            // Let the form submit to formsubmit.co (or change action to Formspree if you set it up)
        });
    }
});
