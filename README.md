# Sipal — homepage institucional

Proposta de homepage em **HTML, CSS e JavaScript**, com conteúdo e fotografias de fontes institucionais da Sipal.

**Apresentação:** https://cauerrds.github.io/sipal/

## Abrir e editar

Abra `index.html` diretamente no navegador. O projeto não tem dependências ou etapa de build. Fontes e imagens estão incluídas; os links externos precisam de conexão.

- `index.html`: conteúdo e estrutura semântica.
- `styles.css`: identidade e estilos responsivos.
- `script.js`: menu móvel, abas dos negócios e indicação da seção atual.
- `assets/`: fotografias, logos e fontes locais.
- `ASSETS.md`: origem e resolução das imagens.
- `QA.md`: verificações da interface.

## Publicação

GitHub Pages publica a **raiz da branch `main`**. Alterações enviadas à branch são publicadas automaticamente. O arquivo `.nojekyll` mantém a distribuição estática. Os recursos usam caminhos relativos, compatíveis com `/sipal/`.

O repositório e a apresentação são públicos. A página mantém `noindex, nofollow` por ser uma proposta de apresentação, sem substituir o site oficial da Sipal.

## Identidade e experiência

Azul `#324368` e verde-água `#07A8A2`, observados nos materiais institucionais, tipografia Barlow e fotografias reais. A navegação apresenta a empresa, seus negócios, carreiras e contato. As abas aceitam clique e teclado; o menu móvel fecha com Escape ou ao navegar. A interface inclui foco visível, link para pular ao conteúdo, textos alternativos e suporte a movimento reduzido.

## Fontes

Consultadas em 9 de novembro de 2026:

- [Site Sipal](https://www.sipal.com.br/): marca e e-mail institucional.
- [LinkedIn da Sipal](https://www.linkedin.com/company/gruposipal/): perfil, sede, atuação e indicadores.
- [Página de carreiras](https://carreira.inhire.com.br/carreiras/carreiras-sipal/): segmentos, valores, trajetória e fotografias.
- [Portal de vagas Plooral](https://sipal.enlizt.me/): fotografia aérea.
- [Vagas oficiais](https://sipalpoc.inhire.app/vagas): destino do CTA de carreiras.

Foi adotado “mais de 50 anos” devido à divergência entre 1972 e 1973 nas fontes. Não foram incluídas capacidades, metas ou certificações sem confirmação. Algumas fotos institucionais estão disponíveis apenas em baixa resolução; os originais do marketing permitirão melhorar a nitidez em telas grandes.

O contato abre o aplicativo de e-mail para `comunica@sipal.com.br`. Não há formulário, coleta de dados ou analytics. Marca e fotografias pertencem aos respectivos titulares. A fonte Barlow está sob a licença SIL OFL, incluída nos assets.

## Verificação

Para verificar a sintaxe do JavaScript com Node.js:

```sh
node --check script.js
```

A revisão de interface está registrada em `QA.md`.
