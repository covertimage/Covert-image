<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bihar Bhumi Tools</title>
    <style>
        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f5f5f5;
            color: #333;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* Header */
        header {
            background: #1e90ff;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2em;
        }

        nav {
            margin-top: 10px;
        }

        nav a {
            margin: 0 15px;
            font-weight: bold;
            color: white;
            transition: 0.3s;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Sections */
        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }

        section h2 {
            text-align: center;
            margin-bottom: 30px;
            color: #1e90ff;
        }

        /* Tool Cards */
        .tool-card {
            background: white;
            padding: 20px;
            margin: 15px 0;
            border-radius: 10px;
            box-shadow: 0 3px 8px rgba(0,0,0,0.2);
            text-align: center;
        }

        .tool-card h3 {
            margin-top: 0;
            color: #333;
        }

        .tool-card p {
            margin: 10px 0 20px 0;
            color: #555;
        }

        .tool-card button {
            background: #1e90ff;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            transition: 0.3s;
        }

        .tool-card button:hover {
            background: #0d6efd;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: white;
            margin-top: 40px;
        }

        /* Responsive */
        @media(max-width: 600px){
            nav a {
                display: block;
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Bihar Bhumi Tools</h1>
        <nav>
            <a href="#image-tools">Image Tools</a>
            <a href="#text-tools">Text Tools</a>
            <a href="#other-tools">Other Tools</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Image Tools Section -->
    <section id="image-tools">
        <h2>Image Design Tools</h2>
        <div class="tool-card">
            <h3>Image Resizer</h3>
            <p>Resize your images easily for free.</p>
            <button onclick="alert('Image Resizer Tool')">Open Tool</button>
        </div>
        <div class="tool-card">
            <h3>Image Converter</h3>
            <p>Convert images to different formats like JPG, PNG, GIF.</p>
            <button onclick="alert('Image Converter Tool')">Open Tool</button>
        </div>
        <div class="tool-card">
            <h3>Image Compressor</h3>
            <p>Reduce image file size without losing quality.</p>
            <button onclick="alert('Image Compressor Tool')">Open Tool</button>
        </div>
    </section>

    <!-- Text Tools Section -->
    <section id="text-tools">
        <h2>Text Tools</h2>
        <div class="tool-card">
            <h3>Text Formatter</h3>
            <p>Format your text in different styles.</p>
            <button onclick="alert('Text Formatter Tool')">Open Tool</button>
        </div>
        <div class="tool-card">
            <h3>Text Counter</h3>
            <p>Count words and characters quickly.</p>
            <button onclick="alert('Text Counter Tool')">Open Tool</button>
        </div>
    </section>

    <!-- Other Tools Section -->
    <section id="other-tools">
        <h2>Other Tools</h2>
        <div class="tool-card">
            <h3>Color Picker</h3>
            <p>Pick colors and copy hex codes easily.</p>
            <button onclick="alert('Color Picker Tool')">Open Tool</button>
        </div>
        <div class="tool-card">
            <h3>QR Code Generator</h3>
            <p>Create QR codes for URLs or text instantly.</p>
            <button onclick="alert('QR Code Generator Tool')">Open Tool</button>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <div class="tool-card">
            <h3>Email</h3>
            <p>Send your queries or suggestions:</p>
            <p><a href="mailto:covertimage71@gmail.com">covertimage71@gmail.com</a></p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        &copy; 2025 Bihar Digital Seva. All rights reserved.
    </footer>

    <script>
        console.log("Bihar Bhumi Tools Home Page Loaded");
    </script>
</body>
</html>
