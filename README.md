<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NG Multi-Services</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="language-switcher">
            <button onclick="changeLanguage('fr')">Français</button>
            <button onclick="changeLanguage('ht')">Créole</button>
            <button onclick="changeLanguage('en')">English</button>
            <button onclick="changeLanguage('es')">Español</button>
        </div>
        <h1 id="header-title">NG Multi-Services</h1>
        <nav>
            <ul>
                <li><a href="#home" id="nav-home">Accueil</a></li>
                <li><a href="#services" id="nav-services">Services</a></li>
                <li><a href="#about" id="nav-about">À Propos</a></li>
                <li><a href="#contact" id="nav-contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2 id="home-title">Bienvenue chez NG Multi-Services</h2>
        <p id="home-text">Votre partenaire pour tous vos besoins en impression et design.</p>
    </section>

    <section id="services">
        <h2 id="services-title">Nos Services</h2>
        <ul>
            <li id="service-1">Impression et Copie</li>
            <li id="service-2">Conception Graphique</li>
            <li id="service-3">Photographie</li>
            <li id="service-4">Impression Sérigraphie</li>
            <li id="service-5">Services Financiers</li>
        </ul>
    </section>

    <section id="about">
        <h2 id="about-title">À Propos de Nous</h2>
        <p id="about-text">NG Multi-Services est une entreprise spécialisée dans l'impression, la conception graphique et les services financiers.</p>
    </section>

    <section id="contact">
        <h2 id="contact-title">Contactez-Nous</h2>
        <p id="contact-text">Pour toute demande, n'hésitez pas à nous contacter.</p>
    </section>

    <footer>
        <p id="footer-text">&copy; 2023 NG Multi-Services. Tous droits réservés.</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 20px;
    text-align: center;
}

.language-switcher {
    margin-bottom: 10px;
}

.language-switcher button {
    background-color: #555;
    color: white;
    border: none;
    padding: 5px 10px;
    margin: 0 5px;
    cursor: pointer;
}

.language-switcher button:hover {
    background-color: #777;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px;
    background-color: white;
    border-radius: 5px;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: white;
}

const translations = {
    fr: {
        "header-title": "NG Multi-Services",
        "nav-home": "Accueil",
        "nav-services": "Services",
        "nav-about": "À Propos",
        "nav-contact": "Contact",
        "home-title": "Bienvenue chez NG Multi-Services",
        "home-text": "Votre partenaire pour tous vos besoins en impression et design.",
        "services-title": "Nos Services",
        "service-1": "Impression et Copie",
        "service-2": "Conception Graphique",
        "service-3": "Photographie",
        "service-4": "Impression Sérigraphie",
        "service-5": "Services Financiers",
        "about-title": "À Propos de Nous",
        "about-text": "NG Multi-Services est une entreprise spécialisée dans l'impression, la conception graphique et les services financiers.",
        "contact-title": "Contactez-Nous",
        "contact-text": "Pour toute demande, n'hésitez pas à nous contacter.",
        "footer-text": "© 2023 NG Multi-Services. Tous droits réservés."
    },
    ht: {
        "header-title": "NG Multi-Services",
        "nav-home": "Akèy",
        "nav-services": "Sèvis",
        "nav-about": "Sou Nou",
        "nav-contact": "Kontak",
        "home-title": "Byenveni nan NG Multi-Services",
        "home-text": "Patenè w pou tout bezwen ou nan enprime ak konsepsyon.",
        "services-title": "Sèvis Nou Yo",
        "service-1": "Enprime ak Kopi",
        "service-2": "Konsepsyon Grafik",
        "service-3": "Fotografi",
        "service-4": "Enprime Serigrafi",
        "service-5": "Sèvis Finansye",
        "about-title": "Sou Nou",
        "about-text": "NG Multi-Services se yon antrepriz ki espesyalize nan enprime, konsepsyon grafik ak sèvis finansye.",
        "contact-title": "Kontakte Nou",
        "contact-text": "Pou tout demann, pa ezite kontakte nou.",
        "footer-text": "© 2023 NG Multi-Services. Tout dwa rezève."
    },
    en: {
        "header-title": "NG Multi-Services",
        "nav-home": "Home",
        "nav-services": "Services",
        "nav-about": "About Us",
        "nav-contact": "Contact",
        "home-title": "Welcome to NG Multi-Services",
        "home-text": "Your partner for all your printing and design needs.",
        "services-title": "Our Services",
        "service-1": "Printing and Copying",
        "service-2": "Graphic Design",
        "service-3": "Photography",
        "service-4": "Screen Printing",
        "service-5": "Financial Services",
        "about-title": "About Us",
        "about-text": "NG Multi-Services is a company specialized in printing, graphic design, and financial services.",
        "contact-title": "Contact Us",
        "contact-text": "For any inquiries, feel free to contact us.",
        "footer-text": "© 2023 NG Multi-Services. All rights reserved."
    },
    es: {
        "header-title": "NG Multi-Services",
        "nav-home": "Inicio",
        "nav-services": "Servicios",
        "nav-about": "Sobre Nosotros",
        "nav-contact": "Contacto",
        "home-title": "Bienvenido a NG Multi-Services",
        "home-text": "Su socio para todas sus necesidades de impresión y diseño.",
        "services-title": "Nuestros Servicios",
        "service-1": "Impresión y Copia",
        "service-2": "Diseño Gráfico",
        "service-3": "Fotografía",
        "service-4": "Impresión Serigráfica",
        "service-5": "Servicios Financieros",
        "about-title": "Sobre Nosotros",
        "about-text": "NG Multi-Services es una empresa especializada en impresión, diseño gráfico y servicios financieros.",
        "contact-title": "Contáctenos",
        "contact-text": "Para cualquier consulta, no dude en contactarnos.",
        "footer-text": "© 2023 NG Multi-Services. Todos los derechos reservados."
    }
};

function changeLanguage(lang) {
    const elements = document.querySelectorAll("[id]");
    elements.forEach(element => {
        const key = element.id;
        if (translations[lang] && translations[lang][key]) {
            element.textContent = translations[lang][key];
        }
    });
}

// Définir la langue par défaut
changeLanguage('fr');
