# Colheita Feliz Offline

Reconstrução experimental, não oficial, de um jogo de fazenda inspirado na Colheita Feliz da época do Orkut.

## Jogar no navegador

Após ativar o **GitHub Pages**, o jogo ficará disponível em:

https://walarconborges.github.io/colheita-feliz-offline/

Para ativar: **Settings → Pages → Build and deployment → Deploy from a branch → main → / (root) → Save**.

## Como jogar offline

Para jogar sem internet, baixe **o repositório completo** em **Code → Download ZIP**, extraia o ZIP e abra `index.html` no Chrome ou Edge. **Não baixe apenas `index.html`:** ele depende das imagens nas pastas `assets/`.

## Organização dos gráficos

Os gráficos estão em arquivos separados, mantendo os caminhos utilizados pelo jogo:

- `assets/original/` — terrenos, ferramentas e recursos originais (32 arquivos).
- `assets/crops/` — plantações (67 arquivos).
- `assets/animals/` — animais (10 arquivos).
- `assets/decor/` — decorações (15 arquivos).

Para incluir ou substituir gráficos, use os caminhos correspondentes no código. As imagens deixaram de ser incorporadas em Base64 ao HTML.

## Salvamento

O jogo salva o progresso no armazenamento local do navegador. Cada navegador ou dispositivo guarda seu próprio progresso. Para mover de um aparelho para outro, use as opções **Exportar progresso** e **Importar progresso** do jogo, guardando o arquivo JSON em local seguro.

## Projeto

Versão inicial publicada: **0.3**. Os gráficos agora ficam em arquivos separados para facilitar melhorias no cenário isométrico, ícones e animações.

**Nota sobre recursos gráficos:** esta edição experimental utiliza materiais recuperados de arquivos de jogos antigos para avaliação e reconstrução. A presença desses arquivos neste repositório não significa que estejam liberados para redistribuição comercial.

## Animais e produção (versão 0.4)

Abra **Animais** para comprar galinhas, patos, ovelhas e porcos. Os animais começam a produzir após a compra; os tempos respeitam a velocidade selecionada em **Opções**. Quando a produção estiver pronta, use **Coletar** na janela dos animais ou clique diretamente no animal dentro do cercado. Os produtos vão para o estoque do criatório e também aparecem no **Celeiro**, onde podem ser vendidos. Vaca, coelho e galo permanecem decorativos nesta versão.

As miniaturas dos animais foram mantidas provisoriamente, com escala limitada para evitar distorção. A conversão e integração dos sprites animados originais ainda estão pendentes.
