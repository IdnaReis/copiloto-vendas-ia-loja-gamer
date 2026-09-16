# 🎮 Copiloto de Vendas com IA para Loja Gamer

Projeto desenvolvido para o desafio **"Copiloto de Vendas com IA para Atendimento ao Cliente"** da trilha *Primeiros Passos com Inteligência Artificial* (DIO).

## 🎯 Tema escolhido

Um **copiloto de vendas** para apoiar atendentes de uma **loja gamer** (produtos como notebooks, placas de vídeo, periféricos e acessórios), ajudando a responder dúvidas técnicas e objeções de clientes durante o atendimento.

## 👤 Quem é o usuário principal

O **vendedor(a)** da loja — presencial ou via chat/WhatsApp — que atende clientes com diferentes níveis de conhecimento técnico sobre hardware e produtos gamer.

## ❗ Problema que a solução resolve

Vendedores nem sempre têm domínio técnico profundo sobre todos os produtos (ex: diferenças entre placas de vídeo, compatibilidade de componentes) e podem perder vendas por não saber responder dúvidas ou contornar objeções de preço/qualidade na hora certa.

O copiloto atua como um **assistente de bolso**: o vendedor descreve a dúvida ou objeção do cliente, e a IA sugere uma resposta clara, técnica quando necessário, e persuasiva.

## 🧠 Abordagem usada

**Copiloto de vendas via prompt estruturado**, sem necessidade de aplicação completa — a IA (ChatGPT, Claude, etc.) é usada diretamente com um prompt fixo + base de conhecimento em Markdown, simulando um assistente interno da loja.

## 📚 Base de conhecimento utilizada

Arquivos simples em Markdown, representando informações reais que uma loja teria disponíveis:

```
knowledge/
  produtos.md              → catálogo resumido de produtos e especificações
  objecoes.md              → objeções comuns de clientes e como contornar
  perguntas-frequentes.md  → dúvidas técnicas recorrentes
```

## 💬 Exemplo de conversa gerada

Veja o exemplo completo em [`exemplos/conversa-exemplo.md`](exemplos/conversa-exemplo.md), mostrando o copiloto respondendo a uma objeção de preço e uma dúvida técnica sobre placas de vídeo.

## 🔧 Como usar

1. Abra o prompt em [`prompt/prompt-base.md`](prompt/prompt-base.md)
2. Cole o prompt em uma IA de sua preferência (ChatGPT, Claude, etc.)
3. Anexe ou cole o conteúdo dos arquivos da pasta `knowledge/` como contexto
4. Descreva a dúvida ou objeção do cliente
5. Receba uma sugestão de resposta pronta para o vendedor usar

## 🚀 Possíveis melhorias futuras

- Integrar o copiloto a um chatbot real (WhatsApp Business API ou site da loja)
- Expandir a base de conhecimento com preços e estoque em tempo real
- Adicionar histórico de conversa para sugestões mais contextualizadas
- Criar métricas de taxa de conversão por sugestão utilizada

## 🛠️ Tecnologias

- Prompt Engineering
- Markdown (base de conhecimento)
- IA generativa (ChatGPT / Claude)

---

Projeto feito por **Idna Reis** — [LinkedIn](https://linkedin.com/in/idna-reis) | [GitHub](https://github.com/IdnaReis)
