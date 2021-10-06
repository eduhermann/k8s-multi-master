# K8S - Multi Master

O repositório tem o objetivo de demonstrar uma forma automatizada de realizar o deploy de um cluster K8S com alta disponibilidade de servidores Master.

Iremos demonstrar a utilização de servidores control-plane operando com o etcd nos próprios nodes.

Verifique a documentação oficial do Kubernetes para mais detalhes de operação em ambientes HA.

## Topologia abordada
- Imagem retirada da documentação oficial do K8S.

![Topologia Kubernetes HA](https://d33wubrfki0l68.cloudfront.net/d1411cded83856552f37911eb4522d9887ca4e83/b94b2/images/kubeadm/kubeadm-ha-topology-stacked-etcd.svg)

### Documentação oficial K8S - HA
- [Doc Kubernetes HA](https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/ha-topology/)