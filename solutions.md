HTML
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Typography Showcase</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=Source+Sans+3:ital,wght@0,400;0,600;1,400&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Typography Showcase</h1>
        <p class="subtitle">Exploring Fonts, Weights, and Text Styling</p>
    </header>

    <main>
        <section id="heading-styles">
            <h2>1. Heading Styles</h2>
            <h1>Heading 1 - Playfair Display Bold</h1>
            <h2>Heading 2 - Section Subtitle</h2>
            <h3>Heading 3 - Subsection Title</h3>
        </section>

        <section id="paragraph-styles">
            <h2>2. Paragraph Styles</h2>
            <p>This paragraph demonstrates standard body text utilizing Source Sans 3 with carefully calibrated line-height and letter-spacing for optimal readability and visual harmony across different screen sizes.</p>
            <p>A second paragraph follows to showcase block spacing and paragraph flow within a structured container.</p>
        </section>

        <section id="text-emphasis">
            <h2>3. Text Emphasis</h2>
            <p>Here is some <strong>bold text</strong> for strong importance, alongside <em>italicized text</em> representing distinct stress or font-style application.</p>
            <p>We can also apply <span class="highlight-underline">underlined text</span> and <span class="tracked-text">adjusted letter spacing</span> for specific visual effects.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Atim Akhtar. All rights reserved.</p>
    </footer>
</body>
</html>
CSS
/* style.css */
body {
    font-family: 'Source Sans 3', sans-serif;
    background-color: #f9f9fb;
    color: #2b2b2b;
    line-height: 1.8;
    letter-spacing: 0.3px;
    margin: 0;
    padding: 0;
}

header {
    background-color: #1e293b;
    color: #ffffff;
    text-align: center;
    padding: 2.5rem 1rem;
}

header h1 {
    font-family: 'Playfair Display', serif;
    font-size: 2.5rem;
    font-weight: 700;
    margin-bottom: 0.5rem;
    letter-spacing: 1px;
}

.subtitle {
    font-size: 1.1rem;
    font-style: italic;
    color: #94a3b8;
    margin: 0;
}

main {
    max-width: 800px;
    margin: 2rem auto;
    padding: 0 1.5rem;
}

section {
    background: #ffffff;
    padding: 2rem;
    margin-bottom: 1.5rem;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
}

h2 {
    font-family: 'Playfair Display', serif;
    color: #1e293b;
    font-size: 1.5rem;
    border-bottom: 2px solid #e2e8f0;
    padding-bottom: 0.5rem;
    margin-top: 0;
    margin-bottom: 1.2rem;
}

h1, h2, h3 {
    font-family: 'Playfair Display', serif;
    color: #334155;
}

section#heading-styles h1 {
    font-size: 2rem;
    font-weight: 700;
    margin: 0.5rem 0;
}

section#heading-styles h2 {
    font-size: 1.5rem;
    font-weight: 600;
    border-bottom: none;
    margin: 0.5rem 0;
}

section#heading-styles h3 {
    font-size: 1.2rem;
    font-weight: 400;
    font-style: italic;
    margin: 0.5rem 0;
}

p {
    margin-bottom: 1rem;
    font-size: 1.05rem;
}

strong {
    font-weight: 600;
    color: #0f172a;
}

em {
    font-style: italic;
    color: #475569;
}

.highlight-underline {
    text-decoration: underline;
    text-decoration-color: #3b82f6;
    text-underline-offset: 4px;
}

.tracked-text {
    letter-spacing: 2px;
    text-transform: uppercase;
    font-size: 0.95rem;
    font-weight: 600;
}

footer {
    text-align: center;
    padding: 1.5rem;
    color: #64748b;
    font-size: 0.9rem;
}