# BRAZILIANS.ME

Protótipo navegável do portal 360° para brasileiros vivendo fora do Brasil.

## Executar localmente

Como o projeto é estático e não possui backend, basta servir esta pasta com um servidor que faça fallback para `index.html`:

```bash
npx serve -s .
```

Abra a URL informada pelo comando. Para uma opção sem instalação, também é possível usar `python3 -m http.server`, começando pela homepage e navegando pelos links.

## Páginas disponíveis

- `/` — homepage, mapa-múndi demonstrativo e exploração por país
- `/portugal` — visão geral de Portugal
- `/portugal/lisboa` — comunidade, vida prática e retrato demonstrativo de Lisboa
- `/familia` — Família 360°
- `/plh` — Português como Língua de Herança
- `/trabalho` — Trabalho e carreira
- `/saude` — Saúde e bem-estar
- `/servicos` — categorias e perfil demonstrativo da Kelly Ilkyo
- `/historias` — histórias demonstrativas
- `/comunidade` — prévia da comunidade
- `/ferramentas` — interfaces demonstrativas de ferramentas
- `/participar` — formulário visual de contribuição
- `/estados-unidos`, `/espanha`, `/japao`, `/irlanda` — páginas iniciais demonstrativas

## Fontes e mapa

O mapa usa Leaflet e tiles públicos do OpenStreetMap, com atribuição visível no mapa. Os pins representam Portugal, Estados Unidos, Espanha, Japão, Irlanda, França, Austrália e Canadá; são pontos de entrada editoriais, não estatísticas populacionais.

A direção editorial foi pesquisada a partir das páginas públicas de [Brasileiras pelo Mundo](https://www.brasileiraspelomundo.com/) e [Brasileiros no Exterior](https://www.brasileirosnoexterior.org/). O protótipo usa temas e referências de cobertura, mas não reproduz artigos ou textos protegidos. As imagens da homepage vêm do Unsplash e são apenas ambientação visual.

## Escopo

Os dados são ilustrativos e estão separados em `data.js`. Não há autenticação, banco de dados, pagamentos, comunidade real, profissionais reais ou envio de formulário. Estatísticas e perfis aparecem explicitamente marcados como demonstrativos.

## Próxima fase recomendada

Validar a arquitetura de conteúdo com brasileiros em Portugal, definir o modelo editorial e substituir os exemplos por dados revisados e fontes verificáveis antes de conectar CMS, busca, diretório profissional ou funcionalidades de comunidade.