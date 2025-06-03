# Westie
<!DOCTYPE html>
<html lang="pl">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Dowiedz się wszystkiego o West Highland White Terrierach: ich pochodzeniu, zachowaniu, potrzebach żywieniowych oraz ciekawostkach.">
    <meta name="keywords" content="West Highland White Terrier, Westie, pies, zachowanie, pochodzenie, karmienie, ciekawostki, rasowe psy">
    <meta name="author" content="Twoje Imię">
    <title>West Highland White Terrier - Westie</title>
    <style>
        /* Ogólny wygląd strony */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }

        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px 0;
        }

        /* Header */
        header {
            background-color: #fff;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 2.5rem;
            color: #007BFF;
        }

        header nav ul {
            list-style: none;
            padding: 0;
            margin-top: 15px;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            text-decoration: none;
            color: #333;
            font-size: 1.1rem;
        }

        header nav ul li a:hover {
            color: #007BFF;
        }

        /* Sekcje */
        section {
            padding: 40px 0;
            background-color: #fff;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            font-size: 2rem;
            color: #007BFF;
            margin-bottom: 20px;
        }

        section p {
            font-size: 1rem;
            margin-bottom: 20px;
        }

        section img {
            width: 100%;
            height: auto;
            margin-top: 20px;
            border-radius: 8px;
        }

        /* Galeria */
        .gallery {
            display: flex;
            gap: 20px;
            justify-content: space-between;
        }

        .gallery img {
            width: 30%;
            border-radius: 8px;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }

        /* Animacja sekcji */
        section {
            opacity: 0;
            transition: opacity 1s ease-in-out;
        }

        section.visible {
            opacity: 1;
        }
    </style>
</head>

<body>
    <header>
        <div class="container">
            <h1>West Highland White Terrier - Westie</h1>
            <nav>
                <ul>
                    <li><a href="#pochodzenie">Pochodzenie</a></li>
                    <li><a href="#zachowanie">Zachowanie</a></li>
                    <li><a href="#karmienie">Karmienie</a></li>
                    <li><a href="#ciekawostki">Ciekawostki</a></li>
                    <li><a href="#galeria">Galeria</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="pochodzenie">
        <div class="container">
            <h2>Pochodzenie West Highland White Terrierów</h2>
            <p>West Highland White Terrier, znany także jako Westie, pochodzi ze Szkocji. Został wyhodowany przez Johna MacLeoda w XIX wieku, aby polować na małe zwierzęta, takie jak szczury i króliki. Ich charakterystyczna biała sierść i energiczna natura sprawiają, że są popularnymi towarzyszami w wielu domach na całym świecie.</p>
            <img src="images/westie1.jpg" alt="West Highland White Terrier">
        </div>
    </section>

    <section id="zachowanie">
        <div class="container">
            <h2>Zachowanie West Highland White Terrierów</h2>
            <p>Westie to psy bardzo energiczne, odważne i przyjazne. Mimo swojej niewielkiej wielkości, są niezwykle pewne siebie. Uwielbiają być w centrum uwagi i potrzebują dużo ruchu. Są towarzyskie, jednak mogą wykazywać niezależność, co sprawia, że są uparte. Dzięki temu, że są małe, dobrze sprawdzają się w mieszkaniach, ale i tak wymagają codziennych spacerów i zabaw.</p>
            <img src="images/westie2.jpg" alt="West Highland White Terrier podczas zabawy">
        </div>
    </section>

    <section id="karmienie">
        <div class="container">
            <h2>Karmienie West Highland White Terrierów</h2>
            <p>Westie mają specyficzne wymagania żywieniowe. Warto zapewnić im zbilansowaną dietę, bogatą w białko i tłuszcze. Zawsze należy wybierać karmy wysokiej jakości, które nie zawierają sztucznych dodatków. Zbyt duża ilość jedzenia może prowadzić do nadwagi, dlatego ważne jest kontrolowanie porcji. Pamiętaj także, by unikać karmienia ich nieodpowiednimi produktami, takimi jak czekolada czy kości.</p>
            <img src="images/westie3.jpg" alt="West Highland White Terrier jedzący">
        </div>
    </section>

    <section id="ciekawostki">
        <div class="container">
            <h2>Ciekawostki o West Highland White Terrierach</h2>
            <ul>
                <li>Westie są często używane w reklamach i filmach, np. w reklamie „RCA Victor” w latach 30-40.</li>
                <li>Ich sierść jest hypoalergiczna, co oznacza, że nie powodują silnych alergii u ludzi.</li>
                <li>Choć są małe, Westie mają instynkt myśliwski, który może przejawiać się w gonieniu małych zwierząt.</li>
                <li>Wielu właścicieli Westie chwali ich za wyjątkową inteligencję i łatwość w nauce komend.</li>
            </ul>
            <img src="images/westie4.jpg" alt="West Highland White Terrier w parku">
        </div>
    </section>

    <section id="galeria">
        <div class="container">
            <h2>Galeria West Highland White Terrierów</h2>
            <div class="gallery">
                <img src="images/westie5.jpg" alt="West Highland White Terrier w naturze">
                <img src="images/westie6.jpg" alt="West Highland White Terrier biegający po łące">
                <img src="images/westie7.jpg" alt="West Highland White Terrier na spacerze">
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 West Highland White Terrier - Wszystkie prawa zastrzeżone.</p>
        </div>
    </footer>

    <script>
        // Prosta animacja przy przewijaniu strony
        window.addEventListener('scroll', function () {
            const sections = document.querySelectorAll('section');
            sections.forEach((section) => {
                const rect = section.getBoundingClientRect();
                if (rect.top < window.innerHeight) {
                    section.classList.add('visible');
                } else {
                    section.classList.remove('visible');
                }
            });
        });
    </script>
</body>

</html>
