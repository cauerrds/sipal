# Verificação da homepage

Revisão em 9 de novembro de 2026, no navegador integrado.

- Desktop, 1440 × 1000: hierarquia, header, hero, indicadores e seção de negócios inspecionados visualmente; sem transbordamento horizontal.
- Mobile, 390 × 844: hero, tipografia, menu, valores e indicadores inspecionados; sem transbordamento horizontal.
- Mobile estreito, 320 × 720: nenhum elemento excede a largura útil.
- Paisagem, 740 × 360: menu limitado à altura disponível e com rolagem interna, permitindo alcançar todos os links.
- Abas: os quatro painéis exibem o conteúdo esperado; seleção por teclado com seta confirmada.
- Menu: abre e fecha; Escape devolve o foco ao botão; navegação fecha o painel.
- Retorno ao início: corrigido e confirmado em scrollY = 0.
- Todos os arquivos locais referenciados existem, as âncoras têm destinos e não existem IDs duplicados.
- Nenhum erro ou aviso no console durante a revisão de navegação e abas.
- JavaScript verificado com `node --check`.
- Site local e destino oficial de vagas respondem HTTP 200.

Limitação: a resolução disponibilizada pelas fontes oficiais restringe a nitidez de algumas fotografias em telas grandes. Ver ASSETS.md. A revisão não equivale a uma auditoria completa WCAG ou a testes em dispositivos físicos.
