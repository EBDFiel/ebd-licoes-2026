<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>QUIZ DA EBD Fiel | Jetro: Conselhos Sábios Aliviam Fardos</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<style>
/* ===== VARIÁVEIS E RESET ===== */
:root {
  --primary: #4361ee;
  --primary-dark: #3a56d4;
  --secondary: #7209b7;
  --accent: #f72585;
  --success: #4cc9f0;
  --warning: #f8961e;
  --danger: #f94144;
  --light: #f8f9fa;
  --dark: #212529;
  --text: #343a40;
  --gray: #6c757d;
  --shadow: 0 10px 30px rgba(0,0,0,0.1);
  --shadow-lg: 0 15px 50px rgba(0,0,0,0.15);
  --gradient: linear-gradient(135deg, #4361ee 0%, #7209b7 100%);
  --gradient-light: linear-gradient(135deg, #4cc9f0 0%, #4361ee 100%);
  --instagram: #E1306C;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}

html {
  scroll-behavior: smooth;
}

body {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: var(--text);
  min-height: 100vh;
  padding: 15px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  line-height: 1.6;
}

/* ===== CONTAINER PRINCIPAL ===== */
.container {
  max-width: 100%;
  width: 100%;
  background: white;
  border-radius: 20px;
  box-shadow: var(--shadow-lg);
  overflow: hidden;
  margin: 10px 0;
  position: relative;
}

/* ===== HEADER MODERNO ===== */
.modern-header {
  background: var(--gradient);
  color: white;
  padding: 25px 20px;
  text-align: center;
  position: relative;
  overflow: hidden;
}

.header-bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  opacity: 0.1;
  background-image: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMDAiIGhlaWdodD0iMTAwIiB2aWV3Qm94PSIwIDAgMTAwIDEwMCI+PHBhdGggZD0iTTIxLDMwIEMyMSwzMCA0MCwzMCA1MCw0MCBDNjAsMzAgNzksMzAgNzksMzAgQzc5LDMwIDg1LDM1IDg1LDQwIEM4NSw0NSA3OSw1MCA3OSw1MCBDNzksNTAgNjAsNTAgNTAsNjAgQzQwLDUwIDIxLDUwIDIxLDUwIEMyMSw1MCAxNSw0NSAxNSw0MCBDMTUsMzUgMjEsMzAgMjEsMzAgWiIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjIiLz48L3N2Zz4=');
  background-size: 150px;
}

.header-content {
  position: relative;
  z-index: 2;
  max-width: 100%;
  margin: 0 auto;
}

.logo-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 15px;
  margin-bottom: 20px;
}

.logo {
  width: 120px;
  height: 120px;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 0 5px 15px rgba(0,0,0,0.2);
  overflow: hidden;
  border-radius: 15px;
  background: white;
  padding: 10px;
}

.logo-img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

.logo-text {
  text-align: center;
}

.logo-text h1 {
  font-size: 1.8rem;
  font-weight: 700;
  margin: 0;
  line-height: 1.2;
}

.logo-text .subtitle {
  font-size: 1rem;
  opacity: 0.9;
  font-weight: 400;
  margin-top: 5px;
}

.welcome-card {
  background: rgba(255,255,255,0.15);
  backdrop-filter: blur(10px);
  padding: 20px;
  border-radius: 16px;
  margin: 20px 0;
  border: 1px solid rgba(255,255,255,0.2);
  text-align: left;
}

.welcome-card h2 {
  font-size: 1.3rem;
  margin-bottom: 10px;
  display: flex;
  align-items: center;
  gap: 10px;
}

.welcome-card p {
  font-size: 1rem;
  opacity: 0.9;
  line-height: 1.5;
}

.cta-section {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 15px;
  margin-top: 20px;
}

.start-btn {
  padding: 16px 35px;
  border: none;
  border-radius: 50px;
  background: var(--accent);
  color: white;
  font-weight: 600;
  cursor: pointer;
  transition: all 0.3s ease;
  font-size: 1.1rem;
  display: flex;
  align-items: center;
  gap: 10px;
  box-shadow: 0 8px 20px rgba(248, 37, 133, 0.4);
  width: 100%;
  max-width: 280px;
  justify-content: center;
}

.start-btn:hover {
  transform: translateY(-3px) scale(1.03);
  box-shadow: 0 12px 25px rgba(248, 37, 133, 0.5);
  background: #ff2d95;
}

.features {
  display: flex;
  flex-direction: column;
  justify-content: center;
  gap: 12px;
  margin-top: 20px;
  width: 100%;
  max-width: 300px;
}

.feature {
  display: flex;
  align-items: center;
  gap: 10px;
  background: rgba(255,255,255,0.1);
  padding: 12px 15px;
  border-radius: 30px;
  font-size: 0.9rem;
  backdrop-filter: blur(5px);
  justify-content: center;
}

/* ===== SEÇÃO DE CONTEÚDO ===== */
.content-section {
  padding: 30px 20px;
  display: flex;
  flex-direction: column;
  gap: 25px;
}

.about-card, .details-card {
  background: var(--light);
  border-radius: 16px;
  padding: 25px 20px;
  box-shadow: var(--shadow);
}

.card-title {
  font-size: 1.3rem;
  color: var(--primary);
  margin-bottom: 15px;
  display: flex;
  align-items: center;
  gap: 10px;
}

.card-content {
  font-size: 0.95rem;
  color: var(--text);
  line-height: 1.6;
}

.card-content ul {
  list-style: none;
  margin-top: 15px;
}

.card-content li {
  margin-bottom: 12px;
  display: flex;
  align-items: flex-start;
  gap: 10px;
}

.card-content li i {
  color: var(--primary);
  margin-top: 3px;
  flex-shrink: 0;
}

.highlight {
  background: var(--gradient-light);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: 600;
}

/* ===== SEÇÃO DO QUIZ ===== */
.quiz-section {
  display: none;
  padding: 20px 15px;
}

.progress-container {
  padding: 0 15px;
  margin-bottom: 20px;
}

.progress-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 10px;
}

.progress-text {
  font-size: 1rem;
  font-weight: 600;
  color: var(--primary);
}

.progress-bar {
  height: 8px;
  background: #e9ecef;
  border-radius: 10px;
  overflow: hidden;
  position: relative;
}

.progress {
  height: 100%;
  background: var(--gradient);
  border-radius: 10px;
  transition: width 0.5s ease;
  position: relative;
}

.progress::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  background-image: linear-gradient(
    -45deg,
    rgba(255, 255, 255, 0.2) 25%,
    transparent 25%,
    transparent 50%,
    rgba(255, 255, 255, 0.2) 50%,
    rgba(255, 255, 255, 0.2) 75%,
    transparent 75%,
    transparent
  );
  background-size: 20px 20px;
  animation: move 1s linear infinite;
}

@keyframes move {
  0% { background-position: 0 0; }
  100% { background-position: 20px 0; }
}

.question {
  margin-bottom: 25px;
  padding: 20px;
  border-radius: 16px;
  background: white;
  box-shadow: var(--shadow);
  border-left: 5px solid var(--primary);
}

.question-header {
  display: flex;
  flex-direction: column;
  gap: 15px;
  margin-bottom: 20px;
}

.question-difficulty {
  padding: 8px 15px;
  border-radius: 20px;
  font-size: 0.85rem;
  font-weight: bold;
  color: white;
  align-self: flex-start;
}

.difficulty-easy { background: var(--success); }
.difficulty-medium { background: var(--warning); }
.difficulty-hard { background: var(--danger); }

.question-text {
  font-size: 1.2rem;
  font-weight: 600;
  color: var(--primary);
  line-height: 1.4;
}

.options {
  display: grid;
  grid-template-columns: 1fr;
  gap: 12px;
}

.option {
  padding: 16px 15px;
  background: var(--light);
  border-radius: 12px;
  cursor: pointer;
  transition: all 0.3s ease;
  display: flex;
  align-items: center;
  border: 2px solid transparent;
  position: relative;
}

.option:hover {
  transform: translateY(-3px);
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  border-color: var(--primary);
}

.option.selected.correct {
  background: var(--success);
  color: white;
  border-color: var(--success);
  transform: translateY(-2px);
}

.option.selected.incorrect {
  background: var(--danger);
  color: white;
  border-color: var(--danger);
  transform: translateY(-2px);
}

.option.correct-answer {
  background: var(--success);
  color: white;
  border-color: var(--success);
  animation: pulse 0.6s ease;
}

.option-letter {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 32px;
  height: 32px;
  background: rgba(255,255,255,0.3);
  border-radius: 50%;
  margin-right: 12px;
  font-weight: bold;
  flex-shrink: 0;
}

.option.selected .option-letter,
.option.correct-answer .option-letter {
  background: rgba(255,255,255,0.2);
}

.feedback-icon {
  margin-left: auto;
  font-size: 1.1rem;
  opacity: 0;
  transition: opacity 0.3s ease;
  flex-shrink: 0;
}

.option.selected.correct .feedback-icon,
.option.correct-answer .feedback-icon {
  opacity: 1;
}

.option.selected.incorrect .feedback-icon {
  opacity: 1;
}

.option.locked {
  cursor: not-allowed;
}

.option.locked:hover {
  transform: none;
  box-shadow: none;
  border-color: transparent;
}

/* ===== NAVEGAÇÃO ===== */
.navigation {
  display: flex;
  justify-content: space-between;
  margin-top: 25px;
  gap: 10px;
}

button {
  padding: 14px 20px;
  border: none;
  border-radius: 50px;
  background: var(--primary);
  color: white;
  font-weight: 600;
  cursor: pointer;
  transition: all 0.3s ease;
  display: flex;
  align-items: center;
  gap: 8px;
  font-size: 0.95rem;
  flex: 1;
  justify-content: center;
}

button:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}

button:disabled {
  background: #bdc3c7;
  cursor: not-allowed;
  transform: none;
  box-shadow: none;
}

.btn-next {
  background: var(--secondary);
}

/* ===== RESULTADOS ===== */
.results {
  text-align: center;
  padding: 30px 20px;
  display: none;
}

.results-header {
  margin-bottom: 25px;
}

.score {
  font-size: 3.5rem;
  font-weight: 700;
  background: var(--gradient);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  margin: 15px 0;
}

.performance {
  display: flex;
  flex-direction: column;
  justify-content: center;
  gap: 15px;
  margin: 30px 0;
}

.performance-item {
  text-align: center;
  padding: 20px;
  border-radius: 16px;
  background: var(--light);
  box-shadow: var(--shadow);
}

.performance-value {
  font-size: 2rem;
  font-weight: 700;
  margin: 10px 0;
}

.performance-easy { color: var(--success); }
.performance-medium { color: var(--warning); }
.performance-hard { color: var(--danger); }

.message {
  font-size: 1.1rem;
  margin: 25px 0;
  padding: 20px;
  border-radius: 16px;
  background: var(--light);
  box-shadow: var(--shadow);
  line-height: 1.5;
}

/* ===== INFORMAÇÕES DA IGREJA E INSTAGRAM ===== */
.church-info {
  text-align: center;
  padding: 20px;
  background: var(--light);
  border-top: 1px solid #dee2e6;
}

.church-name {
  font-size: 1.2rem;
  font-weight: 700;
  color: var(--primary);
  margin-bottom: 5px;
}

.church-location {
  color: var(--text);
  opacity: 0.8;
  font-size: 0.95rem;
  margin-bottom: 15px;
}

.instagram-section {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 10px;
  margin-top: 10px;
}

.instagram-text {
  font-size: 0.9rem;
  color: var(--text);
}

.instagram-link {
  display: flex;
  align-items: center;
  gap: 8px;
  padding: 10px 20px;
  background: var(--instagram);
  color: white;
  border-radius: 50px;
  text-decoration: none;
  font-weight: 600;
  transition: all 0.3s ease;
  box-shadow: 0 4px 15px rgba(225, 48, 108, 0.3);
}

.instagram-link:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(225, 48, 108, 0.4);
  background: #C13584;
}

.instagram-icon {
  font-size: 1.2rem;
}

/* ===== ANIMAÇÕES ===== */
@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}

@keyframes pulse {
  0% { transform: scale(1); }
  50% { transform: scale(1.02); }
  100% { transform: scale(1); }
}

@keyframes bounce {
  0%, 20%, 50%, 80%, 100% {transform: translateY(0);}
  40% {transform: translateY(-10px);}
  60% {transform: translateY(-5px);}
}

.fade-in {
  animation: fadeIn 0.5s ease forwards;
}

.bounce {
  animation: bounce 0.6s;
}

/* ===== MELHORIAS PARA SMARTPHONE ===== */
@media (max-width: 480px) {
  body {
    padding: 10px;
  }
  
  .container {
    border-radius: 16px;
  }
  
  .modern-header {
    padding: 20px 15px;
  }
  
  .logo-text h1 {
    font-size: 1.6rem;
  }
  
  .logo {
    width: 100px;
    height: 100px;
  }
  
  .welcome-card {
    padding: 15px;
  }
  
  .content-section {
    padding: 25px 15px;
  }
  
  .about-card, .details-card {
    padding: 20px 15px;
  }
  
  .quiz-section {
    padding: 15px 10px;
  }
  
  .question {
    padding: 15px;
  }
  
  .question-text {
    font-size: 1.1rem;
  }
  
  .option {
    padding: 14px 12px;
  }
  
  .navigation {
    flex-direction: column;
  }
  
  button {
    width: 100%;
  }
  
  .results {
    padding: 25px 15px;
  }
  
  .score {
    font-size: 3rem;
  }
}

/* ===== MELHORIAS PARA TABLETS ===== */
@media (min-width: 768px) {
  .container {
    max-width: 700px;
  }
  
  .logo-container {
    flex-direction: row;
    text-align: left;
  }
  
  .logo-text {
    text-align: left;
  }
  
  .features {
    flex-direction: row;
    max-width: 100%;
  }
  
  .performance {
    flex-direction: row;
  }
  
  .navigation {
    flex-direction: row;
  }
  
  .instagram-section {
    flex-direction: row;
    justify-content: center;
  }
}

/* ===== MELHORIAS PARA DESKTOP ===== */
@media (min-width: 992px) {
  .container {
    max-width: 900px;
  }
  
  .content-section {
    grid-template-columns: 1fr 1fr;
    display: grid;
  }
}
</style>
</head>
<body>
<div class="container fade-in">
  <!-- HEADER MODERNO -->
  <header class="modern-header">
    <div class="header-bg"></div>
    <div class="header-content">
      <div class="logo-container">
        <div class="logo">
          <img src="https://i.ibb.co/9mLXgx7k/logo.png" alt="Logo EBD Fiel" class="logo-img" id="logo-img">
          <div class="logo-fallback" id="logo-fallback" style="display: none;">
            <i class="fas fa-book-bible"></i>
          </div>
        </div>
        <div class="logo-text">
          <h1>QUIZ DA EBD Fiel</h1>
          <div class="subtitle">Lição 01: Jetro - Conselhos Sábios Aliviam Fardos</div>
        </div>
      </div>

      <div class="welcome-card">
        <h2><i class="fas fa-hands"></i> Bem-vindo ao Quiz da EBD Fiel!</h2>
        <p>Descubra como o conselho sábio de Jetro transformou a liderança de Moisés e aprenda princípios atemporais de gestão, delegação e cuidado pastoral que ainda se aplicam à liderança moderna.</p>
      </div>

      <div class="cta-section">
        <button class="start-btn" id="start-btn">
          <i class="fas fa-play"></i> Iniciar Quiz
        </button>

        <div class="features">
          <div class="feature">
            <i class="fas fa-star" style="color: #4cc9f0;"></i>
            <span>15 Perguntas</span>
          </div>
          <div class="feature">
            <i class="fas fa-check-circle" style="color: #f8961e;"></i>
            <span>Feedback Imediato</span>
          </div>
          <div class="feature">
            <i class="fas fa-graduation-cap" style="color: #f94144;"></i>
            <span>Aprenda com a Bíblia</span>
          </div>
        </div>
      </div>
    </div>
  </header>

  <!-- SEÇÃO DE CONTEÚDO -->
  <section class="content-section">
    <div class="about-card">
      <h2 class="card-title"><i class="fas fa-info-circle"></i> Sobre Esta Lição</h2>
      <div class="card-content">
        <p>Nesta lição, estudaremos a história de Jetro, o sogro de Moisés, que com sabedoria divina percebeu que Moisés estava se esgotando ao tentar julgar sozinho todas as causas do povo de Israel.</p>
        <p>O conselho organizacional de Jetro revolucionou a liderança mosaica, estabelecendo princípios de delegação, hierarquia e administração eficiente que são estudados até hoje em gestão e liderança.</p>
        <p><span class="highlight">Conselhos sábios podem transformar lideranças</span> e trazer alívio a fardos que parecem insuportáveis.</p>
      </div>
    </div>

    <div class="details-card">
      <h2 class="card-title"><i class="fas fa-book-open"></i> O Que Você Vai Aprender</h2>
      <div class="card-content">
        <ul>
          <li><i class="fas fa-check"></i> A relação familiar entre Jetro e Moisés</li>
          <li><i class="fas fa-check"></i> O contexto do encontro e observação de Jetro</li>
          <li><i class="fas fa-check"></i> Os quatro princípios de liderança ensinados</li>
          <li><i class="fas fa-check"></i> A estrutura organizacional proposta</li>
          <li><i class="fas fa-check"></i> A aplicação prática para lideranças atuais</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- SEÇÃO DO QUIZ -->
  <div class="quiz-section" id="quiz-section">
    <div class="progress-container">
      <div class="progress-header">
        <div class="progress-text" id="progress-text">Pergunta 1 de 15</div>
      </div>
      <div class="progress-bar">
        <div class="progress" id="quiz-progress"></div>
      </div>
    </div>

    <div class="quiz-container" id="quiz-container">
      <!-- Perguntas serão inseridas aqui pelo JavaScript -->
    </div>

    <div class="navigation">
      <button id="prev-btn" disabled>
        <i class="fas fa-arrow-left"></i> Anterior
      </button>
      <button id="next-btn" class="btn-next">
        Próxima <i class="fas fa-arrow-right"></i>
      </button>
    </div>
  </div>

  <!-- SEÇÃO DE RESULTADOS -->
  <div class="results" id="results">
    <div class="results-header">
      <h2><i class="fas fa-trophy"></i> Resultado Final</h2>
    </div>
    <div class="score" id="score">0/0</div>

    <div class="performance" id="performance">
      <div class="performance-item">
        <div class="performance-value performance-easy" id="correct-easy">0</div>
        <div>Fáceis</div>
      </div>
      <div class="performance-item">
        <div class="performance-value performance-medium" id="correct-medium">0</div>
        <div>Médias</div>
      </div>
      <div class="performance-item">
        <div class="performance-value performance-hard" id="correct-hard">0</div>
        <div>Difíceis</div>
      </div>
    </div>

    <div class="message" id="message"></div>

    <button id="restart-btn" style="background: var(--success);">
      <i class="fas fa-redo"></i> Fazer Quiz Novamente
    </button>
  </div>

  <!-- Informações da Igreja e Instagram -->
  <div class="church-info">
    <div class="church-name" id="church-name">EBD FIEL</div>
    <div class="church-location" id="church-location">FIEL A PALAVRA</div>

    <div class="instagram-section">
      <div class="instagram-text">Curta nossa página no Instagram:</div>
      <a href="https://www.instagram.com/ebdfiel" target="_blank" class="instagram-link">
        <i class="fab fa-instagram instagram-icon"></i>
        @ebdfiel
      </a>
    </div>
  </div>
</div>

<script>
// =============================================
// CONFIGURAÇÕES PERSONALIZÁVEIS
// =============================================

// 1. CONFIGURAÇÃO DA LOGO
const logoConfig = {
  imageUrl: "https://i.ibb.co/9mLXgx7k/logo.png",
  fallbackText: "EBD"
};

// 2. INFORMAÇÕES DA IGREJA
const churchInfo = {
  name: "EBD FIEL",
  location: "FIEL A PALAVRA"
};

// 3. CONFIGURAÇÕES DO QUIZ
const quizConfig = {
  title: "Lição 01: Jetro - Conselhos Sábios Aliviam Fardos",
  welcomeMessage: "Descubra como o conselho sábio de Jetro transformou a liderança de Moisés e aprenda princípios atemporais de gestão, delegação e cuidado pastoral.",
  theme: "Jetro e os princípios de liderança sábia",
  objective: "Aprender sobre delegação, organização e cuidado pastoral na liderança"
};

// =============================================
// BANCO DE PERGUNTAS - LIÇÃO 01: JETRO
// =============================================

const allQuestions = [
  // PERGUNTAS FÁCEIS (5)
  {
    question: "Qual era a relação familiar entre Jetro e Moisés?",
    options: [
      "Jetro era sogro de Moisés",
      "Jetro era irmão de Moisés", 
      "Jetro era tio de Moisés",
      "Jetro era primo de Moisés"
    ],
    correct: 0,
    explanation: "Jetro era sogro de Moisés, pois sua filha Zípora era esposa de Moisés (Êxodo 3:1).",
    difficulty: "easy"
  },
  {
    question: "Qual era a profissão de Jetro antes de se encontrar com Moisés?",
    options: [
      "Agricultor",
      "Sacerdote de Midiã", 
      "Rei de Egito",
      "Comerciante"
    ],
    correct: 1,
    explanation: "Jetro era sacerdote de Midiã (Êxodo 3:1), demonstrando sua posição de liderança espiritual.",
    difficulty: "easy"
  },
  {
    question: "O que Jetro observou que Moisés fazia desde a manhã até a tarde?",
    options: [
      "Pregava para o povo",
      "Julgava as causas do povo", 
      "Oferecia sacrifícios",
      "Ensina a Lei"
    ],
    correct: 1,
    explanation: "Jetro viu Moisés julgando o povo sozinho, sentado para julgar as causas desde a manhã até à tarde (Êxodo 18:13-14).",
    difficulty: "easy"
  },
  {
    question: "Qual foi a primeira reação de Jetro ao ver Moisés trabalhando sozinho?",
    options: [
      "Aprovação",
      "Preocupação", 
      "Indiferença",
      "Admiração"
    ],
    correct: 1,
    explanation: "Jetro demonstrou preocupação, perguntando: 'Que é isto que fazes ao povo?' (Êxodo 18:14).",
    difficulty: "easy"
  },
  {
    question: "Onde aconteceu o encontro entre Jetro e Moisés descrito em Êxodo 18?",
    options: [
      "No deserto, próximo ao monte de Deus",
      "No Egito", 
      "Em Canaã",
      "Nas margens do Mar Vermelho"
    ],
    correct: 0,
    explanation: "O encontro ocorreu no deserto, onde Moisés estava acampado com o povo de Israel, próximo ao monte de Deus (Êxodo 18:5).",
    difficulty: "easy"
  },
  
  // PERGUNTAS MÉDIAS (5)
  {
    question: "Qual foi o conselho principal que Jetro deu a Moisés sobre liderança?",
    options: [
      "Trabalhar mais horas",
      "Delegar autoridade a outros líderes", 
      "Pedir ajuda a Faraó",
      "Abandonar o povo"
    ],
    correct: 1,
    explanation: "Jetro aconselhou Moisés a escolher homens capazes para ajudá-lo a julgar as causas menores, reservando para si apenas as questões mais difíceis (Êxodo 18:21-22).",
    difficulty: "medium"
  },
  {
    question: "Quais qualidades Jetro disse que os auxiliares de Moisés deveriam ter?",
    options: [
      "Ricos e poderosos",
      "Capazes, tementes a Deus, homens de verdade, que aborreçam a avareza", 
      "Idosos e experientes",
      "Parentes de Moisés"
    ],
    correct: 1,
    explanation: "Jetro listou quatro qualidades essenciais: capacidade, temor a Deus, integridade (homens de verdade) e aversão à ganância (Êxodo 18:21).",
    difficulty: "medium"
  },
  {
    question: "Como Moisés reagiu ao conselho de Jetro?",
    options: [
      "Rejeitou imediatamente",
      "Ouviu e colocou em prática", 
      "Pediu mais tempo para pensar",
      "Consultou outros líderes primeiro"
    ],
    correct: 1,
    explanation: "Moisés aceitou o conselho do sogro e fez tudo quanto este lhe dissera (Êxodo 18:24).",
    difficulty: "medium"
  },
  {
    question: "Qual foi um dos resultados imediatos da implementação do conselho de Jetro?",
    options: [
      "Moisés ficou mais rico",
      "O povo voltou para o Egito", 
      "Moisés pôde se concentrar nas causas mais importantes",
      "Jetro assumiu a liderança"
    ],
    correct: 2,
    explanation: "Com a delegação, as causas menores eram resolvidas por outros, e só as causas graves chegavam a Moisés (Êxodo 18:26).",
    difficulty: "medium"
  },
  {
    question: "Além do conselho administrativo, o que mais Jetro fez durante sua visita?",
    options: [
      "Ofereceu sacrifícios a Deus",
      "Criticou a liderança de Moisés", 
      "Pediu presentes",
      "Tentou levar Moisés de volta a Midiã"
    ],
    correct: 0,
    explanation: "Jetro ofereceu um holocausto e sacrifícios a Deus, e Arão e todos os anciãos de Israel vieram comer pão com ele diante de Deus (Êxodo 18:12).",
    difficulty: "medium"
  },
  
  // PERGUNTAS DIFÍCEIS (5)
  {
    question: "Qual princípio de administração moderna é prefigurado no conselho de Jetro a Moisés?",
    options: [
      "Centralização do poder",
      "Delegação e hierarquização", 
      "Automação de processos",
      "Terceirização de serviços"
    ],
    explanation: "O sistema proposto por Jetro estabelecia níveis de autoridade: líderes de mil, cem, cinquenta e dez, criando uma estrutura organizacional hierárquica.",
    correct: 1,
    difficulty: "hard"
  },
  {
    question: "Segundo estudiosos, qual pode ter sido uma motivação adicional de Jetro ao dar seu conselho?",
    options: [
      "Enfraquecer a liderança de Moisés",
      "Proteger a saúde e bem-estar de seu genro", 
      "Garantir seu próprio poder",
      "Testar a humildade de Moisés"
    ],
    explanation: "Além da eficiência administrativa, Jetro demonstrou preocupação com o esgotamento físico e emocional de Moisés, citando que ele e o povo se cansariam (Êxodo 18:18).",
    correct: 1,
    difficulty: "hard"
  },
  {
    question: "Qual aspecto da personalidade de Jetro é revelado pelo fato de ele ter vindo visitar Moisés trazendo sua família?",
    options: [
      "Preocupação com reunificação familiar e relações pessoais",
      "Interesse em se mudar para o acampamento israelita", 
      "Desejo de controlar a vida familiar de Moisés",
      "Necessidade de proteção para sua família"
    ],
    explanation: "Jetro demonstrou cuidado familiar ao trazer Zípora e os filhos de Moisés para reencontrá-lo, mostrando que valorizava tanto as questões administrativas quanto as familiares.",
    correct: 0,
    difficulty: "hard"
  },
  {
    question: "Como o conselho de Jetro contribuiu para o desenvolvimento da legislação israelita posterior?",
    options: [
      "Criou precedente para tribunais locais e sistema judicial descentralizado",
      "Estabeleceu a monarquia em Israel", 
      "Instituiu o sacerdócio levítico",
      "Determinou o dízimo como obrigatório"
    ],
    explanation: "A estrutura de juízes em diferentes níveis estabelecida por Jetro serviu de base para o desenvolvimento do sistema judicial israelita, com juízes locais resolvendo questões menores.",
    correct: 0,
    difficulty: "hard"
  },
  {
    question: "Qual lição sobre humildade na liderança podemos aprender da atitude de Moisés em relação ao conselho de Jetro?",
    options: [
      "Um verdadeiro líder deve aceitar conselhos mesmo de fora de sua cultura ou religião",
      "Um líder nunca deve aceitar conselhos", 
      "Só parentes podem dar conselhos válidos",
      "Conselhos só são válidos se vierem de profetas"
    ],
    explanation: "Moisés, apesar de ser o líder escolhido por Deus, demonstrou humildade ao aceitar e implementar o conselho de seu sogro midianita, mostrando que sabedoria pode vir de diferentes fontes.",
    correct: 0,
    difficulty: "hard"
  }
];

// =============================================
// VARIÁVEIS GLOBAIS DO QUIZ
// =============================================
let currentQuestionIndex = 0;
let userAnswers = [];
let quizStarted = false;

// =============================================
// INICIALIZAÇÃO DA PÁGINA
// =============================================
document.addEventListener('DOMContentLoaded', function() {
  // Configurar informações da igreja
  document.getElementById('church-name').textContent = churchInfo.name;
  document.getElementById('church-location').textContent = churchInfo.location;
  
  // Verificar se a logo carrega
  const logoImg = document.getElementById('logo-img');
  const logoFallback = document.getElementById('logo-fallback');
  
  logoImg.onerror = function() {
    logoImg.style.display = 'none';
    logoFallback.style.display = 'flex';
    logoFallback.innerHTML = `<i class="fas fa-book-bible"></i>`;
  };
  
  // Configurar botões
  document.getElementById('start-btn').addEventListener('click', startQuiz);
  document.getElementById('prev-btn').addEventListener('click', showPreviousQuestion);
  document.getElementById('next-btn').addEventListener('click', showNextQuestion);
  document.getElementById('restart-btn').addEventListener('click', restartQuiz);
  
  // Inicializar array de respostas
  userAnswers = new Array(allQuestions.length).fill(null);
});

// =============================================
// FUNÇÕES DO QUIZ
// =============================================

function startQuiz() {
  quizStarted = true;
  document.querySelector('.modern-header').style.display = 'none';
  document.querySelector('.content-section').style.display = 'none';
  document.getElementById('quiz-section').style.display = 'block';
  document.getElementById('results').style.display = 'none';
  
  currentQuestionIndex = 0;
  showQuestion(currentQuestionIndex);
}

function showQuestion(index) {
  const question = allQuestions[index];
  const quizContainer = document.getElementById('quiz-container');
  
  // Atualizar barra de progresso
  updateProgressBar();
  
  // Criar HTML da pergunta
  let optionsHTML = '';
  question.options.forEach((option, i) => {
    const letter = String.fromCharCode(65 + i); // A, B, C, D
    const isSelected = userAnswers[index] === i;
    const optionClass = isSelected ? 'selected' : '';
    
    optionsHTML += `
      <div class="option ${optionClass}" data-index="${i}">
        <span class="option-letter">${letter}</span>
        <span class="option-text">${option}</span>
        <span class="feedback-icon">
          ${isSelected ? (i === question.correct ? '<i class="fas fa-check"></i>' : '<i class="fas fa-times"></i>') : ''}
        </span>
      </div>
    `;
  });
  
  quizContainer.innerHTML = `
    <div class="question">
      <div class="question-header">
        <span class="question-difficulty difficulty-${question.difficulty}">
          ${question.difficulty === 'easy' ? 'Fácil' : question.difficulty === 'medium' ? 'Médio' : 'Difícil'}
        </span>
        <div class="question-text">${question.question}</div>
      </div>
      <div class="options">
        ${optionsHTML}
      </div>
    </div>
  `;
  
  // Adicionar event listeners às opções
  document.querySelectorAll('.option').forEach(option => {
    option.addEventListener('click', function() {
      if (quizStarted) {
        selectOption(parseInt(this.getAttribute('data-index')));
      }
    });
  });
  
  // Atualizar estado dos botões de navegação
  updateNavigationButtons();
}

function selectOption(optionIndex) {
  userAnswers[currentQuestionIndex] = optionIndex;
  
  // Atualizar visualização das opções
  const options = document.querySelectorAll('.option');
  const question = allQuestions[currentQuestionIndex];
  
  options.forEach((option, i) => {
    option.classList.remove('selected', 'correct', 'incorrect', 'correct-answer');
    
    if (i === optionIndex) {
      option.classList.add('selected');
      
      if (i === question.correct) {
        option.classList.add('correct');
      } else {
        option.classList.add('incorrect');
      }
    }
    
    // Mostrar resposta correta se o usuário errou
    if (i === question.correct && optionIndex !== question.correct) {
      option.classList.add('correct-answer');
    }
  });
  
  // Atualizar estado dos botões de navegação
  updateNavigationButtons();
}

function showNextQuestion() {
  if (currentQuestionIndex < allQuestions.length - 1) {
    currentQuestionIndex++;
    showQuestion(currentQuestionIndex);
  } else {
    showResults();
  }
}

function showPreviousQuestion() {
  if (currentQuestionIndex > 0) {
    currentQuestionIndex--;
    showQuestion(currentQuestionIndex);
  }
}

function updateProgressBar() {
  const progress = ((currentQuestionIndex + 1) / allQuestions.length) * 100;
  document.getElementById('quiz-progress').style.width = `${progress}%`;
  document.getElementById('progress-text').textContent = `Pergunta ${currentQuestionIndex + 1} de ${allQuestions.length}`;
}

function updateNavigationButtons() {
  document.getElementById('prev-btn').disabled = currentQuestionIndex === 0;
  
  const nextButton = document.getElementById('next-btn');
  if (currentQuestionIndex === allQuestions.length - 1) {
    nextButton.innerHTML = 'Ver Resultados <i class="fas fa-chart-bar"></i>';
  } else {
    nextButton.innerHTML = 'Próxima <i class="fas fa-arrow-right"></i>';
  }
  
  // Habilitar próximo apenas se uma opção foi selecionada
  nextButton.disabled = userAnswers[currentQuestionIndex] === null;
}

function showResults() {
  document.getElementById('quiz-section').style.display = 'none';
  document.getElementById('results').style.display = 'block';
  
  // Calcular pontuação
  let score = 0;
  let correctEasy = 0, correctMedium = 0, correctHard = 0;
  let totalEasy = 0, totalMedium = 0, totalHard = 0;
  
  allQuestions.forEach((question, index) => {
    if (question.difficulty === 'easy') totalEasy++;
    if (question.difficulty === 'medium') totalMedium++;
    if (question.difficulty === 'hard') totalHard++;
    
    if (userAnswers[index] === question.correct) {
      score++;
      
      if (question.difficulty === 'easy') correctEasy++;
      if (question.difficulty === 'medium') correctMedium++;
      if (question.difficulty === 'hard') correctHard++;
    }
  });
  
  // Atualizar resultados
  document.getElementById('score').textContent = `${score}/${allQuestions.length}`;
  document.getElementById('correct-easy').textContent = `${correctEasy}/${totalEasy}`;
  document.getElementById('correct-medium').textContent = `${correctMedium}/${totalMedium}`;
  document.getElementById('correct-hard').textContent = `${correctHard}/${totalHard}`;
  
  // Mensagem personalizada baseada na pontuação
  const messageElement = document.getElementById('message');
  let message = '';
  
  if (score === allQuestions.length) {
    message = '<i class="fas fa-crown"></i> <strong>Excelente!</strong> Você demonstrou um conhecimento excepcional sobre Jetro e princípios de liderança. Sua compreensão da delegação e cuidado pastoral é admirável!';
  } else if (score >= allQuestions.length * 0.7) {
    message = '<i class="fas fa-star"></i> <strong>Muito bom!</strong> Você tem um bom entendimento da lição de Jetro. Continue estudando a Palavra para aprofundar seu conhecimento sobre liderança sábia.';
  } else if (score >= allQuestions.length * 0.5) {
    message = '<i class="fas fa-check-circle"></i> <strong>Bom trabalho!</strong> Você acertou a maioria das questões. Reveja os pontos em que teve dificuldade para fortalecer seu entendimento sobre delegação.';
  } else {
    message = '<i class="fas fa-book"></i> <strong>Continue estudando!</strong> Os conselhos de Jetro têm lições preciosas sobre liderança. Reveja a lição e tente novamente para consolidar seu aprendizado.';
  }
  
  messageElement.innerHTML = message;
}

function restartQuiz() {
  userAnswers = new Array(allQuestions.length).fill(null);
  currentQuestionIndex = 0;
  
  document.getElementById('results').style.display = 'none';
  document.querySelector('.modern-header').style.display = 'block';
  document.querySelector('.content-section').style.display = 'flex';
  
  // Rolagem suave para o topo
  window.scrollTo({ top: 0, behavior: 'smooth' });
}
</script>
</body>
</html>
