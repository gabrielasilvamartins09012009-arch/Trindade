<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Aspectos Geográficos de Trindade-GO</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background-color: #f5f5dc;
            font-family: Arial, sans-serif;
            line-height: 1.8;
            color: #333;
            scroll-behavior: smooth;
        }
        header {
            background: linear-gradient(135deg, #228B22, #8B4513);
            color: white;
            text-align: center;
            padding: 40px 20px;
        }
        header h1 {
            font-size: 2.5rem;
        }
        nav {
            background-color: #8B4513;
            padding: 15px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1rem;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #FFD700; /* dourado */
        }
        main {
            padding: 30px 15px;
            max-width: 1000px;
            margin: auto;
        }
        section {
            margin-bottom: 60px;
        }
        .card {
            background: white;
            border-radius: 12px;
            padding: 25px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        h2 {
            color: #228B22;
            margin-bottom: 15px;
        }
        .imagem {
            width: 100%;
            max-height: 350px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 15px;
        }
        footer {
            background: linear-gradient(135deg, #228B22, #8B4513);
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
        /* Responsividade */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }
            nav a {
                display: inline-block;
                margin: 10px;
                font-size: 1rem;
            }
            .card {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Aspectos Geográficos de Trindade-GO</h1>
    </header>

    <nav>
        <a href="#inicio">Início</a>
        <a href="#relevo">Relevo</a>
        <a href="#aspectos">Aspectos Detalhados</a>
    </nav>

    <main>
        <!-- Página inicial -->
        <section id="inicio" class="card">
            <img src="mapa.png" alt="Mapa de Goiás" class="imagem">
            <h2>Introdução</h2>
            <p>
                Trindade, localizada no estado de Goiás, é uma cidade que se destaca não apenas pela sua
                importância religiosa, mas também por suas características geográficas. Situada na região
                central do Brasil, Trindade apresenta aspectos naturais que refletem o bioma Cerrado,
                marcado por vegetação diversificada, solos típicos e um relevo característico do planalto
                central.
            </p>
            <p>
                A geografia da cidade influencia diretamente sua economia, cultura e forma de ocupação
                do espaço. A presença de áreas de relevo suave, rios e nascentes contribui para a
                organização territorial, a prática da agropecuária e a preservação ambiental.
            </p>
            <p>
                Neste site, você encontrará informações detalhadas sobre o relevo de Trindade e, em uma
                segunda parte, uma análise mais aprofundada de seus aspectos geográficos.
            </p>
        </section>

        <!-- Página 1: relevo -->
        <section id="relevo" class="card">
            <img src="relevo.jpg" class="imagem">
            <h2>Relevo de Trindade-GO</h2>
            <p>
                O relevo de Trindade está inserido no contexto do Planalto Central Brasileiro,
                caracterizado por áreas planas a levemente onduladas. Esse tipo de relevo favorece
                atividades agropecuárias, bastante comuns na região.
            </p>
            <p>
                Há também a presença de colinas suaves e pequenas elevações que marcam a transição
                entre áreas urbanizadas e rurais. Os solos, geralmente de média a baixa fertilidade,
                são adaptados ao cultivo mediante técnicas agrícolas.
            </p>
            <p>
                Além disso, a hidrografia local se relaciona com o relevo, visto que a cidade é cortada
                por diversos córregos e nascentes que abastecem a população e contribuem para o
                equilíbrio ambiental.
            </p>
        </section>

        <!-- Página 2: aspectos detalhados -->
        <section id="aspectos" class="card">
            <img src="geo.jpg" alt="Vegetação do Cerrado em Goiás" class="imagem">
            <h2>Aspectos Geográficos Detalhados</h2>
            <p>
                Trindade está situada em uma região de clima tropical, com duas estações bem definidas:
                o período chuvoso (entre outubro e abril) e o período seco (entre maio e setembro).
                Essa variação climática impacta diretamente na agricultura, na vegetação e na
                organização da cidade.
            </p>
            <p>
                O município se insere no bioma Cerrado, reconhecido por sua biodiversidade e pela
                presença de espécies adaptadas às condições climáticas da região. A vegetação é
                composta por campos, áreas de cerrado típico e matas ciliares que acompanham os cursos
                d'água.
            </p>
            <p>
                Do ponto de vista socioeconômico, os aspectos geográficos de Trindade influenciam a
                expansão urbana e as atividades econômicas, como agricultura, pecuária e turismo
                religioso, que juntos moldam a identidade da cidade.
            </p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 - Aspectos Geográficos de Trindade-GO</p>
    </footer>
</body>
</html>
