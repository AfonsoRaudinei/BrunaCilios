# Designer

## Conceito Visual
- Estética feminina, elegante e acolhedora.
- Linguagem visual focada em beleza, autoestima e sofisticação.
- Combinação de rosa suave com dourado para transmitir delicadeza + premium.

## Paleta de Cores

### Rosa (base da marca)
- `#fce4ec` — rosa claro (fundos e degradês suaves)
- `#f8bbd0` — rosa médio claro (fundos secundários)
- `#ec407a` — rosa vibrante (acentos e destaques)
- `#d81b60` — rosa principal (títulos, botões, elementos de destaque)
- `#880e4f` — rosa escuro (textos de apoio e contraste)

### Dourado (identidade premium no header)
- `#c9a961` — base dourada principal do header
- `#d4af37` — dourado de destaque e brilho principal
- `#f9e79f` — reflexos claros no degradê
- `#f4e4c1` — tom quente de transição no degradê
- `#3a2a0a` e `#5a4a2a` — textos sobre fundo dourado

### Neutras
- `#ffffff` — cartões e áreas de conteúdo
- `#3a2a0a` — marrom escuro de contraste para tipografia no header
- `#5a4a2a` — marrom médio para subtítulos no header

## Tipografia
- Fonte principal: `-apple-system, BlinkMacSystemFont, 'Segoe UI', 'Helvetica Neue', Arial, sans-serif`
- Estilo geral: sem serifa, limpo, moderno e legível.
- Títulos com peso médio/alto (`600–700`), textos com bom espaçamento de linha.

## Fundos e Superfícies
- Fundo principal da página com degradê vertical rosa (`#fce4ec → #f8bbd0`).
- Seções em branco com cantos arredondados (`12px`) e sombras suaves.
- Card de diferenciais com visual “glass” leve (transparência + blur + sombra interna).

## Componentes-Chave
- **Header premium:** degradê dourado animado com efeito de brilho e textura.
- **Cards e seções:** sombras leves, bordas arredondadas e sensação de profundidade.
- **Botão primário:** degradê rosa (`#ec407a → #d81b60`), hover com elevação.
- **Carrosséis:** imagens grandes, loop contínuo, pausa no hover, leve zoom no foco.
- **Box promocional:** bloco rosa com borda suave e itens em fundo translúcido.
- **Cards de contato:** layout em grid responsivo com animação de hover.
- **Botão flutuante:** destaque visual com escala no hover.

## Animações e Movimento
- `goldGlitter` (8s, infinito): deslocamento do degradê dourado no header.
- `shimmer` (3s, infinito): textura diagonal em movimento.
- `shine` (4s, infinito): faixa de brilho passando sobre o header.
- `scroll` (30s, linear, infinito): rolagem automática dos carrosséis.
- Transições curtas (`0.2s–0.3s`) em hover para feedback visual.
- Lightbox com animações de entrada (`fadeIn` e `zoomIn`).

## Layout e Responsividade
- Conteúdo centralizado (`max-width: 1200px`) com respiro lateral.
- Estrutura em blocos/seções empilhadas para leitura fluida.
- Grid adaptável no contato (`auto-fit` + `minmax`).
- Ajustes mobile em `max-width: 768px` (tipografia e largura dos cards do carrossel).

## Direção de Imagem
- Uso intenso de fotos reais (espaço, profissional, clientes e trabalhos).
- Imagens em destaque com preenchimento total (`object-fit: cover`) nos carrosséis.
- Tom visual romântico, delicado e profissional alinhado ao nicho de beleza.
