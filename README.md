# Application-Manager

Gestor de candidaturas a emprego, simples e elegante. Uma única página (`index.html`), sem servidor, sem contas e sem dependências para instalar.

Criado para acompanhar candidaturas de forma rápida: o que enviei, o que foi visto, onde houve entrevista, onde fui recusado e onde ainda estou à espera.

## Funcionalidades

- **Fluxo por etapas**: Candidatei → Candidatura vista → Entrevista → Oferta → Aceite. Em cada etapa só aparecem os botões que fazem sentido (avançar ou *Recusado*), com **↩ Voltar atrás** para corrigir enganos.
- **Vaga fechada**: marca vagas que já não aceitam candidaturas. Uma candidatura recusada fecha a vaga automaticamente.
- **À espera de resposta**: botão dourado que mostra tudo o que não está fechado, recusado ou aceite, com aviso de há quantos dias aguardas.
- **Notas e entrevistas** por candidatura, com tipo (RH, Técnica, Final) e datas, incluindo entrevistas agendadas.
- **Data da candidatura editável**.
- **Filtros**: pesquisa, estado, interação e vaga aberta/fechada.
- **Números no topo**: candidaturas, com interação, recusadas, com entrevista, com oferta e à espera.
- Modo claro/escuro automático e animações suaves.

## Como usar

Abre o `index.html` no navegador (duplo clique) ou usa a versão no GitHub Pages:

`https://fpmota.github.io/Application-Manager/`

### Onde ficam os dados?

No `localStorage` do teu navegador, ou seja, **só no dispositivo e navegador onde usas a página**. Nada é enviado para servidores.

Por isso:

- Usa **Exportar backup** de vez em quando (gera um ficheiro `.json`).
- Usa **Importar backup** para recuperar os dados ou levá-los para outro dispositivo.
- Limpar os dados de navegação apaga as candidaturas, se não tiveres backup.

### Dados pessoais fora do repositório

O ficheiro opcional `seed-data.js` serve para carregar candidaturas iniciais e está no `.gitignore`, por isso **não é publicado**. Sem ele, a app começa vazia.
