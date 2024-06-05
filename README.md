<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hello Creators</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        .container {
            width: 90%;
            margin: auto;
            overflow: hidden;
        }
        .services, .contact {
            padding: 2rem 0;
        }
        .services h2, .contact h2 {
            text-align: center;
            margin-bottom: 1.5rem;
        }
        .service-item {
            background: white;
            margin-bottom: 1.5rem;
            padding: 1rem;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .service-item h3 {
            margin-top: 0;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .contact-info {
            text-align: center;
        }
        .contact-info a {
            color: #333;
            text-decoration: none;
        }
        @media (min-width: 600px) {
            .service-item {
                display: flex;
                justify-content: space-between;
                align-items: center;
            }
            .service-item div {
                flex: 1;
                padding: 1rem;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Hello Creators</h1>
        <p>Transformando ideias em resultados</p>
    </header>

    <div class="container">

        <section class="services">
            <h2>Nossos Serviços</h2>
            <div class="service-item">
                <div>
                    <h3>Agenciamento 2.0</h3>
                    <p>A Hello Creators simplifica todo o processo de trabalho com influenciadores, desde a seleção do perfil ideal até a entrega das campanhas. Nossa abordagem cuidadosa elimina a burocracia e o gerenciamento tedioso, deixando você livre para desfrutar dos resultados tangíveis.</p>
                    <p>Imagine ter uma agência cuidando de toda a parte burocrática como: Hunting, contratos, gestão de pagamentos e negociações, roteirização de campanhas, gestão de KPI's, enquanto você aproveita os benefícios de campanhas bem-sucedidas e resultados mensuráveis. Estou certo de que podemos ajudá-lo a alcançar seus objetivos de marketing de forma eficiente e sem complicações.</p>
                </div>
            </div>

            <div class="service-item">
                <div>
                    <h3>Consultoria</h3>
                    <p>Ao se deparar com a necessidade de influenciar público, criamos um processo que alinha toda a gestão desse serviço de maneira que treinamos sua equipe para que ordenadamente sejam capazes de fazer por si mesma o Marketing de influência, desde o hunting até a gestão das campanhas para reduzir custos e aprimorar resultados.</p>
                </div>
            </div>
        </section>

        <section class="contact">
            <h2>Contato</h2>
            <div class="contact-info">
                <p>Email: <a href="mailto:comercial@hellocreators.com.br">comercial@hellocreators.com.br</a></p>
                <p>WhatsApp: <a href="https://wa.me/5579999614624" target="_blank">+55 (79) 99961-4624</a></p>
                <p>Instagram: <a href="https://instagram.com/hellocreators" target="_blank">@hellocreators</a></p>
                <p>LinkedIn: <a href="https://www.linkedin.com/company/hellocreatosag/" target="_blank">Hello Creators</a></p>
            </div>
        </section>

    </div>

    <footer>
        <p>&copy; 2024 Hello Creators. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
