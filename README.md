# Landing Page Responsiva

Este repositório contém o código-fonte de uma interface web estática do tipo *Landing Page*, desenvolvida nativamente com HTML5, CSS3 e JavaScript. O projeto tem como foco a aplicação de práticas de estruturação semântica, design adaptativo para múltiplos *breakpoints* e manipulação do Modelo de Objeto de Documentos (DOM) na camada do cliente.

## 1. Arquitetura e Engenharia de Interface

A aplicação opera estritamente na camada de apresentação (Front-end), com sua estrutura visual e interativa segmentada nos seguintes pilares:

### 1.1. Estrutura Semântica e Componentização (HTML5)
A interface é baseada em uma arquitetura de página única (*Single-Page*), particionada em seções de conteúdo sequencial: *Intro*, *Top 3*, *Jobs*, *Gallery*, *Pricing* e *Contact*. A marcação semântica garante a organização do fluxo de informação e facilita a navegação ancorada.

### 1.2. Design Responsivo e Estilização (CSS3)
* **Controle de Layout:** Utilização de *Media Queries* para a adaptação fluida da interface geométrica em diferentes resoluções de tela (ambientes *desktop*, *tablet* e *mobile*).
* **Identidade Visual:** Implementação de uma paleta de cores orientada a um tema escuro (*Dark Mode*), com controle rigoroso de tipografia e espaçamentos globais.
* **Navegação Fixa:** Barra de navegação com comportamento de fixação superior (estática) para garantir acesso contínuo ao roteamento interno.

### 1.3. Interatividade e Comportamento (JavaScript Vanilla)
A camada de script é responsável pela orquestração de eventos e gerenciamento de estado da interface de usuário (UI):
* **Navegação Dinâmica:** Implementação de rolagem suave (*smooth scrolling*) ao acionar âncoras no menu de roteamento.
* **Menu Mobile:** Lógica de manipulação de estado para acionamento e recolhimento do menu de navegação adaptativo (tipo *hambúrguer*) em resoluções limitadas.

## 2. Requisitos de Ambiente

Por se tratar de uma aplicação de arquivos estáticos estritos (*Vanilla*), o projeto é *plug-and-play* e não exige o instanciamento de servidores locais, gerenciadores de pacotes ou processos de compilação (*build*).

## 3. Instruções de Execução Local

1. Realize a clonagem do repositório localmente:
```bash
git clone https://github.com/fhugomp/Landing-page.git
```

2. Acesse o diretório do projeto:
```bash
cd Landing-page
```

3. Inicialize a aplicação:
Abra o arquivo `index.html` na raiz do diretório através de qualquer navegador web moderno.

## 4. Implantação e Demonstração Online

O projeto encontra-se hospedado e servido de forma contínua através da infraestrutura de arquivos estáticos do GitHub Pages.

> **Ambiente de Produção:** [Acessar a Landing Page](https://fhugomp.github.io/Landing-page/)

## 5. Referência Visual (Preview)

### Interface Desktop
![Versão do desktop](./assets/images/Desktop-version.jpeg)

### Interface Mobile
<p align="center">
  <img src="./assets/images/Mobile-version.jpeg" alt="Versão do Mobile" style="height: 750px;"/>
</p>
