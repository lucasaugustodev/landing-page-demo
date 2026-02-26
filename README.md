# FlowAI - Landing Page Demo

Landing page para captura de leads da FlowAI, uma plataforma ficticia de automacao de fluxos de trabalho com inteligencia artificial.

## Estrutura

```
landing-page-demo/
  index.html   - Pagina principal
  style.css    - Estilos da pagina
  README.md    - Este arquivo
```

## Funcionalidades

- **Header fixo** com navegacao e CTA
- **Hero section** com estatisticas e chamada para acao
- **Secao de recursos** com grid de 6 cards
- **Tabela de precos** com 3 planos (Starter, Pro, Enterprise)
- **Depoimentos** de clientes
- **Formulario de captura de leads** com campos de nome e email
- **Footer** com links institucionais

## Como usar

Abra o arquivo `index.html` diretamente no navegador. Nenhuma dependencia externa e necessaria alem da fonte Google Fonts (Inter).

## Formulario de Leads

O formulario captura **nome** e **email** do visitante. Ao submeter:

1. Os dados sao exibidos no console do navegador
2. Uma mensagem de sucesso e mostrada ao usuario

Para integrar com um backend, substitua o `console.log` no script por uma chamada `fetch` para sua API.

## Tecnologias

- HTML5
- CSS3 (variáveis CSS, Grid, Flexbox)
- JavaScript vanilla
- Google Fonts (Inter)

## Responsividade

A pagina e totalmente responsiva, adaptando-se a telas de desktop e mobile.
