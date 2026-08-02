# Banco de Questões de Contabilidade Geral — Versão 1.0

PWA público do **Curso de Contabilidade Professor Moreira**, preparado para publicação no GitHub Pages.

## Conteúdo desta versão

- **931 questões liberadas** no aplicativo.
- **48 questões separadas para revisão** em `data/questoes_revisar.json`.
- Pesquisa por enunciado, tema, órgão, cargo, ano, alternativas e comentários.
- Filtros por tema, ano e dificuldade.
- Simulados de 5, 10, 20, 30, 50 ou 100 questões.
- Correção imediata e comentário completo.
- Favoritos, caderno de erros e estatísticas locais.
- Instalação no celular como PWA.
- Funcionamento offline após o primeiro acesso.

## Publicação no GitHub

1. Extraia o ZIP.
2. Copie **todos os arquivos e pastas que estão dentro desta pasta** para:
   `Documentos/GitHub/BANCO-QUESTOES-CONTABILIDADE-GERAL`
3. No GitHub Desktop, faça o commit:
   `Versão 1.0 oficial do banco de questões`
4. Clique em `Push origin`.
5. No GitHub, abra:
   `Settings > Pages > Deploy from a branch > main > /root > Save`

## Estrutura

```text
index.html
app.js
style.css
manifest.json
service-worker.js
README.md
.nojekyll
data/
  questoes.json
  questoes_revisar.json
icons/
  icon-192.svg
  icon-512.svg
```

## Controle de qualidade

A extração foi automatizada. Questões com falha estrutural detectável foram removidas da publicação e enviadas para o arquivo de revisão. Fórmulas, tabelas, imagens e questões que atravessam páginas ainda devem ser conferidas progressivamente.

Gerado em: 02/08/2026 19:41
