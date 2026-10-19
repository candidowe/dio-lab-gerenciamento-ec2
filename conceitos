# Conceitos fundamentais do Amazon EC2

## 1. O que é o EC2?

O Amazon Elastic Compute Cloud (EC2) é um serviço de computação em nuvem que permite disponibilizar servidores virtuais sob demanda.

Esses servidores podem executar sistemas operacionais, aplicações, serviços web e outras cargas de trabalho.

## 2. AMI — Amazon Machine Image

Uma AMI contém as informações necessárias para iniciar uma instância, incluindo a configuração do sistema operacional e os componentes de software associados à imagem.

A escolha da AMI deve considerar compatibilidade, finalidade e requisitos de segurança.

## 3. Tipos de instância

Os tipos de instância definem a capacidade computacional disponível, incluindo CPU virtual, memória, armazenamento e recursos de rede.

A escolha deve considerar a carga de trabalho e o custo estimado.

## 4. Estados da instância

| Estado | Significado |
|---|---|
| `pending` | A instância está sendo iniciada. |
| `running` | A instância está em execução. |
| `stopping` | A instância está em processo de parada. |
| `stopped` | A instância está parada. |
| `shutting-down` | A instância está sendo encerrada. |
| `terminated` | A instância foi encerrada. |

Parar uma instância não é o mesmo que encerrá-la. Uma instância parada pode normalmente ser iniciada novamente. Uma instância encerrada não pode ser reiniciada.

A parada também não garante custo zero: volumes de armazenamento e outros recursos associados podem continuar sendo cobrados.

## 5. Key Pair

Um par de chaves pode ser utilizado para autenticação ao acessar uma instância. A forma de conexão depende do sistema operacional e da configuração utilizada.

A chave privada deve permanecer protegida. Ela não deve ser enviada ao GitHub nem compartilhada publicamente.

## 6. Security Groups

Os Security Groups funcionam como firewalls virtuais associados às interfaces de rede das instâncias.

Suas regras controlam o tráfego de entrada e saída. O princípio recomendado é permitir somente o tráfego necessário.

Portas administrativas, como SSH e RDP, não devem ficar abertas indiscriminadamente à internet.

## 7. Amazon EBS

O Amazon Elastic Block Store disponibiliza volumes de armazenamento em blocos que podem ser associados a instâncias EC2.

Os volumes podem armazenar sistemas operacionais, aplicações e dados. É importante verificar o ciclo de vida dos volumes ao encerrar um laboratório.

## 8. Região e zona de disponibilidade

Uma região AWS corresponde a uma área geográfica. Uma zona de disponibilidade é um local isolado dentro de uma região.

A seleção de região influencia disponibilidade dos serviços, latência e preços aplicáveis.

## 9. Monitoramento

O gerenciamento de instâncias inclui acompanhar estados, verificações de integridade, métricas e registros disponíveis.

O Amazon CloudWatch é um dos serviços utilizados para monitoramento e observabilidade de recursos AWS.

## 10. Segurança e custos

Antes de iniciar recursos, é importante:

- Conferir o tipo e a quantidade de recursos selecionados.
- Verificar os preços e as condições do nível gratuito ou dos créditos.
- Restringir os acessos de rede.
- Proteger credenciais.
- Acompanhar o consumo e os alertas de orçamento disponíveis.
- Revisar recursos remanescentes após o laboratório.

## Referências

- [Conceitos do Amazon EC2](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html)
- [Estados das instâncias](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-instance-lifecycle.html)
- [Segurança do EC2](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-security.html)
- [Documentação do Amazon EBS](https://docs.aws.amazon.com/ebs/)
- [Documentação do Amazon CloudWatch](https://docs.aws.amazon.com/cloudwatch/)
