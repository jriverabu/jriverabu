<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Juan David Rivera - Perfil Profesional</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        :root {
            --primary: #015646;
            --secondary: #0ea5e9;
            --dark: #1f2937;
            --light: #f3f4f6;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', system-ui, sans-serif;
        }

        body {
            background: linear-gradient(to bottom, #1a1a1a, #2d3748);
            color: white;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        .header {
            text-align: center;
            margin-bottom: 3rem;
        }

        .header h1 {
            font-size: 3rem;
            background: linear-gradient(to right, #10b981, #3b82f6);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            margin-bottom: 1rem;
        }

        .header h2 {
            color: #10b981;
            font-size: 1.5rem;
            margin-bottom: 2rem;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-bottom: 2rem;
        }

        .social-links a {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 45px;
            height: 45px;
            border-radius: 50%;
            color: white;
            text-decoration: none;
            transition: transform 0.3s;
        }

        .social-links a:hover {
            transform: translateY(-3px);
        }

        .linkedin { background: #0077b5; }
        .twitter { background: #1da1f2; }
        .github { background: #333; }
        .email { background: #ea4335; }

        .card {
            background: rgba(31, 41, 55, 0.5);
            border-radius: 1rem;
            padding: 2rem;
            margin-bottom: 2rem;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .card h2 {
            color: #10b981;
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
            margin: 2rem 0;
        }

        .skill-category {
            background: rgba(31, 41, 55, 0.7);
            border-radius: 0.75rem;
            padding: 1.5rem;
        }

        .skill-category h3 {
            color: #10b981;
            margin-bottom: 1rem;
        }

        .skills-list {
            display: flex;
            flex-wrap: wrap;
            gap: 0.75rem;
        }

        .skill-tag {
            background: rgba(55, 65, 81, 0.7);
            padding: 0.5rem 1rem;
            border-radius: 9999px;
            font-size: 0.875rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .skill-tag i {
            color: #10b981;
        }

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
        }

        .project-card {
            background: rgba(55, 65, 81, 0.7);
            border-radius: 0.75rem;
            padding: 1.5rem;
            transition: transform 0.3s;
        }

        .project-card:hover {
            transform: translateY(-5px);
        }

        .project-card h3 {
            color: white;
            margin-bottom: 0.75rem;
        }

        .project-card p {
            color: #d1d5db;
            font-size: 0.875rem;
            margin-bottom: 1rem;
        }

        .project-link {
            color: #10b981;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            font-size: 0.875rem;
        }

        .project-link:hover {
            color: #059669;
        }

        .contact-section {
            text-align: center;
        }

        .contact-button {
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            background: #10b981;
            color: white;
            text-decoration: none;
            padding: 0.75rem 1.5rem;
            border-radius: 0.5rem;
            font-weight: 500;
            transition: background-color 0.3s;
        }

        .contact-button:hover {
            background: #059669;
        }

        @media (max-width: 768px) {
            .container {
                padding: 1rem;
            }

            .header h1 {
                font-size: 2rem;
            }

            .header h2 {
                font-size: 1.25rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <h1>Hola, soy Juan David Rivera</h1>
            <h2>🚀 Experto en Marketing Digital | 🤖 Entusiasta de IA | 💻 Desarrollador</h2>
            <div class="social-links">
                <a href="https://linkedin.com/in/tu-usuario" class="linkedin" title="LinkedIn">
                    <i class="fab fa-linkedin-in"></i>
                </a>
                <a href="https://twitter.com/tu-usuario" class="twitter" title="Twitter">
                    <i class="fab fa-twitter"></i>
                </a>
                <a href="https://github.com/tu-usuario" class="github" title="GitHub">
                    <i class="fab fa-github"></i>
                </a>
                <a href="mailto:tu-email@ejemplo.com" class="email" title="Email">
                    <i class="fas fa-envelope"></i>
                </a>
            </div>
        </header>

        <section class="card">
            <h2><i class="fas fa-bullseye"></i> Sobre mí</h2>
            <p>Soy un profesional multifacético con experiencia en marketing digital, desarrollo de software e inteligencia artificial. 
            Mi pasión es combinar estas disciplinas para crear soluciones innovadoras y efectivas.</p>
            <ul style="list-style: none; margin-top: 1rem;">
                <li><i class="fas fa-rocket"></i> Actualmente estoy trabajando en <strong>campañas de marketing impulsadas por IA</strong></li>
                <li><i class="fas fa-seedling"></i> Estoy aprendiendo <strong>nuevas aplicaciones de LLMs en marketing</strong></li>
                <li><i class="fas fa-users"></i> Busco colaborar en <strong>proyectos que integren marketing, IA y desarrollo</strong></li>
                <li><i class="fas fa-comments"></i> Pregúntame sobre <strong>estrategias de marketing digital, IA generativa, o desarrollo de apps</strong></li>
            </ul>
        </section>

        <div class="skills-grid">
            <div class="skill-category">
                <h3><i class="fas fa-chart-line"></i> Marketing Digital & CRM</h3>
                <div class="skills-list">
                    <span class="skill-tag"><i class="fab fa-google"></i> Google Analytics</span>
                    <span class="skill-tag"><i class="fab fa-google"></i> Google Ads</span>
                    <span class="skill-tag"><i class="fab fa-facebook-f"></i> Facebook Ads</span>
                    <span class="skill-tag"><i class="fas fa-envelope"></i> Mailchimp</span>
                    <span class="skill-tag"><i class="fas fa-h-square"></i> HubSpot</span>
                    <span class="skill-tag"><i class="fab fa-salesforce"></i> Salesforce</span>
                </div>
            </div>

            <div class="skill-category">
                <h3><i class="fas fa-robot"></i> Inteligencia Artificial</h3>
                <div class="skills-list">
                    <span class="skill-tag"><i class="fas fa-brain"></i> ChatGPT</span>
                    <span class="skill-tag"><i class="fas fa-code"></i> GPT-3</span>
                    <span class="skill-tag"><i class="fas fa-image"></i> DALL·E</span>
                    <span class="skill-tag"><i class="fab fa-python"></i> TensorFlow</span>
                    <span class="skill-tag"><i class="fas fa-fire"></i> PyTorch</span>
                    <span class="skill-tag"><i class="fas fa-code-branch"></i> Hugging Face</span>
                </div>
            </div>

            <div class="skill-category">
                <h3><i class="fas fa-laptop-code"></i> Desarrollo</h3>
                <div class="skills-list">
                    <span class="skill-tag"><i class="fab fa-python"></i> Python</span>
                    <span class="skill-tag"><i class="fab fa-js"></i> JavaScript</span>
                    <span class="skill-tag"><i class="fab fa-react"></i> React</span>
                    <span class="skill-tag"><i class="fab fa-node-js"></i> Node.js</span>
                    <span class="skill-tag"><i class="fas fa-database"></i> SQL</span>
                    <span class="skill-tag"><i class="fab fa-git-alt"></i> Git</span>
                </div>
            </div>
        </div>

        <section class="card">
            <h2><i class="fas fa-star"></i> Proyectos Destacados</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3>IA Marketing Analytics</h3>
                    <p>Plataforma de análisis de marketing impulsada por IA para optimización de campañas.</p>
                    <a href="#" class="project-link">
                        Ver proyecto <i class="fas fa-external-link-alt"></i>
                    </a>
                </div>
                <div class="project-card">
                    <h3>Sentiment Analysis Tool</h3>
                    <p>Herramienta de análisis de sentimientos para feedback de clientes.</p>
                    <a href="#" class="project-link">
                        Ver proyecto <i class="fas fa-external-link-alt"></i>
                    </a>
                </div>
            </div>
        </section>

        <footer class="card contact-section">
            <h2><i class="fas fa-handshake"></i> ¡Conectemos!</h2>
            <p>¿Interesado en colaborar en proyectos innovadores de marketing digital o IA?<br>
            ¡Contáctame! Siempre estoy abierto a nuevas oportunidades y desafíos emocionantes.</p>
            <div style="margin-top: 1.5rem;">
                <a href="mailto:tu-email@ejemplo.com" class="contact-button">
                    <i class="fas fa-envelope"></i> Contactar
                </a>
            </div>
        </footer>
    </div>
</body>
</html>

