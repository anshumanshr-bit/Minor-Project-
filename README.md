# Minor-Project-
College minor project:- three core layers of web development—HTML, CSS, and JavaScript
1. The Head Section (<head>)
This part loads all the external styling tools and frameworks before the page loads:

Tailwind CSS CDN: Injected via a script tag so utility classes (like bg-blue-500, rounded-xl, flex) work instantly without a separate CSS file.

Google Fonts & Icons: Links to typography and vector icon libraries (like Lucide).

Custom Styles (<style> tag): Any custom animations, glassmorphism blur effects, or background gradient transitions are written right here.

2. The Body Section (<body>)
This contains the HTML structure—the actual layout elements you see on the screen:

Containers, search bars, buttons, weather cards, and modal popups.

They are styled using Tailwind CSS classes directly inside the HTML tags.

3. The Script Section (<script>)
At the very bottom of the page, all the JavaScript logic is wrapped inside a <script> tag. This handles everything dynamic:

Listening for user clicks and keyboard inputs.

Calling the OpenWeatherMap API using asynchronous fetch requests.

Processing the JSON response and updating the HTML text and icons dynamically.

Managing localStorage to save favorite cities.
