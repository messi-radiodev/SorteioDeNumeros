🎲 Sorteador de Números
Projeto simples de sorteio de números aleatórios com base em um intervalo definido pelo usuário.

🔧 Tecnologias Utilizadas
HTML – estrutura da página (pré-existente)

CSS – estilização visual (pré-existente)

JavaScript – lógica do sorteio e interações com o DOM

⚙️ Funcionalidades
✅ sortear()
Recupera os valores dos inputs:

Quantidade de números

Valor inicial do intervalo ("De")

Valor final do intervalo ("Até")

Executa os sorteios com base nos valores informados

Garante que não haja números repetidos

✅ obterNumeroAleatorio(min, max)
Retorna um número aleatório dentro do intervalo desejado:

javascript
Copiar
Editar
return Math.floor(Math.random() * (max - min + 1)) + min;
✅ Controle de repetição
Uso de while para evitar que o mesmo número seja sorteado mais de uma vez

✅ alterarStatusBotao()
Ativa/desativa o botão de reinício usando classList:

Remove a classe desabilitado para ativar

Adiciona novamente a classe para desativar

✅ reiniciar()
Limpa os campos de input

Reseta a área de resultados para o texto padrão

Reativa o botão de sorteio

🖥️ Exemplo de Uso
Informe a quantidade de números a serem sorteados

Digite o número inicial e o número final do intervalo

Clique em Sortear

Clique em Reiniciar para fazer um novo sorteio

📁 Estrutura de Arquivos
pgsql
Copiar
Editar
sorteador-numeros/
├── index.html
├── style.css
└── script.js
🎯 Objetivo do Projeto
Desenvolver a lógica em JavaScript de um sorteador funcional, integrando com HTML/CSS já prontos, utilizando:

Declaração de variáveis

Estruturas de repetição e condição

Manipulação de DOM

Boas práticas com funções

🚀 Status
✅ Projeto concluído e funcionando corretamente

