# 🎴 Oráculo Diário & Compêndio de Tarot

Aplicação web estática, minimalista e 100% *client-side*, inspirada no conceito do *Pocket Oracle* com estética de tinta eletrônica (*e-paper*). Desenvolvida para suporte diário e aprofundamento nos estudos de Tarot e simbologias correlatas.

---

## ✨ Funcionalidades

- **Carta do Dia Determinística:** Selecionada por um algoritmo de hash baseado na data civil local (`YYYY-MM-DD`). A carta permanece idêntica ao longo de todo o dia, sem recarregar um resultado diferente.
- **Ocultação Intencional:** As lâminas iniciam viradas e os dados interpretativos (nome, palavras-chave, mensagem e reflexão) só se manifestam no DOM após o toque da consulente.
- **Tiragem de Três Cartas:** Modo clássico (Passado, Presente e Futuro) com sorteio pseudoaleatório e rotação individual.
- **Compêndio dos 78 Arcanos:** Catálogo com os 22 Arcanos Maiores e os 56 Menores (Paus, Copas, Espadas e Ouros), ilustrações históricas de Pamela Colman Smith (Rider-Waite 1909) e busca em tempo real.
- **Estética E-Paper:** Modo monocromático de alto contraste com textura suave de papel e chaveador opcional para as cores originais das gravuras.
- **Zero Dependências:** Funciona diretamente no navegador (HTML, CSS via Tailwind CDN e JavaScript puro), sem necessidade de backend, banco de dados ou compilação.

---

## 🚀 Como Executar Localmente

Basta clonar o repositório e abrir o arquivo `index.html` em qualquer navegador:

```bash
git clone [https://github.com/williamsantana-dev/tarot.git](https://github.com/williamsantana-dev/tarot.git)
cd tarot
open index.html # ou duplo clique no arquivo
