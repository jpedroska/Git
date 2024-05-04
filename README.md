O Git é um sistema de controle de versão distribuído, projetado para ajudar os desenvolvedores a gerenciar projetos de software, acompanhar alterações ao longo do tempo e colaborar de forma eficiente. Aqui está uma visão geral das principais funcionalidades do Git e para que ele serve:
### Para que Serve o Git

- **Gerenciar versões de código**: Git permite acompanhar as alterações em arquivos e projetos ao longo do tempo, criando um histórico claro de cada mudança.
- **Colaboração**: Com o Git, vários desenvolvedores podem trabalhar em um projeto simultaneamente, sem sobrepor ou perder trabalho.
- **Backups e restaurações**: O Git permite restaurar versões anteriores de arquivos ou projetos, tornando mais fácil desfazer alterações indesejadas.
- **Trabalhar em equipe**: Git facilita a colaboração entre equipes, permitindo que cada membro trabalhe em suas próprias versões (branches) e depois integre as mudanças sem conflitos.
- **Auditoria e rastreamento**: Git fornece informações detalhadas sobre quem fez quais alterações e quando, tornando mais fácil identificar problemas e entender o histórico de um projeto.
### Principais Funcionalidades do Git

1. **Commits**:
    - Um commit é uma "fotografia" de um conjunto de alterações. Cada commit tem um identificador único, um autor, uma mensagem descritiva e um timestamp.
    - Os commits permitem registrar alterações de forma segura e reversível.
2. **Branches (Ramos)**:
    - Um branch é uma linha separada de desenvolvimento. É útil para trabalhar em recursos, correções ou experimentos sem afetar a linha principal do projeto.
    - Você pode criar, alternar e excluir branches para gerenciar diferentes fluxos de trabalho.
3. **Merges (Mesclagens)**:
    - O merge é o processo de combinar alterações de um branch em outro. Permite integrar trabalhos paralelos em um único branch, geralmente para lançar uma nova versão ou compartilhar código entre membros da equipe.
4. **Remotes**:
    - Um remote é uma versão remota de um repositório Git, como um repositório hospedado no GitHub ou GitLab.
    - Git permite sincronizar alterações entre repositórios locais e remotos, facilitando a colaboração.
5. **Pull e Push**:
    - `Pull`: Puxa (baixa) as últimas alterações do repositório remoto para seu repositório local.
    - `Push`: Envia (carrega) suas alterações locais para o repositório remoto.
6. **Resolução de Conflitos**:
    - Conflitos ocorrem quando dois ou mais desenvolvedores fazem alterações conflitantes no mesmo arquivo. Git oferece ferramentas para identificar e resolver conflitos de maneira visual ou usando a linha de comando.
7. **Logs e Histórico**:
    - Comandos como `git log` e `git blame` permitem visualizar o histórico de alterações, entender o contexto das mudanças e identificar quem fez alterações específicas.
8. **Stash**:
    - O stash permite salvar temporariamente alterações não confirmadas sem fazer um commit, para que você possa mudar de contexto ou resolver conflitos sem perder seu trabalho em andamento.
9. **Tags**:
    - As tags permitem marcar commits específicos para referências futuras, como versões de lançamento ou marcos importantes.
### Em Resumo

O Git é uma ferramenta poderosa para gerenciamento de código-fonte, proporcionando flexibilidade, colaboração e controle sobre o processo de desenvolvimento de software. Se usado corretamente, ele facilita a colaboração em equipe, mantém o histórico do projeto e oferece ferramentas para lidar com a complexidade do desenvolvimento moderno.

### Comandos
Atualizar repositorio

1. `git add .` - o ponto é para salva todos os arquivos
2. `git commit -m "crição do projeto"` - criar um commit
3. `git push origin main` - puxar todos os arquivos para o github


