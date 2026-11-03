# Volume Memory

Jogo da memória com cartas de imagens, feito com HTML (`index.html`), CSS (`style.css`) e JavaScript (dentro do `index.html`), usando apenas DOM e eventos do JavaScript puro.

## Como jogar

- O tabuleiro tem 10 cartas (5 pares de imagens), embaralhadas.
- O volume começa em **30**.
- Vire 2 cartas por vez:
  - Iguais: o par fica verde.
  - Diferentes: as duas cartas desviram e o erro é contado.
- A cada **4 erros** o volume perde 10 (mínimo 0) e o tabuleiro continua o mesmo.
- Achou os 5 pares: **+10 de volume** (máximo 100) e uma nova rodada começa, com as cartas embaralhadas de novo.

## Imagens das cartas

Crie uma pasta `imagens` ao lado do `index.html` e coloque 5 imagens de personagens e a imagem do verso das cartas, com estes nomes:

```
volume-memory/
  index.html
  style.css
  README.md
  imagens/
    personagem1.png
    personagem2.png
    personagem3.png
    personagem4.png
    personagem5.png
    verso.png
```

Se usar outros nomes ou `.jpg`, edite a lista `figuras` no `index.html` (campo `src`) e a variável `imagemVerso`.

Use apenas imagens que você tem direito de usar (suas, de licença livre ou de sites de arte gratuita, como OpenGameArt ou Kenney).

## Como rodar

Abra o `index.html` no navegador (ou use a extensão Live Server no VS Code).

## Publicar no GitHub e na Vercel

1. Crie um repositório no GitHub e envie os arquivos (`index.html`, `style.css`, `README.md` e a pasta `imagens`).
2. Na Vercel, clique em **Add New > Project** e importe o repositório.
3. Não precisa de build nem de configuração: deixe o *Framework Preset* como **Other** e clique em **Deploy**.
