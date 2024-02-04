# EstudosGIT
Bem-vindo ao meu repositotio de aprendizado sobre GIT! Este espaço é dedicado a consolidar meus estudos sobre controle de versão e colaboração com GIT.

O que é o GIT?
  GIT é um sistema de controle de versão usado no desenvolvimento de software. Ele rastreia as alterações no código, facilita a colaboração entre equipes e fornece um histórico detalhado das mudanças.

- git config é usado para configurar as opções do Git em um nível específico



  - - Com o GIT, você pode criar ramificações (branches) para desenvolver novos recursos isoladamente, fundir (merge) essas ramificações de volta ao código principal

- git clone URL_do_repositório : é usado para copiar um repositório GIT existente para o seu ambiente local.
- git add nome_do_arquivo : é utilizado para adicionar alterações ao próximo commit no seu repositório GIT. (O git add prepara as mudanças para serem incluídas no próximo commit.)
- - git add . para adicionar todas as alterações no diretório de trabalho ao próximo commit.
- git commit -m "Mensagem do commit" : é utilizado para confirmar as alterações (commits) feitas no seu repositório GIT.
- git pull origin nome_do_branch (git pull origin main): é usado para obter as atualizações mais recentes de um repositório remoto e incorporá-las ao seu repositório local.
- - O (git pull) combina automaticamente o processo de git fetch (que busca as alterações) e git merge (que integra as alterações no seu código).
- git push origin nome_do_branch : é utilizado para enviar as alterações locais para um repositório remoto.
- git remote é usado para gerenciar repositórios remotos associados ao seu projeto Git. Ele permite visualizar, adicionar ou remover repositórios remotos
                                            O que é GITHUB?
    GitHub é uma plataforma de hospedagem de código-fonte e colaboração que utiliza o sistema de controle de versão GIT.
                                            O que é uma Branch 
    Em Git é uma linha independente de desenvolvimento em um repositório.(um rammo),(cópia do código-fonte principal),onde você pode fazer modificações sem afetar diretamente o código na branch principal. Branches são usadas para isolar o trabalho em progresso e permitir o desenvolvimento paralelo.
  - git clone -b nome_do_branch URL_do_repositorio (Lembre-se de que o comando -b é uma opção do git clone para especificar o branch que você deseja clonar.)
  - git clone URL_branch: Este é o comando básico para clonar um repositório Git.
  - git clone URL_branch: --branch nome_DA_Branch: Esta opção especifica qual branch do repositório deve ser clonada.
  - git clone URL_branch: --branch nome_DA_Branch --single-branch: Esta opção faz com que o Git clone apenas a branch especificada
