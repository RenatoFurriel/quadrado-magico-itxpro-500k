# Quadrado Mágico ITXPRO 500k — Planejador de Funil

Ferramenta interativa para simular os **4 funis de vendas** do *Quadrado Mágico ITXPRO 500k* e a **receita projetada** das mentorias GRC TI.

## O que faz

- **Menu lateral** com os 4 funis: **EVENTOS · ASSESSMENT · SHT · PROSPECÇÃO**.
- O funil selecionado aparece em tela cheia, como um **funil que afunila visualmente**.
- **Slider por etapa (0 a 10.000 leads)** + campo numérico editável, mostrando:
  - número absoluto de leads,
  - **% em relação ao topo** do funil,
  - **conversão etapa-a-etapa** (↓ %).
- **Painel de produtos** com os 3 tickets (digitados na hora):
  - MENTORIA GRC TI **START**, **PRO**, **MASTER**;
  - você lança **vendas × ticket** de cada produto → **receita total projetada** (soma) em tempo real.
- **Persistência local** (localStorage): cada funil guarda seus próprios valores ao alternar e ao recarregar.

Paleta: branco predominante, com preto e laranja como cores complementares. Tudo cabe em **uma única tela** (1366×768 para cima).

## Usar localmente

Basta abrir o arquivo `index.html` no navegador (duplo clique).

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie estes arquivos:
   ```bash
   git init
   git add .
   git commit -m "Quadrado Mágico ITXPRO 500k — planejador de funil"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/SEU_REPO.git
   git push -u origin main
   ```
2. No GitHub: **Settings → Pages**.
3. Em *Build and deployment*, selecione **Source: Deploy from a branch**, branch **main** e pasta **/ (root)**. Salve.
4. Aguarde ~1 min e acesse a URL gerada (`https://SEU_USUARIO.github.io/SEU_REPO/`).

O arquivo `.nojekyll` já está incluído para o Pages servir o site sem processamento Jekyll.

## Estrutura

```
index.html    # aplicação completa (HTML + CSS + JS, sem dependências)
README.md     # este arquivo
.nojekyll     # desativa o Jekyll no GitHub Pages
```
