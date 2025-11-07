🎨 Arte Generativa com Turtle

Este projeto cria uma espiral colorida animada usando a biblioteca turtle do Python.
A cada iteração, a tartaruga muda de cor e desenha uma linha, criando um padrão visual dinâmico e artístico.

🐍 Requisitos

Antes de executar o código, certifique-se de ter o Python instalado em sua máquina.
Você pode verificar digitando no terminal:

python --version


O script utiliza apenas bibliotecas padrão do Python (turtle e random), portanto não é necessário instalar pacotes adicionais.

🚀 Como Executar

Baixe o arquivo pratica.py

Abra o terminal na pasta onde o arquivo está salvo

Execute o comando:

python pratica.py


Uma janela será aberta mostrando a animação da espiral colorida.
Para sair, basta fechar a janela manualmente.

🧩 Estrutura do Código

configurar_tela()
Configura a tela do Turtle:

Define o fundo preto

Coloca título na janela

Cria a tartaruga com velocidade máxima e espessura de linha

desenhar_espiral(t, tamanho_maximo)
Função responsável por desenhar a espiral principal.
Ela:

Escolhe cores aleatórias

Avança e gira a tartaruga a cada passo

Aumenta progressivamente o tamanho da linha

Programa principal
Chama as funções acima e mantém a janela aberta até ser fechada manualmente.

🖼️ Exemplo de Resultado

O programa gera uma espiral colorida, semelhante a uma arte abstrata animada:

🔴🟣🔵🟢🟠🟡


Cada execução cria uma variação única, já que as cores são escolhidas aleatoriamente.

📜 Licença

© 2025 – Uso livre para fins educacionais.
Créditos: Gustavo Pedruzzi Borini (autor do código base).
