# laboratorio-devops
Repositorio criado com a finalidade de executar exercicios para o aprendizado da cultura devops
https://github.com/p2pbr/laboratorio-devops.git

issue: exercício-1-diretorio-dev-front-end

branch:
1-exercício-1-diretorio-dev-front-end


Descrição:  
Esta issue tem como objetivo implementar um workflow no GitHub Actions para criar um diretório específico para a equipe de desenvolvimento front-end no servidor remoto. O workflow será acionado sempre que houver um push na branch `feature/criar-diretorio-dev`, e executará as seguintes etapas:

1. Configuração do ambiente com a chave SSH do repositório.
2. Conexão SSH com o servidor remoto para criar o diretório `/home/jaime/dev/front-end`.
3. Verificação de sucesso na criação do diretório.

Objetivos:
- Criar o workflow com as etapas necessárias para automatizar a criação do diretório.
- Garantir que o diretório seja criado corretamente ao realizar um push na branch `feature/criar-diretorio-dev`.

Tarefas:
- Criar o arquivo de workflow no repositório.
- Configurar as variáveis necessárias para autenticação SSH.
- Testar o workflow para garantir que o diretório seja criado com sucesso no servidor.

Notas:
- A chave SSH deve ser configurada no repositório para permitir que o workflow tenha acesso ao servidor remoto.

