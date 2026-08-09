# Painel de Pré-Vendas · Período Trainee 2026.1

Painel interativo de análise de prospecção da UFABC Jr., construído a partir da
consolidação das 45 abas individuais da Planilha de Prospecção PT 2026.1
(dados de 17 de julho a 5 de agosto de 2026).

## Conteúdo

Arquivo único e autocontido: `index.html`. Todo o CSS, o JavaScript e o logo
(em base64) estão embutidos. Não há dependências, build ou instalação.

## Seções

1. Panorama do período
2. Onde o funil vaza
3. Para quem estamos falando
4. Ritmo e gestão do pipeline
5. Qualidade da base e da informação
6. Como estamos contra o mercado

## Recursos interativos

- Funil alternável entre volume absoluto e percentual do topo
- Taxa de resposta por setor alternável entre base completa e base ajustada
- Tooltips em todos os gráficos
- Simulador de recuperação de pipeline com controles de percentual retomado e taxa de resposta

## Privacidade

Todas as análises são agregadas. Nenhum resultado individual de pré-vendedor é
identificado no painel.

## Deploy

Site estático. No Vercel, basta importar o repositório: o framework preset é
"Other" e não há comando de build. O `index.html` na raiz já é servido direto.

## Fontes externas

As fontes tipográficas vêm do Google Fonts. Sem internet, o painel cai para as
fontes do sistema e continua funcionando normalmente.
