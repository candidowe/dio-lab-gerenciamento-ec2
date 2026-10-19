# Roteiro de referência — Gerenciamento de instâncias EC2

## Objetivo

Descrever uma sequência de referência para criar, verificar, gerenciar e encerrar uma instância Amazon EC2.

**Status:** roteiro teórico. Nenhuma instância foi criada ou modificada durante a elaboração deste documento.

## Etapa 1 — Preparação

Antes de iniciar:

- Confirmar acesso autorizado ao ambiente AWS.
- Verificar os custos e os benefícios disponíveis.
- Definir o objetivo do laboratório.
- Escolher uma região apropriada.
- Identificar os recursos necessários.

## Etapa 2 — Configuração da instância

No console do EC2, o procedimento de referência é:

1. Acessar a opção de inicialização de instância.
2. Selecionar uma AMI.
3. Escolher um tipo de instância.
4. Configurar o par de chaves, quando necessário.
5. Revisar as configurações de rede.
6. Definir regras de segurança adequadas.
7. Conferir o armazenamento.
8. Revisar todas as opções antes da inicialização.

## Etapa 3 — Verificação

Após uma inicialização real, verificar:

- Identificador da instância.
- Estado atual.
- Resultado das verificações de status.
- Configuração de rede.
- Volumes associados.
- Possibilidade de conexão, se aplicável.

Os resultados devem ser registrados somente depois da execução.

## Etapa 4 — Gerenciamento do estado

Conforme a finalidade do laboratório, podem ser avaliadas as operações de:

- Inicializar uma instância parada.
- Parar uma instância em execução.
- Reiniciar uma instância.
- Encerrar uma instância que não será mais necessária.

É importante compreender as diferenças entre essas operações antes de executá-las.

## Etapa 5 — Encerramento e revisão

Ao terminar:

1. Confirmar se a instância pode ser encerrada.
2. Verificar as opções de preservação de volumes.
3. Encerrar recursos que não serão mais utilizados.
4. Conferir recursos associados que possam gerar cobranças.
5. Registrar o resultado final.

## Referência

[Iniciar sua primeira instância EC2 — documentação oficial da AWS](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/tutorial-launch-my-first-ec2-instance.html)
