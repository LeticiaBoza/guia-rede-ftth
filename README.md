# Guia Completo e Interativo de Redes FTTH ⚡

Este projeto é um guia interativo desenvolvido para facilitar o entendimento de redes de fibra óptica **FTTH (Fiber To The Home)**, com foco em iniciantes e técnicos em telecomunicações.

---

## 🚀 Funcionalidades Principais

* **Diagrama de Rede Interativo:** Visualize cada nó de conexão física (desde a OLT na central do provedor até a ONU/ONT na casa do cliente) e clique para obter detalhes técnicos específicos sobre cada componente.
* **Calculadora de Orçamento de Potência (Power Budget):** Simule na prática a atenuação óptica (perda de sinal em dB) gerada por fusões, acoplamentos de conectores, divisores (splitters de 1º e 2º nível) e distância física de fibra óptica. Veja em tempo real se o sinal final é considerado excelente, bom, crítico ou inoperante.
* **Comparativo de Tecnologias PON:** Tabela e cards comparativos detalhando as velocidades, taxa de divisão e aplicação de padrões do mercado como **EPON, GPON, XG-PON e XGS-PON**.
* **Guia de Ferramentas e Segurança:** Informações visuais sobre equipamentos essenciais (Power Meter, OTDR, Caneta Laser VFL, Clivador e Máquina de Fusão) e um alerta importantíssimo sobre segurança com lasers invisíveis infravermelhos.
* **Glossário Dinâmico com Busca:** Procure termos e filtre por categorias (Central, Rua, Cliente, Conceitos Físicos) em tempo real.
* **Modo Escuro / Claro (Dark/Light Theme):** Visual moderno de alta tecnologia com opção de alternância rápida de temas.

---

## 💻 Como Executar o Site Localmente

Como o projeto é feito com HTML5, CSS3 (Tailwind CSS) e JavaScript nativo e puro, **você não precisa compilar nada**. Existem várias formas simples de executá-lo:

### Método 1: Abrindo diretamente no navegador (Mais simples)
1. Vá até a pasta do projeto no seu computador.
2. Dê dois cliques no arquivo `index.html` (ou clique com o botão direito e selecione **Abrir com** e escolha seu navegador de preferência, como Chrome, Edge ou Firefox).

### Método 2: Usando o VS Code (Live Server)
Se você estiver utilizando o VS Code:
1. Instale a extensão **Live Server**.
2. Abra a pasta do projeto no VS Code.
3. Clique com o botão direito sobre o arquivo `index.html` e selecione **Open with Live Server**.
4. O site abrirá automaticamente na porta local `http://127.0.0.1:5500`.

### Método 3: Usando terminal (Python ou Node.js)
Se você tiver Python ou Node.js instalados e preferir usar o terminal:

* **Com Python:**
  Abra o prompt de comando (Terminal) na pasta do projeto e digite:
  ```bash
  python -m http.server 8000
  ```
  Depois, abra o seu navegador e acesse `http://localhost:8000`.

* **Com Node.js (npx):**
  Abra o terminal na pasta do projeto e execute:
  ```bash
  npx http-server -p 8000
  ```
  Depois, acesse `http://localhost:8000`.
