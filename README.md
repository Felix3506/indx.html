#<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-book Emagrecimento Natural - Método Saudável e Eficaz</title>
    <meta name="description" content="Descubra um método natural e saudável para emagrecer com nosso e-book exclusivo. Receitas, hábitos e técnicas para transformar seu corpo e saúde.">
    <meta name="keywords" content="emagrecimento, natural, saudável, receitas, ebook, perda de peso, dieta">
    <meta name="author" content="Emagrecimento Natural">
    <link rel="canonical" href="https://seusite.com">
    <style>
        /* Reset e estilos base */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f8fafc;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Cabeçalho */
        header {
            background: linear-gradient(to right, #e6f7ee, #d1f2e5);
            text-align: center;
            padding: 60px 20px;
        }
        
        h1 {
            font-size: 2.8rem;
            color: #166534;
            margin-bottom: 20px;
        }
        
        .header-subtitle {
            font-size: 1.5rem;
            color: #374151;
            margin-bottom: 30px;
        }
        
        /* Botões */
        .btn {
            display: inline-block;
            background-color: #f97316;
            color: white;
            font-weight: bold;
            padding: 16px 32px;
            border-radius: 50px;
            text-decoration: none;
            font-size: 1.1rem;
            transition: all 0.3s;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        .btn:hover {
            background-color: #ea580c;
            transform: translateY(-3px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
        }
        
        /* Seções */
        section {
            padding: 60px 0;
        }
        
        .section-title {
            text-align: center;
            font-size: 2.2rem;
            color: #166534;
            margin-bottom: 40px;
        }
        
        /* Benefícios */
        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-bottom: 40px;
        }
        
        .benefit-card {
            background: white;
            padding: 30px;
            border-radius: 16px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s;
        }
        
        .benefit-card:hover {
            transform: translateY(-5px);
        }
        
        .benefit-icon {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        
        /* Resultados */
        .results {
            background-color: #f0fdf4;
            text-align: center;
        }
        
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }
        
        .stat-card {
            background: white;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
        }
        
        .stat-number {
            font-size: 2.5rem;
            font-weight: bold;
            color: #f97316;
            margin-bottom: 10px;
        }
        
        /* Depoimentos */
        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .testimonial-card {
            background: white;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s;
        }
        
        .testimonial-card:hover {
            transform: translateY(-5px);
        }
        
        .testimonial-header {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
        }
        
        .testimonial-avatar {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background-color: #d1f2e5;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            margin-right: 15px;
        }
        
        /* Bônus */
        .bonus-section {
            background: linear-gradient(to right, #f0fdf4, #e6f7ee);
        }
        
        .bonus-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }
        
        .bonus-card {
            background: white;
            padding: 30px;
            border-radius: 16px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            text-align: center;
            transition: transform 0.3s;
        }
        
        .bonus-card:hover {
            transform: translateY(-5px);
        }
        
        .bonus-icon {
            font-size: 3rem;
            margin-bottom: 20px;
        }
        
        /* Garantia */
        .guarantee {
            text-align: center;
            background-color: white;
        }
        
        .guarantee-badge {
            display: inline-block;
            background-color: #dcfce7;
            padding: 20px;
            border-radius: 50%;
            margin-bottom: 30px;
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        /* FAQ */
        .faq-section {
            background-color: #f8fafc;
        }
        
        .faq-container {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .faq-item {
            background: white;
            margin-bottom: 20px;
            border-radius: 12px;
            padding: 25px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
        }
        
        /* Oferta */
        .offer {
            text-align: center;
            background: linear-gradient(to right, #166534, #22c55e);
            color: white;
            padding: 80px 20px;
        }
        
        .price-container {
            background: white;
            color: #333;
            padding: 40px;
            border-radius: 20px;
            display: inline-block;
            margin: 30px 0;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }
        
        .old-price {
            text-decoration: line-through;
            color: #6b7280;
            font-size: 1.5rem;
        }
        
        .new-price {
            font-size: 3rem;
            font-weight: bold;
            color: #166534;
        }
        
        /* Footer */
        footer {
            background-color: #0f172a;
            color: #e2e8f0;
            padding: 40px 0;
            text-align: center;
        }
        
        /* Responsividade */
        @media (max-width: 768px) {
            h1 {
                font-size: 2.2rem;
            }
            
            .header-subtitle {
                font-size: 1.2rem;
            }
            
            .section-title {
                font-size: 1.8rem;
            }
            
            .new-price {
                font-size: 2.5rem;
            }
        }
    </style>
</head>
<body>
    <!-- Cabeçalho -->
    <header>
        <div class="container">
            <h1>🌱 Emagreça de Forma 100% Natural e Saudável!</h1>
            <p class="header-subtitle">📘 Descubra o método simples, prático e eficaz para perder peso sem dietas malucas nem remédios prejudiciais.</p>
            <a href="#offer" class="btn">QUERO EMAGRECER AGORA!</a>
        </div>
    </header>

    <!-- Benefícios -->
    <section class="benefits">
        <div class="container">
            <h2 class="section-title">🔥 Por Que Este Método Funciona?</h2>
            <div class="benefits-grid">
                <div class="benefit-card">
                    <div class="benefit-icon">✔</div>
                    <h3>Técnicas Científicas</h3>
                    <p>Métodos baseados em estudos científicos da nutrição funcional para resultados comprovados.</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">✔</div>
                    <h3>Resultados Sustentáveis</h3>
                    <p>Foco em mudanças de hábitos para evitar o efeito sanfona e manter o peso ideal.</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">✔</div>
                    <h3>Adaptável à Sua Rotina</h3>
                    <p>Método flexível que se adapta a qualquer estilo de vida, mesmo para quem tem pouco tempo.</p>
                </div>
            </div>
            
            <h2 class="section-title">✅ O Que Você Vai Aprender:</h2>
            <div class="benefits-grid">
                <div class="benefit-card">
                    <div class="benefit-icon">🍵</div>
                    <h3>Receitas Metabólicas</h3>
                    <p>Receitas naturais que aceleram o metabolismo em até 40% sem produtos químicos.</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">⚡</div>
                    <h3>Hábitos Energéticos</h3>
                    <p>Rituais matinais para ter mais energia e disposição durante todo o dia.</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">🥗</div>
                    <h3>Controle Alimentar</h3>
                    <p>Como controlar a fome emocional e os desejos por comida sem sofrimento.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Resultados -->
    <section class="results">
        <div class="container">
            <h2 class="section-title">📈 Resultados Reais em Apenas 30 Dias</h2>
            <div class="stats-grid">
                <div class="stat-card">
                    <div class="stat-number">5-7kg</div>
                    <p>Perda de peso média</p>
                </div>
                <div class="stat-card">
                    <div class="stat-number">83%</div>
                    <p>Redução no desejo por doces</p>
                </div>
                <div class="stat-card">
                    <div class="stat-number">2x</div>
                    <p>Mais energia no dia a dia</p>
                </div>
            </div>
            <p class="header-subtitle">✨ Mais de <strong>3.200 pessoas</strong> já transformaram seus corpos e saúde com este método. Você pode ser o próximo caso de sucesso!</p>
            <a href="#offer" class="btn">QUERO MEU E-BOOK AGORA</a>
        </div>
    </section>

    <!-- Depoimentos -->
    <section class="testimonials">
        <div class="container">
            <h2 class="section-title">💬 O Que Nossos Leitores Dizem</h2>
            <div class="testimonials-grid">
                <div class="testimonial-card">
                    <div class="testimonial-header">
                        <div class="testimonial-avatar">A</div>
                        <div>
                            <h3>Ana Clara, 32 anos</h3>
                            <div>★★★★★</div>
                        </div>
                    </div>
                    <p>"Perdi 7kg em apenas 5 semanas seguindo o método! O melhor é que não senti fome e nem precisei cortar completamente o que gosto. Aprendi a ter equilíbrio!"</p>
                    <p class="testimonial-stats">Antes: 78kg | Depois: 71kg</p>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-header">
                        <div class="testimonial-avatar">C</div>
                        <div>
                            <h3>Carlos, 41 anos</h3>
                            <div>★★★★★</div>
                        </div>
                    </div>
                    <p>"Sempre tentei dietas radicais e falhava. Com esse e-book aprendi a mudar meus hábitos de forma gradual. Em 2 meses perdi 9kg e mantive o peso por mais de 1 ano!"</p>
                    <p class="testimonial-stats">Antes: 92kg | Depois: 83kg</p>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-header">
                        <div class="testimonial-avatar">M</div>
                        <div>
                            <h3>Mariana, 28 anos</h3>
                            <div>★★★★★</div>
                        </div>
                    </div>
                    <p>"Depois da gravidez estava com dificuldade para perder peso. As receitas e dicas do e-book me ajudaram a perder 6kg sem afetar minha amamentação."</p>
                    <p class="testimonial-stats">Antes: 68kg | Depois: 62kg</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Bônus -->
    <section class="bonus-section">
        <div class="container">
            <h2 class="section-title">🎁 Bônus Exclusivos</h2>
            <p class="header-subtitle">(Disponíveis apenas durante esta oferta especial)</p>
            
            <div class="bonus-grid">
                <div class="bonus-card">
                    <div class="bonus-icon">📋</div>
                    <h3>Lista de Compras Inteligente</h3>
                    <p>Alimentos que aceleram o metabolismo, onde comprar com melhor custo-benefício e versão vegetariana inclusa.</p>
                </div>
                
                <div class="bonus-card">
                    <div class="bonus-icon">🍽️</div>
                    <h3>Cardápio Semanal Pronto</h3>
                    <p>4 semanas de refeições planejadas, opções rápidas para dias corridos e versão para famílias inclusa.</p>
                </div>
                
                <div class="bonus-card">
                    <div class="bonus-icon">🎧</div>
                    <h3>Áudios de Meditação Guiada</h3>
                    <p>Redução do estresse e ansiedade, controle da compulsão alimentar e melhora na qualidade do sono.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Garantia -->
    <section class="guarantee">
        <div class="container">
            <div class="guarantee-badge">
                <div style="width: 80px; height: 80px; background-color: #22c55e; border-radius: 50%; display: flex; align-items: center; justify-content: center; color: white; font-size: 1.8rem; font-weight: bold;">7</div>
            </div>
            <h2 class="section-title">Garantia Incondicional de 7 Dias</h2>
            <p class="header-subtitle">Teste nosso método por 7 dias completos. Se por qualquer motivo você não estiver satisfeito, devolvemos 100% do seu dinheiro sem questionamentos.</p>
            <div style="background-color: #f0fdf0; padding: 15px; border-radius: 8px; display: inline-block; margin-top: 20px;">
                <p style="font-weight: bold; color: #166534;">✔ Você não assume nenhum risco!</p>
            </div>
        </div>
    </section>

    <!-- FAQ -->
    <section class="faq-section">
        <div class="container">
            <h2 class="section-title">❓ Perguntas Frequentes</h2>
            
            <div class="faq-container">
                <div class="faq-item">
                    <h3>1. Como receberei o e-book após a compra?</h3>
                    <p>Imediatamente após a confirmação do pagamento, você receberá um e-mail com o link para download do e-book em PDF e todos os bônus. O processo é automático e você pode acessar o material em qualquer dispositivo.</p>
                </div>
                
                <div class="faq-item">
                    <h3>2. Preciso seguir dietas restritivas com esse método?</h3>
                    <p>Não! Nosso foco é na reeducação alimentar e em mudanças sustentáveis. Você aprenderá a fazer escolhas mais inteligentes sem precisar cortar completamente os alimentos que ama. O equilíbrio é a chave.</p>
                </div>
                
                <div class="faq-item">
                    <h3>3. Quanto tempo leva para ver resultados?</h3>
                    <p>A maioria dos nossos alunos começa a perceber diferenças já na primeira semana (mais energia, menos inchaço). A perda de peso significativa geralmente ocorre a partir da segunda/terceira semana, variando conforme o metabolismo de cada pessoa.</p>
                </div>
                
                <div class="faq-item">
                    <h3>4. Posso usar o método se tiver problemas de saúde?</h3>
                    <p>O método é 100% natural e baseado em alimentos, portanto seguro para a maioria das pessoas. Porém, se você tem condições específicas (diabetes, hipertensão, etc.), recomendamos consultar seu médico antes de iniciar qualquer mudança alimentar.</p>
                </div>
                
                <div class="faq-item">
                    <h3>5. Como funciona a garantia de 7 dias?</h3>
                    <p>Se dentro de 7 dias após a compra você achar que o conteúdo não atendeu suas expectativas, basta nos enviar um e-mail que devolveremos todo seu dinheiro, sem burocracia. Você nem precisa justificar sua decisão.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Oferta -->
    <section id="offer" class="offer">
        <div class="container">
            <h2 style="font-size: 2.5rem; margin-bottom: 20px;">⚠️ Oferta por Tempo Limitado!</h2>
            <p style="font-size: 1.3rem; margin-bottom: 30px;">Adquira agora e receba todos os bônus exclusivos</p>
            
            <div class="price-container">
                <div style="margin-bottom: 20px;">
                    <span class="old-price">De R$ 97,00</span>
                    <p class="new-price">Por apenas R$ 29,90</p>
                </div>
                
                <ul style="text-align: left; margin-bottom: 30px; list-style-type: none;">
                    <li style="margin-bottom: 10px; display: flex; align-items: center;">
                        <span style="background-color: #dcfce7; color: #166534; border-radius: 50%; width: 24px; height: 24px; display: inline-flex; align-items: center; justify-content: center; margin-right: 10px;">✔</span>
                        E-book completo "Emagrecimento Natural" (PDF)
                    </li>
                    <li style="margin-bottom: 10px; display: flex; align-items: center;">
                        <span style="background-color: #dcfce7; color: #166534; border-radius: 50%; width: 24px; height: 24px; display: inline-flex; align-items: center; justify-content: center; margin-right: 10px;">✔</span>
                        Lista de Compras Inteligente (bônus)
                    </li>
                    <li style="margin-bottom: 10px; display: flex; align-items: center;">
                        <span style="background-color: #dcfce7; color: #166534; border-radius: 50%; width: 24px; height: 24px; display: inline-flex; align-items: center; justify-content: center; margin-right: 10px;">✔</span>
                        Cardápio Semanal Pronto (bônus)
                    </li>
                    <li style="margin-bottom: 10px; display: flex; align-items: center;">
                        <span style="background-color: #dcfce7; color: #166534; border-radius: 50%; width: 24px; height: 24px; display: inline-flex; align-items: center; justify-content: center; margin-right: 10px;">✔</span>
                        Áudios de Meditação Guiada (bônus)
                    </li>
                    <li style="margin-bottom: 10px; display: flex; align-items: center;">
                        <span style="background-color: #dcfce7; color: #166534; border-radius: 50%; width: 24px; height: 24px; display: inline-flex; align-items: center; justify-content: center; margin-right: 10px;">✔</span>
                        Acesso Imediato e Vitalício
                    </li>
                    <li style="display: flex; align-items: center;">
                        <span style="background-color: #dcfce7; color: #166534; border-radius: 50%; width: 24px; height: 24px; display: inline-flex; align-items: center; justify-content: center; margin-right: 10px;">✔</span>
                        Garantia de 7 Dias
                    </li>
                </ul>
                
                <!-- Substitua o link abaixo pelo seu link do Mercado Pago -->
                <a href="https://www.mercadopago.com.br/checkout/v1/redirect?pref_id=SEU_ID_AQUI" class="btn" style="font-size: 1.2rem; padding: 18px 40px;">
                    SIM, QUERO EMAGRECER AGORA! 🚀
                </a>
                
                <div style="margin-top: 20px;">
                    <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMjAiIGhlaWdodD0iNDAiIHZpZXdCb3g9IjAgMCAxMjAgNDAiPjxwYXRoIGZpbGw9IiMwMGE0ZTAiIGQ9Ik0xMTMuNCAyMC4xYzAgNS41LTQuNSAxMC0xMCAxMHMtMTAtNC41LTEwLTEwIDQuNS0xMCAxMC0xMCAxMCA0LjUgMTAgMTB6Ii8+PHBhdGggZmlsbD0iIzAwYTRlMCIgZD0iTTg3LjkgMjAuMWMwIDUuNS00LjUgMTAtMTAgMTBzLTEwLTQuNS0xMC0xMCA0LjUtMTAgMTAtMTAgMTAgNC41IDEwIDEweiIvPjxwYXRoIGZpbGw9IiM3NzciIGQ9Ik0zMCAxMC40aDEwdjE5LjJIMzB6Ii8+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgMGgxMjB2NDBIMHoiLz48cGF0aCBmaWxsPSIjMDBhNGUwIiBkPSJNNTIuMyAxMC40YzMuNiAwIDYuNSAyLjkgNi41IDYuNXMtMi45IDYuNS02LjUgNi41YTMuOCAzLjggMCAwIDEtMy44LTMuOGMwLTIuMSAxLjctMy44IDMuOC0zLjggMi4xIDAgMy44IDEuNyAzLjggMy44aDYuNWMwLTUuOC00LjctMTAuNS0xMC41LTEwLjVzLTEwLjUgNC43LTEwLjUgMTAuNSA0LjcgMTAuNSAxMC41IDEwLjVjMy42IDAgNi44LTEuOCA4LjctNC42bC00LjYtMi45Yy0xLjQgMS44LTMuNSAyLjktNi4xIDIuOS0zLjYgMC02LjUtMi45LTYuNS02LjVzMi45LTYuNSA2LjUtNi41YzIuMSAwIDMuOCAxLjcgMy44IDMuOCAwIDIuMS0xLjcgMy44LTMuOCAzLjgtMS4xIDAtMi0uNS0yLjYtMS4zLS40LS42LS43LTEuMy0uNy0yLjFoLTMuNGMwIC44LjIgMS42LjYgMi4zIDEuMSAxLjggMy4xIDMgNS40IDMgMy42IDAgNi41LTIuOSA2LjUtNi41cy0yLjktNi41LTYuNS02LjVjLTIuMSAwLTMuOCAxLjctMy44IDMuOCAwIDIuMSAxLjcgMy44IDMuOCAzLjggMS4xIDAgMi0uNSAyLjYtMS4zLjQtLjYuNy0xLjMuNy0yLjFoLTMuNGMwIC44LjIgMS42LjYgMi4zIDEuMSAxLjggMy4xIDMgNS40IDMgMy42IDAgNi41LTIuOSA2LjUtNi41cy0yLjktNi41LTYuNS02LjVjLTIuMSAwLTMuOCAxLjctMy44IDMuOCAwIDIuMSAxLjcgMy44IDMuOCAzLjggMS4xIDAgMi0uNSAyLjYtMS4zLjQtLjYuNy0xLjMuNy0yLjFoLTMuNGMwIC44LjIgMS42LjYgMi4zIDEuMSAxLjggMy4xIDMgNS40IDMgMy42IDAgNi41LTIuOSA2LjUtNi41cy0yLjktNi41LTYuNS02LjVjLTIuMSAwLTMuOCAxLjctMy44IDMuOCAwIDIuMSAxLjcgMy44IDMuOCAzLjggMS4xIDAgMi0uNSAyLjYtMS4zLjQtLjYuNy0xLjMuNy0yLjFoLTMuNGMwIC44LjIgMS42LjYgMi4zIDEuMSAxLjggMy4xIDMgNS40IDMgMy42IDAgNi41LTIuOSA2LjUtNi41cy0yLjktNi41LTYuNS02LjVjLTIuMSAwLTMuOCAxLjctMy44IDMuOCAwIDIuMSAxLjcgMy44IDMuOCAzLjggMS4xIDAgMi0uNSAyLjYtMS4zLjQtLjYuNy0xLjMuNy0yLjFoLTMuNGMwIC44LjIgMS42LjYgMi4zIDEuMSAxLjggMy4xIDMgNS40IDMgMy42IDAgNi41LTIuOSA2LjUtNi41cy0yLjktNi41LTYuNS02LjVjLTIuMSAwLTMuOCAxLjctMy44IDMuOCAwIDIuMSAxLjcgMy44IDMuOCAzLjggMS4xIDAgMi0uNSAyLjYtMS4zLjQtLjYuNy0xLjMuNy0yLjFoLTMuNGMwIC44LjIgMS42LjYgMi4zIDEuMSAxLjggMy4xIDMgNS40IDMgMy42IDAgNi41LTIuOSA2LjUtNi41cy0yLjktNi41LTYuNS02LjVjLTIuMSAwLTMuOCAxLjctMy44IDMuOCAwIDIuMSAxLjcgMy44IDMuOCAzLjggMS4xIDAgMi0uNSAyLjYtMS4zLjQtLjYuNy0xLjMuNy0yLjFoLTMuNGMwIC44LjIgMS42LjYgMi4zIDEuMSAxLjggMy4xIDMgNS40IDMgMy42IDAgNi41LTIuOSA2LjUtNi41cy0yLjktNi41LTYuNS02LjVjLTIuMSAwLTMuOCAxLjctMy44IDMuOCAwIDIuMSAxLjcgMy44IDMuOCAzLjggMS4xIDAgMi0uNSAyLjYtMS4zLjQtLjYuNy0xLjMuNy0yLjFoLTMuNGMwIC44LjIgMS42LjYgMi4zIDEuMSAxLjggMy4xIDMgNS40IDMgMy42IDAgNi41LTIuOSA2LjUtNi41cy0yLjktNi41LTYuNS02LjVjLTIuMSAwLTMuOCAxLjctMy44IDMuOCAwIDIuMSAxLjcgMy44IDMuOCAzLjggMS4xIDAgMi0uNSAyLjYtMS4zLjQtLjYuNy0xLjMuNy0yLjFoLTMuNGMwIC44LjIgMS42LjYgMi4zIDEuMSAxLjggMy4xIDMgNS40IDMgMy42IDAgNi41LTIuOSA2LjUtNi41cy0yLjktNi41LTYuNS02LjVjLTIuMSAwLTMuOCAxLjctMy44IDMuOCAwIDIuMSAxLjcgMy44IDMuOCAzLjggMS4xIDAgMi0uNSAyLjYtMS4zLjQtLjYuNy0xLjMuNy0yLjFoLTMuNGMwIC44LjIgMS42LjYgMi4zIDEuMSAxLjggMy4xIDMgNS40IDMgMy42IDAgNi41LTIuOSA2LjUtNi41cy0yLjktNi41LTYuNS02LjVjLTIuMSAwLTMuOCAxLjctMy44IDMuOCAwIDIuMSAxLjcgMy44IDMuOCAzLjggMS4xIDAgMi0uNSAyLjYtMS4zLjQtLjYuNy0xLjMuNy0yLjFoLTMuNGMwIC44LjIgMS42LjYgMi4zIDEuMSAxLjggMy4xIDMgNS40IDMgMy42IDAgNi41LTIuOSA6LjUtNi41eiIvPjwvc3ZnPg==" alt="Mercado Pago - Compra Segura" style="height: 40px;">
                    <p style="font-size: 0.9rem; color: #6b7280; margin-top: 5px;">Pagamento 100% seguro</p>
                </div>
            </div>
            
            <p style="font-size: 1.1rem; margin-top: 30px;">⏰ Essa oferta pode encerrar a qualquer momento. Não perca essa chance!</p>
        </div>
    </section>

    <!-- Rodapé -->
    <footer>
        <div class="container">
            <p style="margin-bottom: 20px; font-size: 1.1rem;">💚 Transforme seu corpo e sua saúde com métodos naturais. Sua nova vida começa agora!</p>
            <div style="font-size: 0.9rem;">
                <p style="margin-bottom: 10px;">© 2023 Emagrecimento Natural. Todos os direitos reservados.</p>
                <p style="margin-bottom: 10px;">Este produto não substitui o parecer médico profissional. Sempre consulte um médico antes de iniciar qualquer programa de emagrecimento.</p>
                <p>
                    <a href="#" style="color: #22c55e; text-decoration: none;">Termos de Uso</a> |
                    <a href="#" style="color: #22c55e; text-decoration: none;">Política de Privacidade</a>
                </p>
            </div>
        </div>
    </footer>

    <script>
        // Adicione seu código JavaScript personalizado aqui, se necessário
        // Exemplo: animações de scroll, tracking de conversões, etc.
        
        // Exemplo simples de animação ao scroll
        document.addEventListener('DOMContentLoaded', function() {
            const animatedElements = document.querySelectorAll('.benefit-card, .testimonial-card, .bonus-card');
            
            function checkScroll() {
                animatedElements.forEach(element => {
                    const elementPosition = element.getBoundingClientRect().top;
                    const screenPosition = window.innerHeight / 1.3;
                    
                    if (elementPosition < screenPosition) {
                        element.style.opacity = 1;
                        element.style.transform = 'translateY(0)';
                    }
                });
            }
            
            // Inicializa elementos com opacidade 0 para animação
            animatedElements.forEach(element => {
                element.style.opacity = 0;
                element.style.transform = 'translateY(20px)';
                element.style.transition = 'opacity 0.5s ease, transform 0.5s ease';
            });
            
            window.addEventListener('scroll', checkScroll);
            checkScroll(); // Verifica na carga inicial
        });
    </script>
</body>
</html>