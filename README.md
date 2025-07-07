
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estereotipos y Roles de Género</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #F8F8F8; /* Very light gray */
        }
        /* Removed container max-width as sections are no longer boxed */
        /* Removed section-card styles as they are no longer needed */
        .header-gradient {
            background: linear-gradient(to right, #20B2AA, #4682B4); /* Light Sea Green to Steel Blue gradient */
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        img {
            display: block;
            margin: 0 auto;
            border-radius: 1rem; /* Rounded corners for images */
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            max-width: 100%; /* Ensure responsiveness */
            height: auto; /* Maintain aspect ratio */
        }
        /* Custom styles for the message box */
        .message-box {
            background-color: #fefcbf; /* Light yellow */
            border-left: 4px solid #facc15; /* Yellow border */
            padding: 1rem;
            border-radius: 0.5rem;
            margin-top: 1rem;
            color: #854d0c; /* Darker yellow text */
        }
    </style>
</head>
<body class="p-4 sm:p-6 md:p-8">
    <!-- Main content area, no longer wrapped in a fixed-width container -->
    <div class="mx-auto py-8 max-w-4xl"> <!-- Increased max-width for better flow without boxes -->
        <!-- Main Title -->
        <h1 class="text-4xl sm:text-5xl md:text-6xl font-extrabold text-center mb-12 header-gradient">
            Estereotipos y Roles de Género
        </h1>

        <!-- Introduction -->
        <p class="text-lg sm:text-xl text-gray-700 text-center mb-12 px-4">
            Esta infografía te ayudará a entender qué son los estereotipos y los roles de género, y cuáles son sus consecuencias. Es importante destacar que los estereotipos de género afectan a niñas y niños desde edades muy tempranas, limitando su desarrollo.
        </p>

        <!-- Section 1: What are Estereotipos? -->
        <div class="mb-12 px-4"> <!-- Removed section-card, added padding and bottom margin -->
            <h2 class="text-3xl sm:text-4xl font-bold text-blue-600 mb-6">1. ¿Qué son los Estereotipos?</h2>
            <p class="text-gray-800 text-lg mb-4 leading-relaxed">
                Los estereotipos son <strong class="text-blue-500">creencias simplificadas y generalizadas</strong> sobre cómo son o deben ser los miembros de un grupo social.
                La sociedad tiene un conjunto de ideas sobre cómo se espera que los hombres y las mujeres se vistan, se comporten y se presenten.
            </p>
            <ul class="list-disc list-inside text-gray-700 text-base sm:text-lg space-y-2 pl-4">
                <li><strong class="text-blue-400">Ejemplos:</strong> "Los hombres no lloran", "Las mujeres son emocionales".</li>
                <li>Los estereotipos de género pueden clasificarse en cuatro tipos básicos: características de personalidad, comportamientos domésticos, ocupaciones y apariencia física.</li>
                <li>Las exageraciones de los comportamientos estereotípicos asociados a cada género se conocen como <strong class="text-blue-400">hiperfeminidad</strong> e <strong class="text-blue-400">hipermasculinidad</strong>.</li>
            </ul>
            <div class="flex justify-center mt-8">
                <!-- Static Image for Estereotipos section -->
                <img id="image1" src="https://placehold.co/300x200/AEC6CF/FFFFFF?text=Diversidad+de+Creencias" alt="Imagen sobre estereotipos" class="w-full max-w-xs sm:max-w-sm">
            </div>
        </div>

        <!-- Section 2: What are Roles de Género? -->
        <div class="mb-12 px-4"> <!-- Removed section-card, added padding and bottom margin -->
            <h2 class="text-3xl sm:text-4xl font-bold text-purple-600 mb-6">2. ¿Qué son los Roles de Género?</h2>
            <p class="text-gray-800 text-lg mb-4 leading-relaxed">
                Los roles de género son los <strong class="text-purple-500">comportamientos y atributos que una sociedad considera apropiados</strong> para hombres y mujeres.
                Definen cómo se espera que actuemos, hablemos, nos vistamos, nos arreglemos y nos comportemos según el sexo asignado al nacer.
            </p>
            <ul class="list-disc list-inside text-gray-700 text-base sm:text-lg space-y-2 pl-4">
                <li><strong class="text-purple-400">Ejemplos:</strong> Hombres como proveedores, mujeres como cuidadoras del hogar.</li>
            </ul>
            <div class="flex justify-center mt-8 p-4">
                <!-- Static Image for Roles de Género section -->
                <img id="image2" src="https://placehold.co/350x200/D8BFD8/FFFFFF?text=Roles+de+Genero" alt="Imagen sobre roles de género" class="w-full max-w-sm sm:max-w-md">
            </div>
        </div>

        <!-- Section 3: Consequences -->
        <div class="mb-12 px-4"> <!-- Removed section-card, added padding and bottom margin -->
            <h2 class="text-3xl sm:text-4xl font-bold text-green-600 mb-6">3. Consecuencias de los Estereotipos y Roles de Género Rígidos</h2>
            <p class="text-gray-800 text-lg mb-4 leading-relaxed">
                Pueden tener impactos negativos significativos:
            </p>

            <!-- Consequence: Limitation of Development -->
            <h3 class="text-2xl sm:text-3xl font-semibold text-green-500 mb-4">Limitación del Desarrollo</h3>
            <ul class="list-disc list-inside text-gray-700 text-base sm:text-lg space-y-2 pl-4 mb-6">
                <li>Impiden explorar intereses y carreras fuera de las expectativas de género, limitando el desarrollo de habilidades personales y la toma de decisiones vitales.</li>
            </ul>

            <!-- Consequence: Inequality and Discrimination -->
            <h3 class="text-2xl sm:text-3xl font-semibold text-green-500 mb-4">Desigualdad y Discriminación</h3>
            <ul class="list-disc list-inside text-gray-700 text-base sm:text-lg space-y-2 pl-4 mb-6">
                <li>Contribuyen a la brecha salarial y falta de representación.</li>
                <li>Los estereotipos de género pueden llevar a un trato desigual e injusto de las personas basado en su género, conocido como <strong class="text-green-400">sexismo</strong>.</li>
            </ul>

            <!-- Consequence: Mental Health Problems -->
            <h3 class="text-2xl sm:text-3xl font-semibold text-green-500 mb-4">Problemas de Salud Mental</h3>
            <ul class="list-disc list-inside text-gray-700 text-base sm:text-lg space-y-2 pl-4 mb-6">
                <li>Generan estrés, ansiedad y baja autoestima por la presión de conformarse.</li>
            </ul>

            <!-- Consequence: Gender Violence -->
            <h3 class="text-2xl sm:text-3xl font-semibold text-green-500 mb-4">Violencia de Género</h3>
            <ul class="list-disc list-inside text-gray-700 text-base sm:text-lg space-y-2 pl-4 mb-6">
                <li>Pueden perpetuar actitudes que justifican la violencia.</li>
            </ul>

            <div class="flex justify-center mt-8 p-4">
                <!-- Static Image for Consequences section -->
                <img id="image3" src="https://placehold.co/300x200/98FB98/FFFFFF?text=Consecuencias" alt="Imagen sobre consecuencias de estereotipos" class="w-full max-w-xs sm:max-w-sm">
            </div>
        </div>

        <!-- New Section: Combating Gender Stereotypes -->
        <div class="mt-12 px-4"> <!-- Removed section-card, added padding and top margin -->
            <h2 class="text-3xl sm:text-4xl font-bold text-orange-600 mb-6">4. Combatiendo los Estereotipos de Género</h2>
            <p class="text-gray-800 text-lg mb-4 leading-relaxed">
                Es fundamental tomar acción para desafiar y reducir el impacto de los estereotipos de género. Algunas formas de hacerlo incluyen:
            </p>
            <ul class="list-disc list-inside text-gray-700 text-base sm:text-lg space-y-2 pl-4">
                <li>Señalar los estereotipos cuando los observes.</li>
                <li>Ser un ejemplo positivo para otros, especialmente para niños y jóvenes.</li>
                <li>Pronunciarse contra comentarios sexistas.</li>
                <li>Buscar apoyo si estás luchando con las expectativas de género.</li>
            </ul>
        </div>

        <!-- New Section: Gemini API Feature - Stereotype Challenger -->
        <div class="mt-12 px-4"> <!-- Removed section-card, added padding and top margin -->
            <h2 class="text-3xl sm:text-4xl font-bold text-blue-700 mb-6">✨ Desafía un Estereotipo con IA ✨</h2>
            <p class="text-gray-800 text-lg mb-4 leading-relaxed">
                Escribe un estereotipo o una idea común sobre género, y la inteligencia artificial de Gemini te ofrecerá una perspectiva diferente o un contraargumento.
            </p>
            <textarea id="stereotypeInput" class="w-full p-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 mb-4" rows="4" placeholder="Ej: 'Las mujeres son malas conductoras' o 'Los hombres no expresan sus sentimientos'." required></textarea>
            <button id="challengeButton" class="w-full bg-blue-500 hover:bg-blue-600 text-white font-bold py-3 px-6 rounded-lg transition duration-300 ease-in-out transform hover:scale-105 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-opacity-50">
                ✨ Desafiar Estereotipo ✨
            </button>
            <div id="responseContainer" class="mt-6 p-4 bg-gray-100 rounded-lg border border-gray-200 hidden">
                <p class="text-gray-700 leading-relaxed" id="llmResponse"></p>
            </div>
            <div id="loadingIndicator" class="hidden text-center mt-4 text-blue-600 font-semibold">
                Cargando respuesta...
            </div>
            <div id="errorMessageBox" class="message-box hidden">
                <p id="errorMessageText"></p>
            </div>
        </div>

        <!-- APA Reference Section -->
        <div class="mt-12 px-4"> <!-- Removed section-card, added padding and top margin -->
            <h2 class="text-2xl sm:text-3xl font-bold text-gray-700 mb-4">Referencias</h2>
            <p class="text-gray-600 text-sm mb-2">
                Iberdrola. (s.f.). <cite>Estereotipos de género: qué son y cómo acabar con ellos</cite>. Recuperado de <a href="https://www.iberdrola.com/compromiso-social/estereotipos-de-genero" target="_blank" class="text-blue-600 hover:underline">https://www.iberdrola.com/compromiso-social/estereotipos-de-genero</a>
            </p>
            <p class="text-gray-600 text-sm">
                Planned Parenthood. (s.f.). <cite>¿Qué son los estereotipos de rol de género?</cite> Recuperado de <a href="https://www.plannedparenthood.org/es/temas-de-salud/identidad-de-genero/sexo-e-identidad-de-genero/que-son-los-estereotipos-de-rol-de-genero" target="_blank" class="text-blue-600 hover:underline">https://www.plannedparenthood.org/es/temas-de-salud/identidad-de-genero/sexo-e-identidad-de-genero/que-son-los-estereotipos-de-rol-de-genero</a>
            </p>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const challengeButton = document.getElementById('challengeButton');
            const stereotypeInput = document.getElementById('stereotypeInput');
            const responseContainer = document.getElementById('responseContainer');
            const llmResponse = document.getElementById('llmResponse');
            const loadingIndicator = document.getElementById('loadingIndicator');
            const errorMessageBox = document.getElementById('errorMessageBox');
            const errorMessageText = document.getElementById('errorMessageText');

            // Function to show a custom message box
            function showMessageBox(message, type = 'warning') {
                errorMessageText.textContent = message;
                errorMessageBox.className = 'message-box'; // Reset classes
                if (type === 'error') {
                    errorMessageBox.style.backgroundColor = '#fee2e2'; /* Red */
                    errorMessageBox.style.borderColor = '#ef4444'; /* Red */
                    errorMessageBox.style.color = '#991b1b'; /* Darker red */
                } else { // Default to warning
                    errorMessageBox.style.backgroundColor = '#fefcbf'; /* Light yellow */
                    errorMessageBox.style.borderColor = '#facc15'; /* Yellow */
                    errorMessageBox.style.color = '#854d0c'; /* Darker yellow */
                }
                errorMessageBox.classList.remove('hidden');
            }

            // Function to hide the custom message box
            function hideMessageBox() {
                errorMessageBox.classList.add('hidden');
            }

            challengeButton.addEventListener('click', async () => {
                const stereotype = stereotypeInput.value.trim();
                if (!stereotype) {
                    showMessageBox('Por favor, ingresa un estereotipo para desafiar.', 'warning');
                    return;
                }

                hideMessageBox(); // Hide any previous messages
                llmResponse.textContent = '';
                responseContainer.classList.add('hidden');
                loadingIndicator.classList.remove('hidden');

                let chatHistory = [];
                chatHistory.push({ role: "user", parts: [{ text: `Desafía el siguiente estereotipo de género o proporciona un contraargumento: "${stereotype}". Sé conciso y objetivo.` }] });
                const payload = { contents: chatHistory };
                const apiKey = ""; // Canvas will automatically provide the API key at runtime
                const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${apiKey}`;

                try {
                    const response = await fetch(apiUrl, {
                        method: 'POST',
                        headers: { 'Content-Type': 'application/json' },
                        body: JSON.stringify(payload)
                    });

                    if (!response.ok) {
                        let errorDetails = `Error: ${response.status} ${response.statusText}`;
                        try {
                            const errorJson = await response.json();
                            errorDetails += ` - ${errorJson.error.message || JSON.stringify(errorJson)}`;
                        } catch (jsonError) {
                            const errorText = await response.text();
                            errorDetails += ` - ${errorText.substring(0, 100)}... (not JSON)`;
                        }
                        throw new Error(`API response not OK: ${errorDetails}`);
                    }

                    const result = await response.json();

                    if (result.candidates && result.candidates.length > 0 &&
                        result.candidates[0].content && result.candidates[0].content.parts &&
                        result.candidates[0].content.parts.length > 0) {
                        const text = result.candidates[0].content.parts[0].text;
                        llmResponse.textContent = text;
                        responseContainer.classList.remove('hidden');
                    } else {
                        showMessageBox('No se pudo obtener una respuesta de la IA. Inténtalo de nuevo.', 'error');
                        console.error('Unexpected API response structure:', result);
                    }
                } catch (error) {
                    showMessageBox(`Error al comunicarse con la IA: ${error.message}.`, 'error');
                    console.error('Fetch error for Gemini API:', error);
                } finally {
                    loadingIndicator.classList.add('hidden');
                }
            });
        });
    </script>
</body>
</html>
```
