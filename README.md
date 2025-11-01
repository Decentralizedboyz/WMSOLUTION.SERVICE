<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <meta name="description" content="WM Solution Service - Sistema completo de gerenciamento de armazéns e logística">
    <meta name="keywords" content="WMS, warehouse, logistics, gestão, armazém, logística">
    <meta name="author" content="WM Solution Service">
    
    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://wmsolution.service/">
    <meta property="og:title" content="WM Solution Service - Gestão Inteligente de Armazéns">
    <meta property="og:description" content="Sistema completo de gerenciamento de armazéns com tecnologia de ponta">
    <meta property="og:image" content="assets/images/og-image.jpg">

    <!-- Twitter -->
    <meta property="twitter:card" content="summary_large_image">
    <meta property="twitter:url" content="https://wmsolution.service/">
    <meta property="twitter:title" content="WM Solution Service">
    <meta property="twitter:description" content="Sistema completo de gerenciamento de armazéns">
    
    <title>WM Solution Service - Sistema de Gestão de Armazéns</title>
    
    <!-- Favicon -->
    <link rel="icon" type="image/x-icon" href="assets/favicon.ico">
    <link rel="apple-touch-icon" sizes="180x180" href="assets/apple-touch-icon.png">
    
    <!-- CSS -->
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/responsive.css">
    
    <!-- Preload fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Loading Screen -->
    <div id="loader" class="loader-wrapper">
        <div class="loader">
            <div class="loader-inner"></div>
        </div>
    </div>

    <!-- Navigation -->
    <nav class="navbar" id="navbar">
        <div class="container">
            <div class="navbar-brand">
                <a href="#home" class="logo">
                    <svg width="40" height="40" viewBox="0 0 40 40" fill="none">
                        <rect width="40" height="40" rx="8" fill="#4F46E5"/>
                        <path d="M10 20L15 25L30 10" stroke="white" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/>
                    </svg>
                    <span>WM Solution</span>
                </a>
            </div>
            
            <button class="mobile-menu-toggle" id="mobileMenuToggle" aria-label="Toggle menu">
                <span></span>
                <span></span>
                <span></span>
            </button>
            
            <div class="navbar-menu" id="navbarMenu">
                <ul class="navbar-nav">
                    <li><a href="#home" class="nav-link">Início</a></li>
                    <li><a href="#features" class="nav-link">Funcionalidades</a></li>
                    <li><a href="#services" class="nav-link">Serviços</a></li>
                    <li><a href="#about" class="nav-link">Sobre</a></li>
                    <li><a href="#pricing" class="nav-link">Planos</a></li>
                    <li><a href="#contact" class="nav-link">Contato</a></li>
                </ul>
                <div class="navbar-actions">
                    <button class="btn btn-outline" id="loginBtn">Login</button>
                    <button class="btn btn-primary" id="demoBtn">Solicitar Demo</button>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <div class="hero-content">
                <div class="hero-text">
                    <h1 class="hero-title animate-fade-in">
                        Sistema de Gestão de Armazéns
                        <span class="text-gradient">Inteligente e Eficiente</span>
                    </h1>
                    <p class="hero-description animate-fade-in-delay">
                        Otimize suas operações logísticas com nossa solução completa de WMS. 
                        Controle total do estoque, rastreabilidade em tempo real e integração com seus sistemas.
                    </p>
                    <div class="hero-buttons animate-fade-in-delay-2">
                        <button class="btn btn-primary btn-lg" id="startBtn">
                            Começar Agora
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                                <path d="M7 10H13M13 10L10 7M13 10L10 13" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                        </button>
                        <button class="btn btn-outline btn-lg" id="watchDemoBtn">
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                                <circle cx="10" cy="10" r="9" stroke="currentColor" stroke-width="2"/>
                                <path d="M8 6.5V13.5L14 10L8 6.5Z" fill="currentColor"/>
                            </svg>
                            Ver Demonstração
                        </button>
                    </div>
                    
                    <div class="hero-stats">
                        <div class="stat">
                            <strong>500+</strong>
                            <span>Clientes Ativos</span>
                        </div>
                        <div class="stat">
                            <strong>99.9%</strong>
                            <span>Uptime</span>
                        </div>
                        <div class="stat">
                            <strong>24/7</strong>
                            <span>Suporte</span>
                        </div>
                    </div>
                </div>
                
                <div class="hero-image">
                    <img src="assets/images/dashboard.png" alt="WMS Dashboard" loading="lazy">
                    <div class="floating-card card-1">
                        <div class="card-icon">📦</div>
                        <div class="card-text">
                            <strong>+45%</strong>
                            <span>Produtividade</span>
                        </div>
                    </div>
                    <div class="floating-card card-2">
                        <div class="card-icon">📊</div>
                        <div class="card-text">
                            <strong>-30%</strong>
                            <span>Custos Operacionais</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="features">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Funcionalidades Poderosas</h2>
                <p class="section-description">
                    Tudo que você precisa para gerenciar seu armazém com excelência
                </p>
            </div>
            
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">
                        <svg width="48" height="48" viewBox="0 0 48 48" fill="none">
                            <rect width="48" height="48" rx="12" fill="#EEF2FF"/>
                            <path d="M16 24L21 29L32 18" stroke="#4F46E5" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                    </div>
                    <h3>Controle de Estoque</h3>
                    <p>Gestão completa de inventário com rastreabilidade total e alertas automáticos de reposição.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <svg width="48" height="48" viewBox="0 0 48 48" fill="none">
                            <rect width="48" height="48" rx="12" fill="#FEF3C7"/>
                            <path d="M24 16V32M16 24H32" stroke="#F59E0B" stroke-width="3" stroke-linecap="round"/>
                        </svg>
                    </div>
                    <h3>Picking Otimizado</h3>
                    <p>Rotas inteligentes de separação que reduzem tempo e aumentam a produtividade.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <svg width="48" height="48" viewBox="0 0 48 48" fill="none">
                            <rect width="48" height="48" rx="12" fill="#DCFCE7"/>
                            <circle cx="24" cy="24" r="8" stroke="#22C55E" stroke-width="3"/>
                        </svg>
                    </div>
                    <h3>Rastreamento RFID</h3>
                    <p>Tecnologia RFID para rastreamento em tempo real de produtos e equipamentos.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <svg width="48" height="48" viewBox="0 0 48 48" fill="none">
                            <rect width="48" height="48" rx="12" fill="#FEE2E2"/>
                            <path d="M24 16L30 22L24 28L18 22L24 16Z" stroke="#EF4444" stroke-width="3" stroke-linejoin="round"/>
                        </svg>
                    </div>
                    <h3>Integração ERP</h3>
                    <p>Conecte-se facilmente com SAP, Oracle, TOTVS e outros sistemas empresariais.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <svg width="48" height="48" viewBox="0 0 48 48" fill="none">
                            <rect width="48" height="48" rx="12" fill="#E0E7FF"/>
                            <rect x="16" y="20" width="16" height="8" stroke="#6366F1" stroke-width="3"/>
                        </svg>
                    </div>
                    <h3>Dashboard Analytics</h3>
                    <p>Painéis interativos com KPIs em tempo real para tomada de decisão estratégica.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <svg width="48" height="48" viewBox="0 0 48 48" fill="none">
                            <rect width="48" height="48" rx="12" fill="#F3E8FF"/>
                            <path d="M24 16V32" stroke="#9333EA" stroke-width="3" stroke-linecap="round"/>
                            <path d="M16 24H32" stroke="#9333EA" stroke-width="3" stroke-linecap="round"/>
                        </svg>
                    </div>
                    <h3>Multi-Armazém</h3>
                    <p>Gerencie múltiplos armazéns e centros de distribuição em uma única plataforma.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Nossos Serviços</h2>
                <p class="section-description">
                    Soluções completas para transformar sua operação logística
                </p>
            </div>
            
            <div class="services-tabs">
                <div class="tabs-nav">
                    <button class="tab-btn active" data-tab="implementation">Implementação</button>
                    <button class="tab-btn" data-tab="integration">Integração</button>
                    <button class="tab-btn" data-tab="training">Treinamento</button>
                    <button class="tab-btn" data-tab="support">Suporte</button>
                </div>
                
                <div class="tabs-content">
                    <div class="tab-pane active" id="implementation">
                        <div class="service-content">
                            <div class="service-text">
                                <h3>Implementação Completa do WMS</h3>
                                <p>Nossa equipe especializada cuida de todo o processo de implementação, desde o mapeamento de processos até o go-live.</p>
                                <ul class="service-list">
                                    <li>Análise e mapeamento de processos</li>
                                    <li>Configuração personalizada do sistema</li>
                                    <li>Migração segura de dados</li>
                                    <li>Testes e validação</li>
                                    <li>Acompanhamento pós-implantação</li>
                                </ul>
                                <button class="btn btn-primary">Saiba Mais</button>
                            </div>
                            <div class="service-image">
                                <img src="assets/images/implementation.svg" alt="Implementação" loading="lazy">
                            </div>
                        </div>
                    </div>
                    
                    <div class="tab-pane" id="integration">
                        <div class="service-content">
                            <div class="service-text">
                                <h3>Integração com Sistemas</h3>
                                <p>Conectamos o WMS com todos os seus sistemas empresariais para criar um ecossistema integrado e eficiente.</p>
                                <ul class="service-list">
                                    <li>Integração com ERPs (SAP, Oracle, TOTVS)</li>
                                    <li>Conexão com sistemas de transporte</li>
                                    <li>APIs RESTful documentadas</li>
                                    <li>Webhooks para eventos em tempo real</li>
                                    <li>EDI para troca de documentos</li>
                                </ul>
                                <button class="btn btn-primary">Saiba Mais</button>
                            </div>
                            <div class="service-image">
                                <img src="assets/images/integration.svg" alt="Integração" loading="lazy">
                            </div>
                        </div>
                    </div>
                    
                    <div class="tab-pane" id="training">
                        <div class="service-content">
                            <div class="service-text">
                                <h3>Programa de Treinamento</h3>
                                <p>Capacitamos sua equipe para extrair o máximo potencial do sistema com treinamentos personalizados.</p>
                                <ul class="service-list">
                                    <li>Treinamento presencial e online</li>
                                    <li>Material didático exclusivo</li>
                                    <li>Certificação de usuários</li>
                                    <li>Workshops de boas práticas</li>
                                    <li>Reciclagem periódica</li>
                                </ul>
                                <button class="btn btn-primary">Saiba Mais</button>
                            </div>
                            <div class="service-image">
                                <img src="assets/images/training.svg" alt="Treinamento" loading="lazy">
                            </div>
                        </div>
                    </div>
                    
                    <div class="tab-pane" id="support">
                        <div class="service-content">
                            <div class="service-text">
                                <h3>Suporte Especializado 24/7</h3>
                                <p>Nossa equipe de suporte está sempre disponível para garantir a continuidade de suas operações.</p>
                                <ul class="service-list">
                                    <li>Atendimento 24 horas, 7 dias por semana</li>
                                    <li>SLA garantido por contrato</li>
                                    <li>Suporte remoto e presencial</li>
                                    <li>Base de conhecimento online</li>
                                    <li>Atualizações automáticas do sistema</li>
                                </ul>
                                <button class="btn btn-primary">Saiba Mais</button>
                            </div>
                            <div class="service-image">
                                <img src="assets/images/support.svg" alt="Suporte" loading="lazy">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing" class="pricing">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Planos e Preços</h2>
                <p class="section-description">
                    Escolha o plano ideal para o tamanho da sua operação
                </p>
            </div>
            
            <div class="pricing-grid">
                <div class="pricing-card">
                    <div class="pricing-header">
                        <h3>Starter</h3>
                        <div class="pricing-price">
                            <span class="currency">R$</span>
                            <span class="amount">2.500</span>
                            <span class="period">/mês</span>
                        </div>
                        <p class="pricing-description">Ideal para pequenas operações</p>
                    </div>
                    <ul class="pricing-features">
                        <li>
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                                <path d="M7 10L9 12L13 8" stroke="#22C55E" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                            Até 5 usuários
                        </li>
                        <li>
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                                <path d="M7 10L9 12L13 8" stroke="#22C55E" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                            1 armazém
                        </li>
                        <li>
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                                <path d="M7 10L9 12L13 8" stroke="#22C55E" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                            Módulos básicos
                        </li>
                        <li>
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                                <path d="M7 10L9 12L13 8" stroke="#22C55E" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                            Suporte em horário comercial
                        </li>
                        <li>
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                                <path d="M7 10L9 12L13 8" stroke="#22C55E" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                            Treinamento online
                        </li>
                    </ul>
                    <button class="btn btn-outline btn-block">Escolher Plano</button>
                </div>
                
                <div class="pricing-card featured">
                    <div class="pricing-badge">Mais Popular</div>
                    <div class="pricing-header">
                        <h3>Professional</h3>
                        <div class="pricing-price">
                            <span class="currency">R$</span>
                            <span class="amount">5.900</span>
                            <span class="period">/mês</span>
                        </div>
                        <p class="pricing-description">Para operações em crescimento</p>
                    </div>
                    <ul class="pricing-features">
                        <li>
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                                <path d="M7 10L9 12L13 8" stroke="#22C55E" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                            Até 20 usuários
                        </li>
                        <li>
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                                <path d="M7 10L9 12L13 8" stroke="#22C55E" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                            Até 3 armazéns
                        </li>
                        <li>
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                                <path d="M7 10L9 12L13 8" stroke="#22C55E" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                            Todos os módulos
                        </li>
                        <li>
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                                <path d="M7 10L9 12L13 8" stroke="#22C55E" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                            Suporte 24/7
                        </li>
                        <li>
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                                <path d="M7 10L9 12L13 8" stroke="#22C55E" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                            Integração com ERP
                        </li>
                        <li>
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                                <path d="M7 10L9 12L13 8" stroke="#22C55E" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                            Dashboard avançado
                        </li>
                    </ul>
                    <button class="btn btn-primary btn-block">Escolher Plano</button>
                </div>
                
                <div class="pricing-card">
                    <div class="pricing-header">
                        <h3>Enterprise</h3>
                        <div class="pricing-price">
                            <span class="custom">Personalizado</span>
                        </div>
                        <p class="pricing-description">Soluções sob medida</p>
                    </div>
                    <ul class="pricing-features">
                        <li>
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                                <path d="M7 10L9 12L13 8" stroke="#22C55E" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                            Usuários ilimitados
                        </li>
                        <li>
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                                <path d="M7 10L9 12L13 8" stroke="#22C55E" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                            Armazéns ilimitados
                        </li>
                        <li>
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                                <path d="M7 10L9 12L13 8" stroke="#22C55E" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                            Customização completa
                        </li>
                        <li>
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                                <path d="M7 10L9 12L13 8" stroke="#22C55E" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                            SLA prioritário
                        </li>
                        <li>
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                                <path d="M7 10L9 12L13 8" stroke="#22C55E" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                            Gerente de conta dedicado
                        </li>
                    </ul>
                    <button class="btn btn-outline btn-block">Falar com Vendas</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Entre em Contato</h2>
                <p class="section-description">
                    Fale conosco e descubra como podemos transformar sua operação
                </p>
            </div>
            
            <div class="contact-content">
                <div class="contact-info">
                    <h3>Vamos conversar sobre seu projeto</h3>
                    <p>Nossa equipe está pronta para entender suas necessidades e apresentar a melhor solução.</p>
                    
                    <div class="contact-items">
                        <div class="contact-item">
                            <div class="contact-icon">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
                                    <path d="M3 8L12 13L21 8M5 19H19C20.1 19 21 18.1 21 17V7C21 5.9 20.1 5 19 5H5C3.9 5 3 5.9 3 7V17C3 18.1 3.9 19 5 19Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                </svg>
                            </div>
                            <div>
                                <strong>Email</strong>
                                <p>contato@wmsolution.service</p>
                            </div>
                        </div>
                        
                        <div class="contact-item">
                            <div class="contact-icon">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
                                    <path d="M3 5.5C3 14.09 9.91 21 18.5 21C19.33 21 20 20.33 20 19.5V16.4C20 15.84 19.56 15.39 19 15.35L15.21 15.04C14.67 14.99 14.16 15.26 13.9 15.72L12.78 17.62C10.38 16.41 7.59 13.62 6.38 11.22L8.28 10.1C8.74 9.84 9.01 9.33 8.96 8.79L8.65 5C8.61 4.44 8.16 4 7.6 4H4.5C3.67 4 3 4.67 3 5.5Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                </svg>
                            </div>
                            <div>
                                <strong>Telefone</strong>
                                <p>0800 123 4567</p>
                            </div>
                        </div>
                        
                        <div class="contact-item">
                            <div class="contact-icon">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
                                    <path d="M17 8C17 10.76 14.76 13 12 13C9.24 13 7 10.76 7 8C7 5.24 9.24 3 12 3C14.76 3 17 5.24 17 8ZM12 11C13.65 11 15 9.65 15 8C15 6.35 13.65 5 12 5C10.35 5 9 6.35 9 8C9 9.65 10.35 11 12 11Z" stroke="currentColor" stroke-width="2"/>
                                    <path d="M12 22C12 22 3 16 3 8C3 3.58 6.58 0 11 0C15.42 0 19 3.58 19 8C19 16 12 22 12 22Z" stroke="currentColor" stroke-width="2"/>
                                </svg>
                            </div>
                            <div>
                                <strong>Endereço</strong>
                                <p>São Paulo, SP - Brasil</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <form class="contact-form" id="contactForm">
                    <div class="form-row">
                        <div class="form-group">
                            <label for="name">Nome Completo</label>
                            <input type="text" id="name" name="name" required placeholder="Seu nome">
                        </div>
                        <div class="form-group">
                            <label for="email">Email</label>
                            <input type="email" id="email" name="email" required placeholder="seu@email.com">
                        </div>
                    </div>
                    
                    <div class="form-row">
                        <div class="form-group">
                            <label for="phone">Telefone</label>
                            <input type="tel" id="phone" name="phone" placeholder="(11) 99999-9999">
                        </div>
                        <div class="form-group">
                            <label for="company">Empresa</label>
                            <input type="text" id="company" name="company" placeholder="Nome da empresa">
                        </div>
                    </div>
                    
                    <div class="form-group">
                        <label for="subject">Assunto</label>
                        <select id="subject" name="subject" required>
                            <option value="">Selecione um assunto</option>
                            <option value="demo">Solicitar demonstração</option>
                            <option value="pricing">Informações sobre preços</option>
                            <option value="support">Suporte técnico</option>
                            <option value="partnership">Parceria</option>
                            <option value="other">Outro</option>
                        </select>
                    </div>
                    
                    <div class="form-group">
                        <label for="message">Mensagem</label>
                        <textarea id="message" name="message" rows="4" required placeholder="Como podemos ajudar?"></textarea>
                    </div>
                    
                    <button type="submit" class="btn btn-primary btn-lg btn-block">
                        Enviar Mensagem
                        <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                            <path d="M2 10L8 4L6 10L14 10L8 16L10 10L2 10Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-top">
                <div class="footer-brand">
                    <a href="#home" class="footer-logo">
                        <svg width="40" height="40" viewBox="0 0 40 40" fill="none">
                            <rect width="40" height="40" rx="8" fill="#4F46E5"/>
                            <path d="M10 20L15 25L30 10" stroke="white" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                        <span>WM Solution</span>
                    </a>
                    <p>Sistema inteligente de gestão de armazéns para empresas modernas.</p>
                    <div class="footer-social">
                        <a href="#" aria-label="LinkedIn">
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="currentColor">
                                <path d="M16 3C17.1 3 18 3.9 18 5V15C18 16.1 17.1 17 16 17H4C2.9 17 2 16.1 2 15V5C2 3.9 2.9 3 4 3H16ZM7.5 14V8.5H5.5V14H7.5ZM6.5 7.5C7.2 7.5 7.75 6.95 7.75 6.25C7.75 5.55 7.2 5 6.5 5C5.8 5 5.25 5.55 5.25 6.25C5.25 6.95 5.8 7.5 6.5 7.5ZM14.5 14V10.8C14.5 9.1 13.9 8 12.5 8C11.8 8 11.3 8.4 11 8.9V8.5H9V14H11V11C11 10.3 11.3 9.8 12 9.8C12.7 9.8 13 10.3 13 11V14H14.5Z"/>
                            </svg>
                        </a>
                        <a href="#" aria-label="Twitter">
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="currentColor">
                                <path d="M18.25 4.65C17.6 4.95 16.9 5.15 16.15 5.25C16.9 4.8 17.5 4.1 17.75 3.25C17.05 3.65 16.25 3.95 15.45 4.1C14.75 3.4 13.8 3 12.75 3C10.75 3 9.15 4.6 9.15 6.6C9.15 6.9 9.2 7.15 9.25 7.45C6.25 7.3 3.6 5.85 1.85 3.65C1.55 4.2 1.35 4.8 1.35 5.5C1.35 6.75 2 7.8 3 8.4C2.4 8.4 1.85 8.2 1.35 7.95V8C1.35 9.75 2.6 11.2 4.25 11.55C3.95 11.65 3.6 11.7 3.3 11.7C3.05 11.7 2.85 11.65 2.6 11.6C3.05 13.05 4.4 14.15 6 14.2C4.75 15.15 3.2 15.75 1.5 15.75C1.2 15.75 0.9 15.75 0.65 15.7C2.3 16.7 4.2 17.25 6.3 17.25C12.75 17.25 16.4 11.75 16.4 7.05V6.6C17.1 6.05 17.75 5.4 18.25 4.65Z"/>
                            </svg>
                        </a>
                        <a href="#" aria-label="Instagram">
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="currentColor">
                                <path d="M10 2C12.2 2 12.5 2 13.4 2.1C15.7 2.2 16.9 3.4 17 5.7C17.1 6.6 17.1 6.9 17.1 9.1V10.9C17.1 13.1 17.1 13.4 17 14.3C16.9 16.6 15.7 17.8 13.4 17.9C12.5 18 12.2 18 10 18C7.8 18 7.5 18 6.6 17.9C4.3 17.8 3.1 16.6 3 14.3C2.9 13.4 2.9 13.1 2.9 10.9V9.1C2.9 6.9 2.9 6.6 3 5.7C3.1 3.4 4.3 2.2 6.6 2.1C7.5 2 7.8 2 10 2ZM10 0.5C7.7 0.5 7.4 0.5 6.5 0.6C3.5 0.7 1.5 2.7 1.4 5.7C1.3 6.6 1.3 6.9 1.3 9.2V10.8C1.3 13.1 1.3 13.4 1.4 14.3C1.5 17.3 3.5 19.3 6.5 19.4C7.4 19.5 7.7 19.5 10 19.5C12.3 19.5 12.6 19.5 13.5 19.4C16.5 19.3 18.5 17.3 18.6 14.3C18.7 13.4 18.7 13.1 18.7 10.8V9.2C18.7 6.9 18.7 6.6 18.6 5.7C18.5 2.7 16.5 0.7 13.5 0.6C12.6 0.5 12.3 0.5 10 0.5ZM10 5.4C7.5 5.4 5.4 7.5 5.4 10C5.4 12.5 7.5 14.6 10 14.6C12.5 14.6 14.6 12.5 14.6 10C14.6 7.5 12.5 5.4 10 5.4ZM10 13C8.3 13 7 11.7 7 10C7 8.3 8.3 7 10 7C11.7 7 13 8.3 13 10C13 11.7 11.7 13 10 13ZM14.8 4.2C14.2 4.2 13.8 4.6 13.8 5.2C13.8 5.8 14.2 6.2 14.8 6.2C15.4 6.2 15.8 5.8 15.8 5.2C15.8 4.6 15.4 4.2 14.8 4.2Z"/>
                            </svg>
                        </a>
                    </div>
                </div>
                
                <div class="footer-links">
                    <div class="footer-column">
                        <h4>Produto</h4>
                        <ul>
                            <li><a href="#features">Funcionalidades</a></li>
                            <li><a href="#pricing">Preços</a></li>
                            <li><a href="#">Integrações</a></li>
                            <li><a href="#">Roadmap</a></li>
                        </ul>
                    </div>
                    
                    <div class="footer-column">
                        <h4>Empresa</h4>
                        <ul>
                            <li><a href="#about">Sobre nós</a></li>
                            <li><a href="#">Carreiras</a></li>
                            <li><a href="#">Parceiros</a></li>
                            <li><a href="#">Blog</a></li>
                        </ul>
                    </div>
                    
                    <div class="footer-column">
                        <h4>Recursos</h4>
                        <ul>
                            <li><a href="#">Documentação</a></li>
                            <li><a href="#">API</a></li>
                            <li><a href="#">Guias</a></li>
                            <li><a href="#">Webinars</a></li>
                        </ul>
                    </div>
                    
                    <div class="footer-column">
                        <h4>Suporte</h4>
                        <ul>
                            <li><a href="#">Central de Ajuda</a></li>
                            <li><a href="#contact">Contato</a></li>
                            <li><a href="#">Status do Sistema</a></li>
                            <li><a href="#">Termos de Uso</a></li>
                        </ul>
                    </div>
                </div>
            </div>
            
            <div class="footer-bottom">
                <p>&copy; 2024 WM Solution Service. Todos os direitos reservados.</p>
                <div class="footer-legal">
                    <a href="#">Privacidade</a>
                    <a href="#">Termos</a>
                    <a href="#">Cookies</a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Modal Demo -->
    <div class="modal" id="demoModal">
        <div class="modal-content">
            <div class="modal-header">
                <h3>Solicitar Demonstração</h3>
                <button class="modal-close" id="modalClose">
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
                        <path d="M18 6L6 18M6 6L18 18" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                    </svg>
                </button>
            </div>
            <div class="modal-body">
                <form id="demoForm">
                    <div class="form-group">
                        <label for="demoName">Nome Completo</label>
                        <input type="text" id="demoName" name="name" required>
                    </div>
                    <div class="form-group">
                        <label for="demoEmail">Email Corporativo</label>
                        <input type="email" id="demoEmail" name="email" required>
                    </div>
                    <div class="form-group">
                        <label for="demoCompany">Empresa</label>
                        <input type="text" id="demoCompany" name="company" required>
                    </div>
                    <div class="form-group">
                        <label for="demoPhone">Telefone</label>
                        <input type="tel" id="demoPhone" name="phone" required>
                    </div>
                    <div class="form-group">
                        <label for="demoSize">Tamanho da Operação</label>
                        <select id="demoSize" name="size" required>
                            <option value="">Selecione</option>
                            <option value="small">Pequena (até 1000 SKUs)</option>
                            <option value="medium">Média (1000-5000 SKUs)</option>
                            <option value="large">Grande (5000+ SKUs)</option>
                        </select>
                    </div>
                    <button type="submit" class="btn btn-primary btn-block">Enviar Solicitação</button>
                </form>
            </div>
        </div>
    </div>

    <!-- Back to Top -->
    <button class="back-to-top" id="backToTop" aria-label="Voltar ao topo">
        <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
            <path d="M12 19V5M12 5L5 12M12 5L19 12" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
    </button>

    <!-- Scripts -->
    <script src="js/main.js" defer></script>
</body>
</html>
