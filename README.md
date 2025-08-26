# Visão Geral do Projeto
Este projeto é uma **calculadora de IMC (Índice de Massa Corporal)**, desenvolvida com uma estrutura simples usando **HTML, CSS e JavaScript**. O objetivo principal é permitir que o usuário insira sua altura e peso para calcular o seu IMC e, em seguida, exibir o resultado com a classificação de sua condição (por exemplo, "abaixo do peso", "peso normal", "sobrepeso", etc.).

# Estrutura do Projeto
A estrutura de arquivos do projeto é bem direta:

 - `index.html`: Contém a estrutura da página, incluindo o formulário para a entrada de dados (altura e peso), um botão para calcular e o local onde o resultado será exibido.

 - `style.css`: Responsável por toda a estilização da página, garantindo um visual limpo e responsivo.

 - `script.js`: O cérebro do projeto. É onde a lógica de cálculo do IMC é implementada, capturando os valores do formulário, processando a equação e manipulando o HTML para exibir o resultado e a classificação.

# Funcionalidades
A calculadora de IMC possui as seguintes funcionalidades:

 - **Entrada de Dados**: Campos para o usuário inserir sua altura e peso.

 - **Cálculo**: Um botão que, ao ser clicado, aciona a função em JavaScript para calcular o IMC. A fórmula utilizada é: [IMC=
fracpesoaltura 
2
 .]

 - **Exibição de Resultado**: O resultado do cálculo é exibido na tela.

 - **Classificação do IMC**: O código verifica o valor do IMC e o classifica de acordo com a tabela padrão de IMC da OMS, informando ao usuário em qual categoria ele se encontra.

# Como Usar
É muito simples testar a calculadora:

1. **Clone o repositório**: No seu terminal, execute o comando:
```
git clone https://github.com/ParreirasJuniorWeb/Calculadora_IMC_HTML_CSS_javascript.git
```
2. **Abra o arquivo**: Abra o arquivo `index.html` em seu navegador web preferido (como Chrome, Firefox ou Edge).

3. **Insira seus dados**: Digite sua altura (em metros) e seu peso (em quilogramas).

4. **Calcule**: Clique no botão "Calcular IMC" e veja o resultado.
