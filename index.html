<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>O Meu Mundo</title>
    <!-- Importação de fonte elegante semelhante à da imagem -->
    <link href="https://googleapis.com" rel="stylesheet">
    
    <style>
        /* Fundo roxo escuro com degradê */
        body {
            margin: 0;
            padding: 0;
            background: linear-gradient(180deg, #0d041a 0%, #230a3a 50%, #0d041a 100%);
            color: #ffffff;
            font-family: 'Playfair Display', serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-between;
            min-height: 100vh;
            box-sizing: border-box;
            padding: 50px 20px;
            text-align: center;
            overflow: hidden;
            position: relative;
        }

        /* Efeito de Brilhinhos/Partículas que sobem */
        .particula {
            position: absolute;
            background: rgba(255, 255, 255, 0.7);
            border-radius: 50%;
            pointer-events: none;
            bottom: -10px;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.8);
            animation: subirParticula linear infinite;
        }

        @keyframes subirParticula {
            0% { transform: translateY(0) scale(0); opacity: 0; }
            50% { opacity: 0.8; }
            100% { transform: translateY(-105vh) scale(1); opacity: 0; }
        }

        /* Texto superior */
        .mensagem {
            font-size: 1.35rem;
            line-height: 1.8;
            max-width: 90%;
            height: 90px;
            color: #f3e9f9;
            text-shadow: 0 0 8px rgba(255,255,255,0.2);
            z-index: 10;
        }

        /* Área da animação central */
        .canvas-container {
            position: relative;
            width: 320px;
            height: 350px;
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 5;
        }

        /* 1. Estruturação do Caule Verde */
        .caule {
            position: absolute;
            bottom: 20px;
            width: 12px;
            height: 180px;
            background: linear-gradient(to top, #1e7e34, #2cc159);
            border-radius: 6px;
            transform-origin: bottom;
            animation: crescerCaule 1.8s cubic-bezier(0.4, 0, 0.2, 1) forwards;
            box-shadow: 0 0 10px rgba(44, 193, 89, 0.3);
        }

        /* Ramos verdes laterais */
        .ramo {
            position: absolute;
            width: 8px;
            height: 45px;
            background-color: #2cc159;
            border-radius: 4px;
            transform-origin: bottom;
            scale: 0;
        }
        .ramo.esquerdo {
            bottom: 60px;
            left: -20px;
            transform: rotate(-45deg);
            animation: crescerRamo 0.8s ease-out 1s forwards;
        }
        .ramo.direito {
            bottom: 100px;
            right: -20px;
            transform: rotate(45deg);
            animation: crescerRamo 0.8s ease-out 1.4s forwards;
        }

        /* 2. Coração feito de pontos luminosos rosa/vermelhos */
        .ponto-coracao {
            position: absolute;
            width: 8px;
            height: 8px;
            background-color: #ff3366;
            border-radius: 50%;
            box-shadow: 0 0 12px #ff3366, 0 0 20px #ff3366;
            opacity: 0;
            transform: scale(0);
            animation: acenderPonto 0.5s ease-out forwards;
        }

        /* Bloco Inferior (Suave / Fade-in) */
        .bloco-inferior {
            opacity: 0;
            animation: efeitoSuave 2s ease-out 5s forwards;
            z-index: 10;
        }

        .titulo-contador {
            font-style: italic;
            font-size: 1.25rem;
            margin-bottom: 18px;
            color: #eae1f0;
        }

        /* Caixa de contagem arredondada igual à imagem */
        .caixa-contador {
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255, 255, 255, 0.12);
            border-radius: 50px;
            padding: 14px 40px;
            font-size: 1.45rem;
            font-weight: 600;
            color: #ff5e84;
            text-shadow: 0 0 12px rgba(255, 94, 132, 0.5);
            box-shadow: 0 8px 24px rgba(0,0,0,0.3);
            letter-spacing: 0.5px;
        }

        /* Animações CSS */
        @keyframes crescerCaule {
            from { transform: scaleY(0); }
            to { transform: scaleY(1); }
        }
        @keyframes crescerRamo {
            to { scale: 1; }
        }
        @keyframes acenderPonto {
            to { opacity: 1; transform: scale(1); }
        }
        @keyframes efeitoSuave {
            to { opacity: 1; }
        }
    </style>
</head>
<body>

    <!-- Texto Superior -->
    <div class="mensagem" id="textoLetraPorLetra"></div>

    <!-- Estrutura da Planta e Coração -->
    <div class="canvas-container" id="containerRosa">
        <div class="caule">
            <div class="ramo esquerdo"></div>
            <div class="ramo direito"></div>
        </div>
    </div>

    <!-- Bloco do Contador -->
    <div class="bloco-inferior">
        <div class="titulo-contador">Meu amor por ti começou em:</div>
        <div class="caixa-contador" id="contador">0 dias 00h 00m 00s</div>
    </div>

    <script>
        // CONFIGURAÇÃO DA DATA: 14 de Fevereiro deste ano (2026)
        const dataInicio = new Date(2026, 1, 14, 0, 0, 0); 

        // Gerador Automático de Brilhinhos de Fundo
        function criarBrilhinhos() {
            const numParticulas = 35;
            for (let i = 0; i < numParticulas; i++) {
                let particula = document.createElement('div');
                particula.className = 'particula';
                particula.style.left = Math.random() * 100 + 'vw';
                particula.style.width = particula.style.height = (Math.random() * 4 + 2) + 'px';
                particula.style.animationDelay = Math.random() * 8 + 's';
                particula.style.animationDuration = Math.random() * 6 + 6 + 's';
                document.body.appendChild(particula);
            }
        }
        criarBrilhinhos();

        // Lógica Matemática do Contador Crescente
        function atualizarContador() {
            const agora = new Date();
            const diferenca = agora - dataInicio;

            const dias = Math.floor(diferenca / (1000 * 60 * 60 * 24));
            const horas = Math.floor((diferenca % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const minutos = Math.floor((diferenca % (1000 * 60 * 60)) / (1000 * 60));
            const segundos = Math.floor((diferenca % (1000 * 60)) / 1000);

            document.getElementById('contador').innerHTML = 
                `${dias} dias ${String(horas).padStart(2, '0')}h ${String(minutos).padStart(2, '0')}m ${String(segundos).padStart(2, '0')}s`;
        }
        setInterval(atualizarContador, 1000);
        atualizarContador();

        // Construção Matemática dos Pontos do Coração Luminoso
        const container = document.getElementById('containerRosa');
        const totalPontos = 32; 
        const delayInicialCoracao = 2000; // Começa após 2 segundos (quando o caule termina)

        for (let i = 0; i < totalPontos; i++) {
            // Equação paramétrica para desenhar um formato de coração perfeito
            const t = (i / totalPontos) * 2 * Math.PI;
            const x = 16 * Math.pow(Math.sin(t), 3);
            const y = 13 * Math.cos(t) - 5 * Math.cos(2*t) - 2 * Math.cos(3*t) - Math.cos(4*t);
            
            const ponto = document.createElement('div');
            ponto.className = 'ponto-coracao';
            
            // Posicionamento e centralização no topo do caule
            ponto.style.left = (160 + x * 5.5) + 'px'; 
            ponto.style.top = (110 - y * 5.5) + 'px'; 
            
            // Ordem sequencial para acender da base até às curvas superiores
            ponto.style.animationDelay = (delayInicialCoracao + (i * 70)) + 'ms';
            container.appendChild(ponto);
        }

        // Escrita do Texto Superior Letra por Letra
        const fraseCompleta = "O meu mundo ficou mais bonito no dia em que te encontrei... e desde então, só cresce o que sinto por ti. I love you.";
        let index = 0;

        function escreverTexto() {
            if (index < fraseCompleta.length) {
                document.getElementById("textoLetraPorLetra").innerHTML += fraseCompleta.charAt(index);
                index++;
                setTimeout(escreverTexto, 65); 
            }
        }
        // Ativa a escrita logo após o coração terminar de se estruturar completamente
        setTimeout(escreverTexto, 4500);
    </script>

</body>
</html>
