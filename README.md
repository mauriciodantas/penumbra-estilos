# Penumbra · Estilo Studio

Gerador de estilos para o app Penumbra, direto no navegador: https://mauriciodantas.github.io/penumbra-estilos/

- Controles de cor, curvas, tons divididos, LUT, película, captura e overlays, com prévia em tempo real.
- Imagem de referência: seis cenas de exemplo (paisagem, cidade, interiores e retratos) ou uma foto sua.
- Modo avançado: edição do JSON do estilo e do arquivo `.cube`.
- Exporta `.estilo.zip` (estilo + LUT com SHA-256), `.estilo.json`, `.cube` e prévia em PNG.
- Abre estilos e LUTs existentes (`.estilo.json`, `.estilo.zip`, `.cube`).

Tudo roda no seu navegador: nenhuma foto ou arquivo é enviado para fora.

## Formato

O formato Estilo 1.0 está descrito em [`spec/estilo-1.0.schema.json`](spec/estilo-1.0.schema.json), com nove exemplos em [`spec/examples`](spec/examples).

## Licenças

- Código da página: MIT (`LICENSE`).
- Exemplos de estilo: CC-BY-4.0.
- Fotos de referência embutidas: CC0 (domínio público), com autor e origem indicados na própria página.

## Publicar

A página é um único arquivo estático (`index.html`), servido pelo GitHub Pages a partir da branch `main`.
