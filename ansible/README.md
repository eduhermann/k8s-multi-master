# K8S - Multi Master
## Ansible

- É importante que seu ambiente esteja com:
    * Chave SSH aplicada em todas as VMs para evitar necessidade de inserir senha manualmente.
    * VMs instaladas comunicáveis a nível de rede e com firewall liberado entre ambas.
    * VMs com S.O. atualizado e em pleno funcionamento.

- A hierarquia do Ansible segue padrões adotados a partir de boas práticas seguindo a documentação da ferramenta.

- Faça o clone do repositório, atualize informações de IP e credenciais caso necessário e então execute a playbook **playbook_deploy-ks8.yml** que todas as roles estão integradas a essa playbook.