# roles

- Aqui estão todas as roles envolvidas no projeto.

- role_pre-setup
    * Destinada a configurações básicas iniciais realizada em todos os nodes.

- role_haproxy
    * Destinada a instalação e configuração do serviço HAProxy, provendo configurações de nodes e também página de saúde do serviço e nodes.

- role_deploy-k8s
    * Destinada a instalação e configuração de recursos iniciais para a utilização do Kubernetes.

- role_init-k8s
    * Inicialização dos nodes Masters K8S.

- role_workers-k8s
    * Adicionando nodes Workers ao cluster K8S.