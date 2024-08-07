
# Sistema Bancário Simples

Este é um sistema bancário simples implementado em Python. Ele permite aos usuários realizarem operações básicas como depósitos, saques, visualização de extratos, criação de contas e usuários, e listagem de contas.

## Funcionalidades

1. **Depositar**: Permite ao usuário depositar um valor em sua conta.
2. **Sacar**: Permite ao usuário sacar um valor de sua conta, respeitando o limite diário e o saldo disponível.
3. **Extrato**: Exibe o extrato das transações realizadas na conta.
4. **Nova conta**: Cria uma nova conta associada a um usuário existente.
5. **Listar contas**: Lista todas as contas criadas no sistema.
6. **Novo usuário**: Cria um novo usuário no sistema.
7. **Sair**: Encerra o programa.


### Passos

1. Clone este repositório ou baixe o arquivo ZIP.
2. Navegue até o diretório onde os arquivos foram salvos.
3. Execute o script principal:

    ```bash
    python main.py
    ```

### Uso

Ao executar o script, será exibido um menu com as seguintes opções:

- `[d]` Depositar
- `[s]` Sacar
- `[e]` Extrato
- `[nc]` Nova conta
- `[lc]` Listar contas
- `[nu]` Novo usuário
- `[q]` Sair

Digite a letra correspondente à operação desejada e siga as instruções que serão exibidas.

## Estrutura do Código

- **menu**: Exibe o menu de opções e retorna a escolha do usuário.
- **depositar**: Realiza a operação de depósito.
- **sacar**: Realiza a operação de saque, verificando limites e saldo disponível.
- **exibir_extrato**: Exibe o extrato da conta.
- **criar_usuario**: Cria um novo usuário no sistema.
- **filtrar_usuario**: Filtra usuários pelo CPF.
- **criar_conta**: Cria uma nova conta associada a um usuário.
- **listar_contas**: Lista todas as contas existentes no sistema.
- **main**: Função principal que controla o fluxo do programa.
