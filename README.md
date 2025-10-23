<!doctype html>
<html lang="cs">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>UZUM4KI Drift Organizace</title>
  <meta name="description" content="United Gaming Division - Společenství hráčů a profesionálů v herním průmyslu.">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">
  <style>
/* Reset and base styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #ffffff;
    background: linear-gradient(135deg, #0a0a0a, #1a1a1a, #2a2a2a);
    background-attachment: fixed;
    overflow-x: hidden;
}

body::before {
    content: '';
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="grain" width="100" height="100" patternUnits="userSpaceOnUse"><circle cx="25" cy="25" r="1" fill="%2300ff00" opacity="0.05"/><circle cx="75" cy="75" r="1" fill="%2300ff00" opacity="0.05"/></pattern></defs><rect width="100" height="100" fill="url(%23grain)"/></svg>');
    pointer-events: none;
    z-index: -1;
}

/* Navbar */
.navbar {
    background: rgba(0, 0, 0, 0.9);
    backdrop-filter: blur(10px);
    border-bottom: 1px solid rgba(255, 255, 255, 0.1);
}

.navbar-brand {
    color: #722F37 !important;
    font-weight: bold;
    font-size: 1.5rem;
}

.navbar-brand:hover {
    color: #FFFFFF !important;
    transition: color 0.8s;
}

.navbar-nav .nav-link {
    color: #ffffff;
    transition: color 0.3s;
}

.navbar-nav .nav-link:hover {
    color: #722F37;
}

/* Hero Section */
.hero {
    background: linear-gradient(45deg, rgba(0, 0, 0, 0.8), rgba(107, 12, 12, 0.2)), url('https://images.unsplash.com/photo-1632460353825-82a001c3716b?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1170');
    background-size: cover;
    background-position: center;
    min-height: 60vh;
    display: flex;
    align-items: center;
    position: relative;
}

.hero::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.6);
    z-index: 1;
}

.hero .container {
    position: relative;
    z-index: 2;
}

.hero h1 {
    font-size: 3rem;
    font-weight: bold;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.8);
    color: #722F37;
}

.hero .lead {
    font-size: 1.2rem;
    color: #cccccc;
}

.btn-primary {
    background-color: #722F37;
    border-color: #722F37;
    color: #000;
    font-weight: bold;
}

.btn-primary:hover {
    background-color: #722F37;
    border-color: #722F37;
}

.btn-outline-light {
    border-color: #ffffff;
    color: #ffffff;
}

.btn-outline-light:hover {
    background-color: #ffffff;
    color: #000;
}

/* Glass Effect */
.glass {
    background: rgba(255, 255, 255, 0.1);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255, 255, 255, 0.2);
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.glass-hover:hover {
    background: rgba(255, 255, 255, 0.15);
    transform: translateY(-2px);
    transition: all 0.3s;
}

/* Stats Section */
.stat {
    font-size: 2rem;
    font-weight: bold;
    color: #722F37;
}

.kpi {
    color: #722F37;
}

/* Sections */
section {
    padding: 60px 0;
}

section h2 {
    color: #722F37;
    font-weight: bold;
    margin-bottom: 30px;
}

.section-title {
    color: #722F37 !important;
}

/* Members */
#members .glass {
    transition: transform 0.3s;
}

#members .glass:hover {
    transform: translateY(-5px);
}

.member-name {
    color: #722F37;
    font-size: 1.2em;
}

/* Gallery */
#gallery img {
    transition: transform 0.3s;
}

#gallery img:hover {
    transform: scale(1.05);
}

/* Footer */
footer {
    background: rgba(0, 0, 0, 0.9);
    border-top: 1px solid rgba(255, 255, 255, 0.1);
}

footer .muted {
    color: #cccccc;
}

/* Responsive */
@media (max-width: 768px) {
    .hero h1 {
        font-size: 2rem;
    }
    .hero .lead {
        font-size: 1rem;
    }
    section {
        padding: 40px 0;
    }
}

/* Animations */
@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(30px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

section {
    animation: fadeInUp 1s ease-out;
}

/* Custom Scrollbar */
::-webkit-scrollbar {
    width: 8px;
}

::-webkit-scrollbar-track {
    background: #1a1a1a;
}

::-webkit-scrollbar-thumb {
    background: #722F37;
    border-radius: 4px;
}

::-webkit-scrollbar-thumb:hover {
    background: #5a1f2a;
}
  </style>
</head>

<body>
  <nav class="navbar navbar-expand-lg sticky-top border-bottom border-opacity-25 border-white">
    <div class="container py-2">
      <a class="navbar-brand fw-bold" href="#">UZUM4KI 漩渦</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#nav"><span class="navbar-toggler-icon"></span></button>
      <div class="collapse navbar-collapse" id="nav">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item"><a class="nav-link" href="#about">O nás</a></li>
          <li class="nav-item"><a class="nav-link" href="#members">Členové</a></li>
          <li class="nav-item"><a class="nav-link" href="#events">Události</a></li>
          <li class="nav-item"><a class="nav-link" href="#gallery">Galerie</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Kontakt</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <header class="hero py-5">
    <div class="container">
      <h1 class="display-5 fw-bold">UZUM4KI DR1FT GR0UP</h1>
      <p class="lead muted mt-3">Neoficiální organizace na serveru Skimo RP, zaměřená na driftování.</p>
    </div>
  </header>

  <section id="stats" class="py-5">
    <div class="container">
      <div class="row g-4">
        <div class="col-12 col-lg-4"><div class="glass p-3 glass-hover"><div class="muted">Aktivní členové</div><div class="stat kpi">1</div></div></div>
        <div class="col-12 col-lg-4"><div class="glass p-3 glass-hover"><div class="muted">Uspořádaných projížďek</div><div class="stat kpi">0</div></div></div>
        <div class="col-12 col-lg-4"><div class="glass p-3 glass-hover"><div class="muted">Let hraní</div><div class="stat kpi">5+</div></div></div>
      </div>
    </div>
  </section>

  <section id="about" class="pb-2">
    <div class="container">
      <div class="glass p-4">
        <h2 class="section-title h4 mb-3">O nás / 關於我們</h2>
        <p class="mb-0">UDG je společenství hráčů SkimoRP, kteří milují driftování. Plánujeme organizovat noční projížďky a později také komunitní akce.</p>
      </div>
    </div>
  </section>

  <section id="members" class="py-5">
    <div class="container">
      <h2 class="section-title h4 m-0 mb-3">Členové / 成員</h2>
      <div class="row g-3">
        <div class="col-12 col-md-6 col-lg-4">
          <div class="glass p-3 h-100">
            <div class="member-name fw-bold">Amir Corleone</div>
            <div class="muted small">CEO, personalista a organizátor</div>
            <div class="muted small">Auto: Dodge Charger 3.6 V6 ER3B6 - Turbocharged</div>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4">
          <div class="glass p-3 h-100">
            <div class="member-name fw-bold">Kinoko Yokashi</div>
            <div class="muted small">Manažerka, organizátorka srazů</div>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4">
          <div class="glass p-3 h-100">
            <div class="member-name fw-bold">Yogashi Ling Dong</div>
            <div class="muted small">Personalista, nábor do komunity</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="events" class="py-5">
    <div class="container">
      <div class="glass p-4">
        <h2 class="section-title h4 mb-3">Nadcházející události / 活動</h2>
        <ul class="list-unstyled">
          <li class="mb-3">
            <div class="fw-bold">Night Cruise</div>
            <div class="muted small">Naše první menší projížďka se uskuteční již brzy!</div>
          </li>
          <li class="mb-3">
            <div class="fw-bold">Soutěž o LEXUS IS300 + tuning</div>
            <div class="muted small">cca 21.02.2026</div>
          </li>
          <li>
            <div class="fw-bold">x</div>
            <div class="muted small">x</div>
          </li>
        </ul>
      </div>
    </div>
  </section>

  <section id="gallery" class="py-5">
    <div class="container">
      <h2 class="section-title h4 m-0 mb-3">Galerie</h2>
      <div class="row g-3">
        <div class="col-12 col-md-6 col-lg-4">
          <div class="glass p-3">
            <img src="https://via.placeholder.com/300x200?text=Turnaj+1" alt="Turnaj 1" class="img-fluid rounded">
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4">
          <div class="glass p-3">
            <img src="https://via.placeholder.com/300x200?text=LAN+Party" alt="LAN Party" class="img-fluid rounded">
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4">
          <div class="glass p-3">
            <img src="https://via.placeholder.com/300x200?text=Workshop" alt="Workshop" class="img-fluid rounded">
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="contact" class="pb-5">
    <div class="container">
      <div class="glass p-4">
        <h2 class="section-title h4 mb-3">Kontakt</h2>
        <p class="muted">Máte zájem se připojit nebo spolupracovat? Kontaktujte nás!</p>
        <div class="row g-3">
          <div class="col-12 col-md-6">
            <div class="fw-bold">Email</div>
            <div class="muted">info@udo.ic</div>
          </div>
          <div class="col-12 col-md-6">
            <div class="fw-bold">Discord</div>
            <div class="muted">UDO SKIMO-RP</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer class="py-4 border-top border-opacity-25 border-white">
    <div class="container d-flex flex-wrap justify-content-between align-items-center">
      <div class="muted">© 2024 Uzumaki Drift Organizationn</div>
      <button id="toTop" class="btn btn-outline-light btn-sm" type="button"><i class="fa-solid fa-arrow-up me-1"></i>Nahoru</button>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script>
// Smooth scrolling for navigation links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
            target.scrollIntoView({
                behavior: 'smooth',
                block: 'start'
            });
        }
    });
});

// Scroll to top button
const toTopBtn = document.getElementById('toTop');
window.addEventListener('scroll', () => {
    if (window.pageYOffset > 100) {
        toTopBtn.style.display = 'block';
    } else {
        toTopBtn.style.display = 'none';
    }
});

toTopBtn.addEventListener('click', () => {
    window.scrollTo({
        top: 0,
        behavior: 'smooth'
    });
});

// Add animation on scroll
const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px 0px -50px 0px'
};

const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.style.opacity = '1';
            entry.target.style.transform = 'translateY(0)';
        }
    });
}, observerOptions);

document.querySelectorAll('section').forEach(section => {
    section.style.opacity = '0';
    section.style.transform = 'translateY(30px)';
    section.style.transition = 'opacity 0.6s ease-out, transform 0.6s ease-out';
    observer.observe(section);
});

// Navbar background change on scroll
window.addEventListener('scroll', () => {
    const navbar = document.querySelector('.navbar');
    if (window.scrollY > 50) {
        navbar.style.background = 'rgba(0, 0, 0, 0.95)';
    } else {
        navbar.style.background = 'rgba(0, 0, 0, 0.9)';
    }
});
  </script>
</body>
</html>
