# ⛽ Calculadora de Combustível

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)
![Deploy](https://img.shields.io/badge/Deploy-GitHub%20Pages-blue)

## 🚀 Acesse o projeto

**[👉 Clique aqui para testar a Calculadora de Combustível](https://nunes39-cmyk.github.io/Calculadora-de-combust-vel/)**

A aplicação está publicada no GitHub Pages e pode ser acessada diretamente pelo navegador, sem necessidade de instalação.

## 📖 Sobre o projeto

A **Calculadora de Combustível** é uma aplicação web desenvolvida utilizando **HTML, CSS e JavaScript**, com o objetivo de ajudar o usuário a comparar os preços da gasolina e do etanol (álcool) e identificar qual opção tende a ser mais vantajosa economicamente.

O sistema utiliza a conhecida regra dos 70%, realizando automaticamente a divisão do preço do etanol pelo preço da gasolina.

Além da calculadora, o projeto conta com uma página explicativa que demonstra como o cálculo é realizado.

O projeto foi desenvolvido para praticar conceitos de desenvolvimento web, manipulação de elementos HTML e lógica de programação com JavaScript.

## ⚙️ Funcionalidades

- Inserção do preço por litro do etanol.
- Inserção do preço por litro da gasolina.
- Cálculo automático da proporção entre os preços.
- Identificação do combustível mais vantajoso segundo a regra dos 70%.
- Exibição do resultado diretamente na página.
- Exibição dos valores informados pelo usuário.
- Campos numéricos obrigatórios com valor mínimo configurado.
- Página adicional explicando o funcionamento do cálculo.
- Navegação entre a calculadora e a página explicativa.
- Disponibilização gratuita pelo GitHub Pages.

## 🧮 Como funciona o cálculo?

A calculadora utiliza a seguinte fórmula:

**Proporção = Preço do etanol ÷ Preço da gasolina**

A partir do resultado, o sistema aplica as condições:

| Resultado | Recomendação |
|---|---|
| Menor que 0,70 | Compensa utilizar etanol |
| Maior ou igual a 0,70 | Compensa utilizar gasolina |

### 📊 Exemplo prático

Considere os seguintes preços:

| Combustível | Preço por litro |
|---|---:|
| Etanol | R$ 3,90 |
| Gasolina | R$ 6,80 |

**Cálculo:**

```text
3,90 ÷ 6,80 = 0,5735
```

Como o resultado é menor que 0,70, a calculadora recomenda:

**✅ Compensa abastecer com etanol!**

### ⚠️ Observação importante

A regra dos 70% é uma referência simplificada, não uma garantia de economia para todos os veículos.

O resultado real depende do consumo específico do automóvel com cada combustível.

Por exemplo, veículos flex modernos podem apresentar uma relação de eficiência diferente de 70%. Para uma comparação mais precisa, seria necessário considerar o consumo em km/L de cada combustível.

## 🛠️ Tecnologias utilizadas

| Tecnologia | Finalidade |
|---|---|
| HTML5 | Estrutura da aplicação e formulários |
| CSS3 | Estilização da interface |
| JavaScript | Cálculo, condições e atualização dos resultados |
| GitHub | Versionamento e hospedagem do código |
| GitHub Pages | Publicação da aplicação na web |

## 📁 Estrutura do projeto

```text
Calculadora-de-combust-vel/
│
├── assets/
│   ├── logo.png
│   └── info.png
│
├── calculohtml/
│   └── calculo.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── index.html
│
└── README.md
```

### Descrição dos componentes

**`index.html`**

Página principal da calculadora, contendo o formulário para informar os preços e a área de exibição dos resultados.

**`css/style.css`**

Arquivo responsável pela aparência visual da aplicação.

**`js/script.js`**

Contém a função `calcular()`, que recebe os valores digitados, calcula a proporção entre os combustíveis e apresenta a recomendação.

**`calculohtml/calculo.html`**

Página explicativa que demonstra a fórmula utilizada, apresenta um exemplo e permite retornar à calculadora.

**`assets/`**

Diretório destinado às imagens utilizadas na interface, como o logotipo e o ícone de informações.

## 💻 Como utilizar

1. Acesse a [Calculadora de Combustível](https://nunes39-cmyk.github.io/Calculadora-de-combust-vel/).
2. Informe o preço do litro do etanol.
3. Informe o preço do litro da gasolina.
4. Clique no botão **Calcular**.
5. Confira qual combustível é recomendado.

Para entender a lógica utilizada, clique no ícone de informações disponível na interface.

## 🚀 Como executar localmente

Não é necessário instalar bibliotecas ou dependências externas.

1. Baixe ou clone o repositório:

```bash
git clone https://github.com/nunes39-cmyk/Calculadora-de-combust-vel.git
```

2. Abra a pasta do projeto.
3. Execute o arquivo `index.html` em um navegador.
4. Informe os preços e utilize a calculadora normalmente.

O projeto funciona inteiramente no navegador, utilizando JavaScript para realizar os cálculos.

## 🧠 Conceitos de programação aplicados

- Estruturação de páginas com HTML5.
- Estilização de elementos utilizando CSS3.
- Manipulação do DOM com JavaScript.
- Captura de valores de campos HTML.
- Utilização de variáveis.
- Operações matemáticas.
- Estruturas condicionais `if` e `else`.
- Manipulação de eventos de formulário.
- Atualização dinâmica de conteúdo.
- Organização de arquivos em diretórios.
- Publicação de aplicações estáticas.

## 📌 Limitações do projeto

A aplicação foi desenvolvida para fins de estudo e utilização como ferramenta de comparação simplificada.

- Utiliza a proporção fixa de 70%.
- Não considera o consumo individual de cada veículo.
- Não consulta preços de postos de combustível automaticamente.
- Não armazena histórico de cálculos.
- Não utiliza banco de dados ou servidor próprio.

## 🎯 Objetivo do projeto

Desenvolver uma aplicação web funcional para colocar em prática os conhecimentos de HTML, CSS e JavaScript.

O projeto também busca demonstrar como uma lógica matemática simples pode ser transformada em uma ferramenta interativa e acessível pela internet.

## 👨‍💻 Autor

**Miguel Nunes Ribeiro**

Estudante de Análise e Desenvolvimento de Sistemas.

GitHub: [@nunes39-cmyk](https://github.com/nunes39-cmyk)

---

⭐ Projeto desenvolvido para fins de aprendizado, prática de desenvolvimento web e construção de portfólio.
