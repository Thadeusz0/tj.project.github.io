<!DOCTYPE html>
<html>
<head>
    <title>T&J Project</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            background-color: black; /* změna barvy pozadí na černou */
            color: white; /* změna barvy textu na bílou */
        }
        .centered-text {
            /* styly pro text uprostřed stránky */
            /* např. text-align: center; atd. */
            text-align: center; /* zarovnání textu na střed */
            margin-top: 50vh; /* posunutí textu na vertikální střed */
            transform: translateY(-50%); /* posunutí textu na vertikální střed */
            position: relative; /* nastavení relativní pozice pro umístění obrázku */
        }
        .centered-text::before {
            content: ""; /* prázdný obsah pro pseudo-element */
            display: block; /* zobrazení jako blokový element */
            position: absolute; /* nastavení absolutní pozice pro obrázek */
            top: 0; /* nastavení horního okraje na 0 */
            left: 0; /* nastavení levého okraje na 0 */
            right: 0; /* nastavení pravého okraje na 0 */
            bottom: 0; /* nastavení spodního okraje na 0 */
            background-image: url('https://github.com/Thadeusz0/tj.project.github.io/blob/main/TJ_Project_TJ'); /* odkaz na obrázek */
            background-size: cover; /* nastavení velikosti obrázku na "cover" */
            background-position: center; /* nastavení pozice obrázku na střed */
            opacity: 0.5; /* průhlednost obrázku */
            z-index: -1; /* nastavení z-indexu, aby byl obrázek za textem */
        }
    </style>
</head>
<body>
    <div class="centered-text">
        <h1>T&J Project starting soon...</h1>
    </div>
</body>
</html>
