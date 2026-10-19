# dio-lab-gerenciamento-ec2
Laboratório DIO sobre conceitos e gerenciamento de instâncias Amazon EC2 na AWS.

# Laboratório DIO — Gerenciamento de Instâncias Amazon EC2

![AWS](https://img.shields.io/badge/AWS-Amazon%20EC2-orange)
![Documentação](https://img.shields.io/badge/Projeto-Documentação%20Técnica-blue)
![Status](https://img.shields.io/badge/Prática-Pendente-lightgrey)

## Sobre o projeto

Este repositório foi desenvolvido como parte do desafio da Digital Innovation One (DIO), com o objetivo de organizar e consolidar conhecimentos sobre gerenciamento de instâncias do Amazon Elastic Compute Cloud (Amazon EC2).

O material reúne conceitos fundamentais, um roteiro de referência para gerenciamento de instâncias e recomendações básicas de segurança e controle de custos.

**Escopo atual:** documentação teórica e planejamento da prática. Não foi criada nem gerenciada uma instância EC2 neste projeto, pois o laboratório está sendo desenvolvido sem uma conta AWS própria.

## Objetivos de aprendizagem

- Compreender o funcionamento do Amazon EC2.
- Identificar os principais componentes de uma instância.
- Conhecer o fluxo de criação e gerenciamento de instâncias.
- Compreender os estados de uma instância EC2.
- Conhecer conceitos de AMI, tipos de instância, EBS e Security Groups.
- Entender cuidados básicos de segurança e custos.
- Praticar a organização de documentação técnica usando Markdown e GitHub.

## Conceitos estudados

| Conceito | Descrição |
|---|---|
| Amazon EC2 | Serviço de computação que disponibiliza servidores virtuais na AWS. |
| AMI | Imagem usada como modelo para iniciar uma instância. |
| Tipo de instância | Define os recursos computacionais disponíveis. |
| Key Pair | Par de chaves que pode ser usado para autenticação. |
| Security Group | Firewall virtual que controla o tráfego de rede. |
| Amazon EBS | Serviço de armazenamento em blocos para instâncias EC2. |
| Região | Área geográfica da infraestrutura AWS. |
| Zona de disponibilidade | Local isolado dentro de uma região AWS. |

## Roteiro de gerenciamento

O fluxo de referência para trabalhar com uma instância EC2 envolve:

1. Acessar o console da AWS.
2. Abrir o serviço Amazon EC2.
3. Selecionar uma AMI apropriada.
4. Escolher um tipo de instância.
5. Configurar rede, armazenamento e regras de segurança.
6. Revisar as configurações e iniciar a instância.
7. Acompanhar o estado e as verificações da instância.
8. Configurar e testar a conexão, se necessário.
9. Parar ou encerrar a instância de acordo com o objetivo do laboratório.
10. Verificar os recursos remanescentes e possíveis custos.

Essas etapas são um roteiro de referência, não um registro de execução.

## Segurança e controle de custos

- Proteger credenciais e chaves privadas.
- Evitar a exposição desnecessária de portas.
- Aplicar o princípio do menor privilégio.
- Conferir os recursos antes de iniciá-los.
- Consultar as condições de cobrança e os benefícios disponíveis.
- Verificar volumes, endereços IP e outros recursos que possam continuar gerando custos.
- Não publicar credenciais, tokens ou informações sensíveis no GitHub.

## Status do projeto

- [x] Assistir às videoaulas da DIO.
- [x] Organizar a documentação inicial.
- [x] Preparar um roteiro teórico de gerenciamento.
- [X ] Executar o laboratório em um ambiente AWS.
- [ ] Registrar evidências de execução real.
- [ ] Atualizar o projeto com resultados práticos, se houver acesso futuro a um laboratório.

## Limitações

Este projeto não comprova a criação, conexão, parada ou encerramento de instâncias EC2. As etapas práticas permanecem pendentes.

O material tem finalidade educacional e de revisão dos conceitos estudados.

## Conclusão

A documentação organiza os principais conceitos relacionados ao gerenciamento de instâncias Amazon EC2 e oferece uma referência para uma futura atividade prática.

O próximo passo para consolidar o aprendizado será executar o roteiro em um ambiente autorizado de laboratório e registrar os resultados observados.

## Referências

- [Documentação oficial do Amazon EC2](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html)
- [Primeiros passos com Amazon EC2](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html)
- [Ciclo de vida das AMIs](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ami-lifecycle.html)
- [Grupos de segurança do EC2](https://docs.aws.amazon.com/us_en/AWSEC2/latest/UserGuide/ec2-security-groups.html)
- [Segurança no Amazon EC2](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-security.html)
- [GitHub: introdução à escrita e ao Markdown](https://docs.github.com/pt/get-started/writing-on-github)
