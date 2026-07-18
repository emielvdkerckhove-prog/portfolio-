<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mijn Portfolio</title>
    <style>
        /* Dit stukje (CSS) zorgt ervoor dat de site er netjes uitziet */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fafafa;
        }
        header {
            text-align: center;
            padding: 40px 0;
            background-color: #ffffff;
            border-bottom: 1px solid #eee;
            margin-bottom: 30px;
        }
        h1 { margin: 0; color: #111; }
        .intro { color: #666; font-size: 1.1em; }
        
        .categorie-sectie {
            margin-bottom: 40px;
        }
        .categorie-titel {
            color: #0066cc;
            border-bottom: 2px solid #0066cc;
            padding-bottom: 5px;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .project-kaart {
            background: #fff;
            padding: 20px;
            border-radius: 6px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
            border: 1px solid #e1e4e8;
        }
        .project-kaart h3 { margin-top: 0; color: #222; }
        .project-link {
            display: inline-block;
            margin-top: 10px;
            color: #0066cc;
            text-decoration: none;
            font-weight: bold;
        }
        .project-link:hover { text-decoration: underline; }
    </style>
</head>
<body>

    <header>
        <h1>[JOUW NAAM]</h1>
        <p class="intro">Welkom op mijn portfolio. Hieronder vind je een overzicht van mijn werk, opgedeeld in categorieën.</p>
    </header>

    <!-- CATEGORIE 1 -->
    <section class="categorie-sectie">
        <h2 class="categorie-titel">📸 Categorie 1: Fotografie / Ontwerp</h2>
        <div class="grid">
            <div class="project-kaart">
                <h3>Project Titel A</h3>
                <p>Korte beschrijving van wat je hier hebt gedaan. Wat was je rol en wat is het resultaat?</p>
                <a href="#" class="project-link">Bekijk project →</a>
            </div>
            <div class="project-kaart">
                <h3>Project Titel B</h3>
                <p>Korte beschrijving van het tweede project in deze categorie.</p>
                <a href="#" class="project-link">Bekijk project →</a>
            </div>
        </div>
    </section>

    <!-- CATEGORIE 2 -->
    <section class="categorie-sectie">
        <h2 class="categorie-titel">✍️ Categorie 2: Teksten / Copywriting</h2>
        <div class="grid">
            <div class="project-kaart">
                <h3>Project Titel C</h3>
                <p>Beschrijf hier je geschreven werk, een artikel of een andere prestatie.</p>
                <a href="#" class="project-link">Lees artikel →</a>
            </div>
        </div>
    </section>

    <!-- CATEGORIE 3 -->
    <section class="categorie-sectie">
        <h2 class="categorie-titel">🚀 Categorie 3: Andere Projecten</h2>
        <div class="grid">
            <div class="project-kaart">
                <h3>Project Titel D</h3>
                <p>Een omschrijving van een heel ander project waar je trots op bent.</p>
                <a href="#" class="project-link">Bekijk website →</a>
            </div>
        </div>
    </section>

</body>
</html># portfolio-
my portfolio 
