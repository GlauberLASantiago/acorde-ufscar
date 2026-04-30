🎵 Acorde UFSCar

Acorde UFSCar é um aplicativo web interativo focado no estudo de harmonia musical, dicionário de acordes e engenharia reversa de notas. Desenvolvido com foco na experiência do utilizador e na precisão da teoria musical, a ferramenta é ideal para estudantes, músicos e professores.

Desenvolvido pelo professor Glauber Santiago — DAC/UFSCar.

<img width="482" height="864" alt="image" src="https://github.com/user-attachments/assets/e39f0478-87d3-4f3d-bddf-7273d9f756de" />


✨ Funcionalidades

🎹 Teclado Virtual Interativo: Selecione a nota fundamental diretamente num teclado visual.

📖 Amplo Dicionário de Acordes: Suporte para 29 tipos de acordes diferentes (Tríades, Tétrades, Acordes Suspensos, Aumentados, com Extensões como 9ª, 11ª, 13ª, etc.).

🔄 InverterFlux (Engenharia Reversa): Modo exclusivo onde o utilizador escolhe apenas uma nota, e o sistema lista todos os acordes catalogados onde aquela nota específica está presente, informando a sua função exata (Ex: Terça Maior, Quinta Diminuta, etc.).

🔊 Áudio Integrado (Síntese Sonora): Reproduza o som do acorde completo ou clique numa linha de intervalo específico para ouvir a nota isolada (gerado via Web Audio API com controlo de envelope e filtro passa-baixa).

🧠 Motor de Enarmonia Inteligente: Calcula a grafia musical correta dos intervalos (diferenciando sustenidos e bemóis matematicamente).

🎨 Feedback Visual de Cores: Os botões e o painel de resultados mudam automaticamente de cor com base na presença da Terça Menor na fórmula do acorde (Verde para categorias menores, Azul para maiores e outros).

📱 PWA (Progressive Web App): Instalável! Pode ser adicionado ao ecrã inicial de smartphones, tablets e computadores para funcionar como uma aplicação nativa.

⌨️ Entrada por Texto Inteligente: Permite digitar o nome do acorde na barra de pesquisa (ex: C7, F#m7b5, Dó menor) para seleção automática.

🚀 Como usar

O aplicativo é constituído por um ficheiro único e não requer dependências complexas (Node.js, NPM, etc.).

Faça o clone ou o download deste repositório.

Abra o ficheiro index.html no seu navegador web preferido.

No modo NormalFlux: Clique na nota fundamental e depois no tipo de acorde (ou digite no ecrã superior).

No modo InverterFlux: Clique no botão azul "🔄 InverterFlux", escolha uma única nota e descubra os acordes que a contêm.

Dica: Para instalar o PWA, basta alojar o index.html em qualquer servidor com HTTPS (como o GitHub Pages) e clicar no botão "⬇️ Instalar" que irá aparecer na interface, ou usar a opção de "Adicionar ao ecrã principal" do seu navegador mobile.

🛠️ Tecnologias Utilizadas

Este projeto foi construído inteiramente com tecnologias web standard (Vanilla), garantindo leveza, rapidez e compatibilidade máxima sem necessidade de bibliotecas externas:

HTML5 (Semântica e estrutura)

CSS3 (CSS Variables, Flexbox, CSS Grid, Transições suaves)

JavaScript (ES6+) (Lógica musical, manipulação de DOM)

Web Audio API (Síntese e reprodução do som dos acordes e notas)

PWA Integrado (Manifesto embutido e Service Worker para instalabilidade)

👤 Autor & Créditos

Glauber Santiago
Professor - Departamento de Artes e Comunicação (DAC) - UFSCar

🌐 Página do Servidor: servidores.ufscar.br/glauber

🌐 Glauberia: sites.google.com/view/glauberia

Este projeto foi concebido para o auxílio didático na aprendizagem de harmonia e estruturação musical.
