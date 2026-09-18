# 🎬 Ferramenta de Apresentação Técnica & Estudo de Interação com IA

## Projeto: Plataforma Unificada de Gestão de Delivery (PUGD)

Este repositório reúne os artefatos de desenvolvimento da aplicação web interativa de apresentação técnica (`apresentacao.html`), bem como a documentação e estudo metodológico das interações de engenharia de software realizadas em regime de *pair programming* com Inteligência Artificial.

---

## 📁 Estrutura de Arquivos

| Arquivo | Descrição |
| :--- | :--- |
| **`apresentacao.html`** | Aplicação Web interativa completa em formato Single Page Application (SPA). Contém deck de slides executivos, hub de diagramas arquiteturais com controles dinâmicos de Zoom e Pan (Mermaid.js) e simulador operacional de pedidos e cozinha (delivery vs. retirada no balcão). |
| **`historico_conversa.html`** | Visualizador estilizado e responsivo com o registro passo a passo das 9 etapas de concepção e refinamento do projeto, preparado com estilos para impressão direta e exportação em PDF. |
| **`historico_conversa.md`** | Documento estruturado em Markdown contendo a transcrição integral dos prompts, respostas técnicas da IA e decisões de arquitetura. |

---

## 🤖 Especificações Técnicas da Inteligência Artificial

A construção, depuração e evolução dos componentes foram desenvolvidas em colaboração com o modelo de inteligência artificial através de um fluxo contínuo de refinamento iterativo.

- **Modelo de IA:** Gemini 3.8 Flash
- **Nível de Raciocínio (Thinking Effort):** High
- **Ambiente de Desenvolvimento:** Antigravity IDE (Google DeepMind)
- **Versão do Antigravity IDE:** v2.5.5 (Build 1.107.0 / Commit `ecfbad74d93962fc8ca485d93ab9b4f3d4cb6cf8`)
- **Modo de Interação:** Chat Interativo de Pair Programming (*Human-in-the-Loop*)

---

## 🚀 Como Executar

Não é necessária nenhuma instalação de dependências ou servidor HTTP complexo:
1. Clone este repositório:
   ```bash
   git clone https://github.com/ThalesRDC/Apresenta-o-de-projeto-HTML.git
   ```
2. Abra o arquivo `apresentacao.html` diretamente em qualquer navegador moderno para rodar a apresentação e o simulador.
3. Abra `historico_conversa.html` para consultar a trilha de prompts e imprimir o relatório em PDF (via atalho `Ctrl + P` ou botão nativo na interface).
