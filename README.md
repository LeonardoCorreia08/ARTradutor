# AR Tradutor PRO

Uma aplicação web progressiva (PWA) de realidade aumentada voltada para reconhecimento inteligente de objetos em tempo real via câmera, oferecendo tradução instantânea para múltiplos idiomas, síntese de voz, histórico de detecção e feedback interativo dos usuários.

---

## 🌍 Funcionalidades Principais

* **Reconhecimento de Objetos por IA:** Utiliza TensorFlow.js em conjunto com o modelo `coco-ssd` para detectar objetos diretamente pelo feed da câmera em tempo real.
* **Tradução Multilíngue:** Suporte nativo para tradução dos rótulos detectados em vários idiomas (Português, Inglês, Espanhol e Francês).
* **Síntese de Voz (Text-to-Speech):** Reprodução em áudio opcional dos nomes dos objetos traduzidos conforme são identificados.
* **Painel de Histórico:** Acompanhamento estatístico dos objetos detectados com contadores e opção de limpeza de dados.
* **Captura de Tela e Feedback:** Permite pausar e capturar a imagem atual para confirmar detecções ou corrigir rótulos imprecisos.
* **Modos de Visualização:** Alternância entre modo claro e escuro, além de suporte para troca de câmera (frontal e traseira).

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 / CSS3:** Estruturação semântica e interface customizada com design responsivo.
* **JavaScript (Vanilla):** Lógica da aplicação, manipulação do DOM e controle de eventos.
* **TensorFlow.js & COCO-SSD:** Modelos de machine learning para detecção de objetos no navegador.
* **Web APIs:** `MediaDevices` (câmera), `SpeechSynthesis` (voz) e `Service Worker` (PWA).

---

## 🚀 Como Executar o Projeto

Como o projeto consiste em um arquivo HTML único (`index.html`) que importa bibliotecas via CDN:

1. Salve o código fornecido em um arquivo local, por exemplo, `index.html`.
2. Abra o arquivo diretamente em qualquer navegador web moderno que suporte acesso à webcam (Google Chrome, Firefox, Edge, Safari).
3. Conceda permissão para uso da câmera e clique em **"Iniciar Câmera"** para começar a explorar o reconhecimento de objetos.

---

<div align="center">
  <p>Desenvolvido com 💻 por <a href="https://github.com/LeonardoCorreia08" target="_blank">Leonardo Correia</a></p>
  <a href="#top">Voltar ao topo</a>
</div>
