# Template - Amigurumis Exus e Pombagiras

Landing low-ticket para produto digital de amigurumi espiritual/religioso. Use como base para ofertas de artesanato com nicho simbolico, colecao pronta, entrega digital, dois pacotes e bonus.

## Sobre o produto original

- **Produto**: Biblioteca de Exus e Pombagiras em Amigurumi, com mais de 100 modelos prontos organizados por entidade.
- **Nicho**: Artesanato, amigurumi, croche e espiritualidade.
- **Tipo**: Produto digital low-ticket.
- **Persona**: Artesas e crocheteiras que ja tem nocao basica de croche/amigurumi e querem produzir pecas simbolicas para uso pessoal, presente, colecao ou venda.
- **Mecanismo principal**: modelos prontos em PDF, fotos de referencia e organizacao por entidade para nao comecar do zero.

## Oferta

- **Pacote Basico**: R$27,90.
- **Pacote Completo**: R$37,90.
- **Diferenca estrategica**: por R$10 a mais, o completo inclui 5 bonus exclusivos.
- **Garantia**: 15 dias.
- **Entrega**: acesso digital enviado pelo e-mail informado na compra.

## Bonus

1. Kit de Acabamento e Apresentacao.
2. Lista de Materiais para Amigurumis Espirituais.
3. Guia de Organizacao da Colecao.
4. Ficha de Identidade Simbolica das Entidades.
5. Acesso ao Grupo de Artesas no WhatsApp.

## Paleta de cores

| Token | HEX | Uso |
|-------|-----|-----|
| Fundo escuro | `#2a1208` / `#3b1a0b` | Oferta, bloco de recapitulacao e secoes escuras |
| Creme quente | `#fff4dc` / `#f8dfad` | Hero e blocos demonstrativos |
| Bege claro | `#f3e8d8` / `#f7f2ea` | Beneficios e FAQ |
| Coral urgencia | `#ef5b4d` | Bloco de urgencia |
| Azul destaque | `#2563eb` aprox. | Palavra de destaque, titulo do plano completo |
| Verde/lime CTA | `#a3e635` aprox. | Botoes principais |

## Estrutura

1. Hero de venda imediata com mockup principal, bullets e CTA.
2. Demonstrativo visual de organizacao do pack.
3. Beneficios do produto.
4. Headline de urgencia com CTA.
5. Persona/uso ideal.
6. Tudo que vai receber.
7. Bloco com 5 bonus.
8. Oferta com Pacote Basico e Pacote Completo.
9. Garantia de 15 dias.
10. Como vai ser o acesso.
11. FAQ com 7 perguntas.
12. Rodape legal/compra segura.

## Tracking e checkout

- **Pixel UTMify**: `6a3d34bc1bae5a7def2ef36a`.
- **Checkout Wiapy**:
  - Basico: `https://pay.wiapy.com/wrElruxdCfT`
  - Completo: `https://pay.wiapy.com/y3WrCBBqaT`

## Arquivos e assets

- Usa `index.html`, `styles.css`, `script.js` e pasta `assets/`.
- Imagens principais ficam em `assets/optimized/`.
- O HTML carrega `assets/site-critical.css` e preload do `mockup-principal.webp`.
- Mantem dependencias externas de fonte Google, Phosphor Icons, TailwindCSS shop e scripts UTMify.

## Decisoes criticas / regras

- Nao remover o pixel UTMify do `<head>`.
- Nao trocar os links dos dois CTAs de checkout sem atualizar tambem o `INFO.md`.
- Manter o Pacote Completo como oferta de maior valor por apenas R$10 a mais.
- Manter a garantia como 15 dias; se mudar para outro prazo, atualizar hero, checkout, garantia, FAQ e rodape.
- O nicho espiritual exige cuidado com copy: preservar tom respeitoso, simbolico e orientado a artesanato, sem promessas religiosas absolutas.
- O template depende da pasta `assets/`; copiar apenas o HTML quebra os mockups e selos.

## Status

- **Status**: Producao/importado da pagina enviada.
- **Tamanho**: ~60 KB HTML + ~10 KB CSS + assets locais.
