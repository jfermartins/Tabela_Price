# Tabela Price

## Descrição

Este projeto é uma aplicação web desenvolvida em Java Server Pages (JSP) que implementa a Tabela Price (também conhecida como Sistema Francês de Amortização) para cálculo de empréstimos. Foi desenvolvido como um desafio acadêmico para a disciplina de Programação Orientada a Objetos, com o objetivo de aplicar os conceitos aprendidos. A Tabela Price é um método de amortização de dívidas caracterizado por parcelas fixas, onde a proporção de juros e amortização varia ao longo do tempo.

## Funcionalidades

*   Cálculo da Tabela Price com base no valor do empréstimo, taxa de juros e número de parcelas.
*   Exibição detalhada de cada parcela, incluindo saldo devedor, prestação, juros e amortização.
*   Interface de usuário simples e intuitiva para entrada de dados e visualização dos resultados.

## Tecnologias Utilizadas

*   **Java Server Pages (JSP):** Para a lógica de backend e renderização dinâmica das páginas web.
*   **HTML5:** Estrutura das páginas web.
*   **CSS3:** Estilização básica.
*   **Bootstrap 4.1.3:** Framework CSS para um design responsivo e moderno.

## Como Executar o Projeto

### Pré-requisitos

Para executar este projeto, você precisará ter instalado:

*   Um servidor de aplicação Java (ex: Apache Tomcat).
*   Java Development Kit (JDK) 8 ou superior.
*   Uma IDE compatível com projetos web Java (ex: NetBeans, IntelliJ IDEA, Eclipse).

### Instalação e Configuração

1.  **Clone o repositório:**

    ```bash
    git clone https://github.com/jfermartins/Tabela_Price.git
    cd Tabela_Price
    ```

2.  **Importe o projeto na sua IDE:**

    *   **NetBeans:** Abra o NetBeans, vá em `File > Open Project...` e selecione a pasta `Tabela_Price` clonada.
    *   **Outras IDEs:** Importe o projeto como um projeto web existente ou um projeto Maven/Gradle, se aplicável (este projeto parece ser um projeto NetBeans padrão).

3.  **Configure o servidor de aplicação:**

    *   Adicione o seu servidor Tomcat (ou similar) à sua IDE.
    *   Implante o projeto `Tabela_Price` no servidor de aplicação.

4.  **Execute a aplicação:**

    *   Inicie o servidor de aplicação.
    *   Abra seu navegador e acesse `http://localhost:8080/Tabela_Price/` (a porta e o contexto podem variar dependendo da sua configuração).

## Estrutura do Projeto

```
Tabela_Price/
├── README.md
├── build.xml
├── lib/                   # Bibliotecas externas
├── nbproject/             # Arquivos de configuração do NetBeans
├── src/
│   └── conf/
│       └── MANIFEST.MF
└── web/                   # Conteúdo web da aplicação
    ├── META-INF/
    │   └── context.xml
    ├── WEB-INF/
    │   ├── jspf/          # Fragmentos JSP (header, footer, menu)
    │   │   ├── footer.jspf
    │   │   ├── header.jspf
    │   │   └── menu.jspf
    │   └── web.xml        # Descritor de implantação web
    ├── index.jsp          # Página inicial
    └── tabela-price.jsp   # Página principal da calculadora Tabela Price
```

## Autor

*   **Jane Fernanda Martins**



