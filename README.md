# K8S - Multi Master

O repositório tem o objetivo de demonstrar uma forma automatizada de realizar o deploy de um cluster K8S com alta disponibilidade de servidores Master.

Iremos demonstrar a utilização de servidores control-plane operando com o etcd nos próprios nodes.

É importante que você tenha conhecimento de algumas ferramentas OpenSource como virtualização, servidores Linux, Redes, Ansible, Docker e Kubernetes.

Verifique a documentação oficial do Kubernetes para mais detalhes de operação em ambientes HA.

### Documentação oficial K8S - HA
- [Doc Kubernetes HA](https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/ha-topology/)

### Topologia abordada
- Imagem retirada da documentação oficial do K8S.

![Topologia Kubernetes HA](https://d33wubrfki0l68.cloudfront.net/d1411cded83856552f37911eb4522d9887ca4e83/b94b2/images/kubeadm/kubeadm-ha-topology-stacked-etcd.svg)

### Recursos utilizados

Aqui estão alguns dos recursos utilizados para realizar o deploy do ambiente.

Lembrando que é possível adaptar o ambiente caso necessário.

* 07 VMs
    * S.O. Ubuntu 20.04 LTS
    * 02 GB de Memória RAM
    * 02 core CPU
    * 01 network card
        * 3 VMs para os nodes Masters
        * 3 VMs para os nodes Workers
        * 1 VM para o HAProxy

### Executando o projeto

O projeto foi estruturado com a utilização de Ansible para a automatização do deploy.

Navegue entre as pastas do projeto e verifique os README disponível em cada para provisionar o projeto.

### Agradecimentos

Agradecimentos ao pessoal da [LinuxTips](https://www.linuxtips.io/) pelo conteúdo, especificamente pelo conteúdo do curso de [Kubernetes](https://www.linuxtips.io/products/descomplicando-o-kubernetes)

**Enjoy!**