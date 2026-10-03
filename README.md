# Manual do Business Partner Teduc

Guia de atuação consultiva para os Business Partners da Teduc, publicado como uma única
página web autocontida. Aplica o Teduc Design System (Laranja `#F69243`, Grafite `#333333`,
Cinza-lilás `#A2A5CA`, tipografia Inter).

**Versão 1.0 · adoção operacional em 19/09/2026**
Validação institucional: Cintia Alves · Dúvidas e sugestões: contato@teduc.com.br

## O que o manual contém

31 capítulos em sete partes, pensados para consulta rápida durante o trabalho:

| Parte | Conteúdo |
| --- | --- |
| Comece aqui | Rotas por situação e como ler o status de cada orientação |
| I · Fundamentos | A Teduc, Build Intelligence, papel do parceiro, modelos de parceria, condições comerciais, primeiros 30 dias |
| II · Portfólio | Business, Education, Public, Products & Ventures e como conectar necessidades |
| III · Oportunidade | Seleção de contas, abordagem, descoberta, qualificação, registro e Opportunity & Fit |
| IV · Proposta | Proposta consultiva, preço e negociação, objeções, fechamento e passagem |
| V · Valor | Evidência de valor, expansão e ativos, rotina de gestão |
| VI · Ferramentas | Briefing, Opportunity & Fit, checklist de proposta, handoff e revisão de valor |
| VII · Referência | Conduta e FAQ, glossário e governança do manual |

Recursos de uso: busca em todo o texto, sumário com indicação de posição, botões de copiar
nos roteiros e modelos, checklists com contador, calculadora de priorização de contas,
favoritos por capítulo, ajuste de tamanho do texto e folha de estilo para impressão em PDF.
Favoritos e preferências ficam no navegador de quem lê, sem servidor.

## Versões e idiomas

O app adaptativo existe em quatro idiomas, com o mesmo conteúdo e a mesma estrutura de
capítulos. O seletor de idioma fica no topo, ao lado do controle de tamanho de texto, e
preserva o capítulo aberto ao trocar de língua.

| Arquivo | Idioma |
| --- | --- |
| `index.html` | Português (Brasil) — padrão |
| `en.html` | Inglês (Estados Unidos) |
| `es.html` | Espanhol |
| `fr.html` | Francês |
| `documento.html` | Versão documento, em português, para leitura linear e impressão em PDF |

Todos os arquivos são autocontidos: CSS, JavaScript e logos (em base64) estão dentro de
cada um. A única dependência externa é a fonte Inter, carregada do Google Fonts, com
fallback para fontes do sistema. Os links entre idiomas são relativos, então funcionam em
qualquer subdiretório.

## Como publicar

### GitHub Pages

1. Suba o conteúdo desta pasta para a raiz do repositório.
2. Em **Settings → Pages**, selecione a branch e a pasta `/ (root)`.
3. A página fica disponível em `https://<organizacao>.github.io/<repositorio>/`.

O arquivo `.nojekyll` evita que o GitHub Pages processe o conteúdo com o Jekyll.

### Localmente

Abra `index.html` no navegador, ou sirva a pasta com `python3 -m http.server`.

## Estrutura

```
index.html                      App adaptativo em português (padrão)
en.html · es.html · fr.html     App adaptativo em inglês, espanhol e francês
documento.html                  Versão documento em português, para impressão
assets/teduc-logo-branco.png    Logo oficial, versão branca
assets/teduc-logo-grafite.png   Logo oficial, versão grafite
.nojekyll                       Desliga o Jekyll no GitHub Pages
```

Os logos em `assets/` servem de referência para outros materiais; a página já os traz
embutidos. Preserve proporções e versões dos arquivos oficiais e não redesenhe o logotipo.

## Manutenção

- Ao alterar um capítulo, atualize os quatro idiomas: os arquivos são independentes.
- Revise o manual a cada mudança de portfólio, modelo comercial, operação ou materiais
  institucionais, e registre a alteração no capítulo 31.
- As etiquetas de status (*Institucional*, *Recomendação operacional*, *Depende de acordo*)
  precisam acompanhar o que a Teduc já aprovou formalmente.
- Números de rede e exemplos comerciais citam fonte e data-base: atualize ambos juntos.

## Fonte

Baseado na apresentação institucional *Teduc Business Partners 2026* (17 páginas).
Os exemplos são ilustrativos e não descrevem contratos, resultados ou cases reais.
Documento de uso interno da rede de parceiros.
