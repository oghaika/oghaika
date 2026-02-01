<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Haika - Developer Portfolio</title>
    <meta name="description" content="Haika - Full Stack Developer especializado em JavaScript, TypeScript, React, EJS, PHP, HTML e CSS">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Animated Background -->
    <div class="bg-animation">
        <div class="stars"></div>
        <div class="stars2"></div>
        <div class="stars3"></div>
    </div>

    <!-- Navigation -->
    <nav class="navbar">
        <div class="nav-container">
            <div class="nav-logo">
                <svg class="logo-icon" width="32" height="32" viewBox="0 0 32 32" fill="none">
                    <path d="M16 2L2 9L16 16L30 9L16 2Z" fill="url(#gradient1)"/>
                    <path d="M2 23L16 30L30 23V9L16 16L2 9V23Z" fill="url(#gradient2)"/>
                    <defs>
                        <linearGradient id="gradient1" x1="2" y1="2" x2="30" y2="16">
                            <stop offset="0%" stop-color="#667eea"/>
                            <stop offset="100%" stop-color="#764ba2"/>
                        </linearGradient>
                        <linearGradient id="gradient2" x1="2" y1="9" x2="30" y2="30">
                            <stop offset="0%" stop-color="#f093fb"/>
                            <stop offset="100%" stop-color="#f5576c"/>
                        </linearGradient>
                    </defs>
                </svg>
                <span class="logo-text">haika</span>
            </div>
            <div class="nav-links">
                <a href="#repositories" class="nav-link">Repositórios</a>
                <a href="#projects" class="nav-link">Projetos</a>
                <a href="#about" class="nav-link">Sobre</a>
                <a href="#contact" class="nav-link">Contato</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-container">
            <div class="hero-content">
                <div class="profile-section">
                    <div class="profile-image-wrapper">
                        <div class="profile-ring"></div>
                        <div class="profile-image">
                            <svg width="120" height="120" viewBox="0 0 120 120" fill="none">
                                <circle cx="60" cy="60" r="60" fill="url(#profileGradient)"/>
                                <text x="60" y="75" font-size="48" font-weight="600" fill="white" text-anchor="middle" font-family="Inter">H</text>
                                <defs>
                                    <linearGradient id="profileGradient" x1="0" y1="0" x2="120" y2="120">
                                        <stop offset="0%" stop-color="#667eea"/>
                                        <stop offset="100%" stop-color="#764ba2"/>
                                    </linearGradient>
                                </defs>
                            </svg>
                        </div>
                    </div>
                    <div class="status-badge">
                        <span class="status-dot"></span>
                        Disponível para projetos
                    </div>
                </div>

                <h1 class="hero-title">
                    <span class="greeting">Olá, eu sou</span>
                    <span class="name">Haika</span>
                    <span class="role">Full Stack Developer</span>
                </h1>

                <p class="hero-description">
                    Desenvolvedor apaixonado por criar experiências web incríveis.
                    Especializado em construir aplicações modernas e escaláveis.
                </p>

                <div class="tech-stack">
                    <div class="tech-item" style="--delay: 0s">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
                            <path d="M3 3h18v18H3V3z" fill="#F7DF1E"/>
                            <path d="M7.5 15.5c0 1.5 1 2 2.5 2s2.5-.5 2.5-2v-6h-2v6c0 .5-.2.7-.5.7s-.5-.2-.5-.7v-6h-2v6zm7-6h2c0-.5.2-.7.5-.7s.5.2.5.7v1h-3v2h3v2.5c0 1.5-1 2-2.5 2s-2.5-.5-2.5-2v-1h2v1c0 .5.2.7.5.7s.5-.2.5-.7v-4c0-1.5 1-2 2.5-2s2.5.5 2.5 2v1h-2v-1c0-.5-.2-.7-.5-.7s-.5.2-.5.7v1z" fill="#000"/>
                        </svg>
                        <span>JavaScript</span>
                    </div>
                    <div class="tech-item" style="--delay: 0.1s">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
                            <path d="M3 3h18v18H3V3z" fill="#3178C6"/>
                            <path d="M13.5 15.5h2v-2h-2v2zm-3-6h2v-2h-2v2zm3 0h2v-2h-2v2zm3 0h2v-2h-2v2z" fill="#fff"/>
                        </svg>
                        <span>TypeScript</span>
                    </div>
                    <div class="tech-item" style="--delay: 0.2s">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
                            <circle cx="12" cy="12" r="9" fill="#61DAFB"/>
                            <ellipse cx="12" cy="12" rx="9" ry="3" stroke="#000" stroke-width="1" fill="none"/>
                            <ellipse cx="12" cy="12" rx="3" ry="9" stroke="#000" stroke-width="1" fill="none"/>
                        </svg>
                        <span>React</span>
                    </div>
                    <div class="tech-item" style="--delay: 0.3s">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
                            <path d="M12 2L2 7v10l10 5 10-5V7L12 2z" fill="#8993be"/>
                        </svg>
                        <span>EJS</span>
                    </div>
                    <div class="tech-item" style="--delay: 0.4s">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
                            <ellipse cx="12" cy="12" rx="10" ry="6" fill="#777BB4"/>
                        </svg>
                        <span>PHP</span>
                    </div>
                    <div class="tech-item" style="--delay: 0.5s">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
                            <path d="M3 3h18v18H3V3z" fill="#E34F26"/>
                            <path d="M6 6h12l-1 12-5 2-5-2-1-12z" fill="#fff"/>
                        </svg>
                        <span>HTML</span>
                    </div>
                    <div class="tech-item" style="--delay: 0.6s">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
                            <path d="M3 3h18v18H3V3z" fill="#1572B6"/>
                            <path d="M6 6h12l-1 12-5 2-5-2-1-12z" fill="#fff"/>
                        </svg>
                        <span>CSS</span>
                    </div>
                </div>

                <div class="cta-buttons">
                    <a href="#projects" class="btn btn-primary">
                        <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                            <path d="M10 2a8 8 0 100 16 8 8 0 000-16zM9 14V9h2v5H9zm0-6V6h2v2H9z" fill="currentColor"/>
                        </svg>
                        Ver Projetos
                    </a>
                    <a href="#contact" class="btn btn-secondary">
                        <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                            <path d="M2 4l8 5 8-5v10a2 2 0 01-2 2H4a2 2 0 01-2-2V4z" stroke="currentColor" stroke-width="2" fill="none"/>
                        </svg>
                        Entrar em Contato
                    </a>
                </div>
            </div>

            <div class="hero-visual">
                <div class="code-window">
                    <div class="window-header">
                        <div class="window-controls">
                            <span class="control close"></span>
                            <span class="control minimize"></span>
                            <span class="control maximize"></span>
                        </div>
                        <div class="window-title">haika.js</div>
                    </div>
                    <div class="window-content">
                        <pre><code><span class="keyword">const</span> <span class="variable">developer</span> = {
  <span class="property">name</span>: <span class="string">'Haika'</span>,
  <span class="property">role</span>: <span class="string">'Full Stack Developer'</span>,
  <span class="property">skills</span>: [
    <span class="string">'JavaScript'</span>,
    <span class="string">'TypeScript'</span>,
    <span class="string">'React'</span>,
    <span class="string">'Node.js'</span>
  ],
  <span class="property">passion</span>: <span class="string">'Building amazing things'</span>,
  <span class="method">code</span>: <span class="keyword">function</span>() {
    <span class="keyword">return</span> <span class="string">'Clean & Efficient'</span>;
  }
};

<span class="comment">// Always learning, always growing</span>
<span class="variable">developer</span>.<span class="method">code</span>();</code></pre>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="stats-section">
        <div class="stats-container">
            <div class="stat-card">
                <div class="stat-icon">
                    <svg width="32" height="32" viewBox="0 0 32 32" fill="none">
                        <path d="M8 4h16v24H8V4z" stroke="url(#statGrad1)" stroke-width="2" fill="none"/>
                        <path d="M12 12h8M12 16h8M12 20h5" stroke="url(#statGrad1)" stroke-width="2"/>
                        <defs>
                            <linearGradient id="statGrad1" x1="8" y1="4" x2="24" y2="28">
                                <stop offset="0%" stop-color="#667eea"/>
                                <stop offset="100%" stop-color="#764ba2"/>
                            </linearGradient>
                        </defs>
                    </svg>
                </div>
                <div class="stat-number" data-target="50">0</div>
                <div class="stat-label">Projetos Concluídos</div>
            </div>

            <div class="stat-card">
                <div class="stat-icon">
                    <svg width="32" height="32" viewBox="0 0 32 32" fill="none">
                        <circle cx="16" cy="16" r="12" stroke="url(#statGrad2)" stroke-width="2" fill="none"/>
                        <path d="M16 8v8l4 4" stroke="url(#statGrad2)" stroke-width="2"/>
                        <defs>
                            <linearGradient id="statGrad2" x1="4" y1="4" x2="28" y2="28">
                                <stop offset="0%" stop-color="#f093fb"/>
                                <stop offset="100%" stop-color="#f5576c"/>
                            </linearGradient>
                        </defs>
                    </svg>
                </div>
                <div class="stat-number" data-target="3">0</div>
                <div class="stat-label">Anos de Experiência</div>
            </div>

            <div class="stat-card">
                <div class="stat-icon">
                    <svg width="32" height="32" viewBox="0 0 32 32" fill="none">
                        <path d="M16 4l4 8h8l-6 6 2 8-8-4-8 4 2-8-6-6h8l4-8z" stroke="url(#statGrad3)" stroke-width="2" fill="none"/>
                        <defs>
                            <linearGradient id="statGrad3" x1="4" y1="4" x2="28" y2="28">
                                <stop offset="0%" stop-color="#4facfe"/>
                                <stop offset="100%" stop-color="#00f2fe"/>
                            </linearGradient>
                        </defs>
                    </svg>
                </div>
                <div class="stat-number" data-target="100">0</div>
                <div class="stat-label">Commits Este Mês</div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="footer-content">
            <p>&copy; 2026 Haika. Desenvolvido com dedicação e café.</p>
            <div class="social-links">
                <a href="#" class="social-link" aria-label="GitHub">
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                        <path d="M12 2C6.477 2 2 6.477 2 12c0 4.42 2.865 8.17 6.839 9.49.5.092.682-.217.682-.482 0-.237-.008-.866-.013-1.7-2.782.603-3.369-1.34-3.369-1.34-.454-1.156-1.11-1.463-1.11-1.463-.908-.62.069-.608.069-.608 1.003.07 1.531 1.03 1.531 1.03.892 1.529 2.341 1.087 2.91.831.092-.646.35-1.086.636-1.336-2.22-.253-4.555-1.11-4.555-4.943 0-1.091.39-1.984 1.029-2.683-.103-.253-.446-1.27.098-2.647 0 0 .84-.269 2.75 1.025A9.578 9.578 0 0112 6.836c.85.004 1.705.114 2.504.336 1.909-1.294 2.747-1.025 2.747-1.025.546 1.377.203 2.394.1 2.647.64.699 1.028 1.592 1.028 2.683 0 3.842-2.339 4.687-4.566 4.935.359.309.678.919.678 1.852 0 1.336-.012 2.415-.012 2.743 0 .267.18.578.688.48C19.138 20.167 22 16.418 22 12c0-5.523-4.477-10-10-10z"/>
                    </svg>
                </a>
                <a href="#" class="social-link" aria-label="LinkedIn">
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                        <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
                    </svg>
                </a>
                <a href="#" class="social-link" aria-label="Twitter">
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                        <path d="M23.953 4.57a10 10 0 01-2.825.775 4.958 4.958 0 002.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 00-8.384 4.482C7.69 8.095 4.067 6.13 1.64 3.162a4.822 4.822 0 00-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 01-2.228-.616v.06a4.923 4.923 0 003.946 4.827 4.996 4.996 0 01-2.212.085 4.936 4.936 0 004.604 3.417 9.867 9.867 0 01-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 007.557 2.209c9.053 0 13.998-7.496 13.998-13.985 0-.21 0-.42-.015-.63A9.935 9.935 0 0024 4.59z"/>
                    </svg>
                </a>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
