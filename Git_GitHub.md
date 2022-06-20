# Desafio Bootcamp - Git e GitHub :cat:



​	O **Git** é uma ferramenta de arquivos em geral, muito utilizada por desenvolvedores de _software_, onde é permitido salvar diferentes versões do seu projeto, para a realização de melhorias.

​	O **Github** é um serviço de armazenamento em nuvens, onde podemos criar repositórios, públicos e privados, e interagir com outros usuários da plataforma, trocando experiencias, e melhorias. Temos 5 vantagens de se utilizar

- Controle de versões.
- Armazenamento em nuvem.
- Trabalho em equipe.
- Melhoria do código.
- Reconhecimento.



**Etapas de um Arquivo**

- **Untracked and Tracked**

  1- **Untracked** é o estado em que o arquivo se encontra quando a ferramenta de versionamento Git ainda não tem o conhecimento.

  2- **Tracked** é quando o Git já tem a ciência do arquivo.

  Em Tracked o arquivo se encontra em três estágios:

  - **Unmodified** - O arquivo ainda não sofreu modificações ou já está armazenado em um repositório.
  - **Modified** - O arquivo já recebeu alguma modificação.
  - **Staged** - O arquivo se encontra pronto para para "entrar no palco", aguardando para ser armazenado.

**Desenvolvimento**

- **Working Directory**

  Working Directory é a árvore de diretórios dos arquivos iniciais (fonte), onde pode-se ver e editar. (Nessa etapa o Git ainda não conhece o arquivo, o arquivo é Untracked)*.

- **Staging Área**

​		Staging Área é o nível em que o arquivo se encontra pronto para avançar de nível, ou seja, pronto para embarcar a um repositório local. (Nessa etapa do processo o Git já tem conhecimento do arquivo, o arquivo passa a ser Tracked).

- **Repository**

 		É o local onde o arquivo fica armazenado. (o arquivo continua ser tracked).



**Comandos básicos**

Dentro do Git Bash utilizamos os seguintes comandos:

**mkdir** - Criar arquivo

**cd** - Entrar na pasta especifica (cd c/users)

**cd ..** - Retornar para a pasta anterior

**del** - Deletar tudo que tem dentro de um diretório

**rmdir** - Deleta o diretório

**dir** -  Verificar todos os diretórios

**ls** - Listar os diretórios.

**ls -a** - Listar os arquivos ocultos.

​		Quando criamos um arquivo com o _mkdir_, o arquivo esta na fase em que o git não tem ciência do que esta lá, ou seja fica com o status de _untracked_, para avisarmos o Git do arquivo utilizamos o comando _git add_, onde o status é alterado para _starged_, onde o arquivo esta pronto para ser comitado, ou seja temos que iniciar o repositório com o _git init_, e para ser armazenado em um repositório para isso utilizamos o _git commit_.

​		Quando removermos o arquivo _Unmodified_ ele retorna a ser um arquivo _untracked_. Ao editarmos o arquivo _Unmodified, ele passa a ser um arquivo _modified_, aguardando um _commit_ e logo após ele ser commitado, passa a ser novamente um arquivo _Unmodified_, ou seja um arquivo sem novas alterações.

**Observações**

- Arquivos iniciados com ponto - .git - trata-se de um arquivo oculto.

- .md - Arquivos com formado md são Markdown.

- Quando utilizar pela primeira vez, deve se realizar a configuração abaixo:

  git config --global user.email "e-mail@e-mail.com"

  git config --global user.name "Ana Carolina"





















