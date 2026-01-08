cat > .github/copilot-instructions.md <<'EOF'
# Descrição do Projeto

Este projeto é um site educacional para compartilhar tarefas de casa e exercícios de programação com estudantes. Os estudantes podem navegar, visualizar e baixar tarefas diretamente do portal.

## Estrutura do Projeto

- [`assignments/`](../assignments/) Cada tarefa de casa é armazenada em sua própria subpasta com uma estrutura consistente.
- [`templates/`](../templates/) Templates reutilizáveis para novo conteúdo
- [`assets/`](../assets/) Contém os recursos do site incluindo CSS, JavaScript, imagens e arquivos de configuração
- [`index.html`](../index.html) A página principal do site que serve como um portal estático para navegar e visualizar tarefas. O conteúdo é configurável através do arquivo [`config.json`](../config.json) para gerar dinamicamente listas e detalhes de tarefas.

## Diretrizes do Projeto

- Manter estilo consistente em todas as páginas
- Manter nomes de arquivos e pastas descritivos e organizados

Este repositório adota o padrão Conventional Commits para mensagens de commit. Use o formato tipo(escopo): breve descrição (ex.: feat(auth): adicionar login). Tipos recomendados: feat, fix, docs, style, refactor, test e chore. Exemplos de commits para referência:
- feat(auth): adicionar fluxo de login com JWT
- fix(ui): corrigir alinhamento do botão enviar
- docs: atualizar README com instruções de contribuição
- style: aplicar formatação Prettier no código
- refactor(api): extrair cliente HTTP para módulo separado
- test: adicionar testes unitários para validação de entrada
- chore(deps): atualizar dependências de desenvolvimento

## Padrões Educacionais

Ao gerar conteúdo para este projeto:

- **Focado em aprendizado**: Todo conteúdo deve ser projetado com objetivos de aprendizado claros e níveis de dificuldade apropriados
- **Amigável para estudantes**: Use linguagem clara e encorajadora que motiva os estudantes
EOF