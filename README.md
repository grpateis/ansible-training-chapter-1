# ansible-training-chapter-1
Primeiro capítulo do treinamento Ansible for Devops
Notas:
Instalado Ansible
Instalado Vagrant
Criada instância EC2 na AWS
  Não relevante para esse exercício
Criado key-pair na AWS
Permitir porta 22 (ssh) - já é default
Dar as permissões para execução do Key-Pair
  chmod 400
Para o Ansible reconhecer e usar o Ke-Pair
  ssh-add : adicionar pem file.

Arquivo Ansible.cfg
  pode setar defaults
  
ansible -m setup
  mostra todos os recursos do servidor
 
ansible -b ou ansible -become 
  permite ser root no servidor
  
ansible -m service
  checa se o serviço está ativo
 
ansible -m yum | apt | dnf
  instala pacotes no servidor
  
 ansible-doc 
  mostra o manual do ansible
  
 ansible -K
  para digitar a senha do root
  
 ansible -B 2000
  executa tarefa no background
  
 async_status
  checa se tarefa no background foi concluída
  
 ansible - m shell
  executa bash(shell) - exemplp : para entender piple '|'
  
 -m git 
  para integrar com o git (deve ser configurado)
  
 
