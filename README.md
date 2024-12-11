# Como Criar um Banco de Dados no Microsoft Azure

## Passo 1: Acesse o Portal do Azure
- Faça login no [Portal do Azure](https://portal.azure.com).

## Passo 2: Navegue até "Banco de Dados"
- No menu lateral esquerdo, clique em **"Criar um recurso"**.
- Na barra de pesquisa, procure por **"Banco de Dados SQL"** e selecione-o.

## Passo 3: Configure o Banco de Dados
1. **Grupo de Recursos**:
   - Selecione um grupo existente ou clique em **"Criar novo"**.
2. **Nome do Banco de Dados**:
   - Escolha um nome único para seu banco de dados.
3. **Servidor**:
   - Clique em **"Criar novo"** para configurar um servidor.
     - Informe o nome do servidor, login de administrador e senha.
     - Escolha a região geográfica para hospedar o servidor.

## Passo 4: Escolha o Plano de Preço
- Selecione a opção de preço mais adequada ao seu uso.
- Para testes, opte pela camada **"Gratuita"** ou de menor custo.

## Passo 5: Configure as Regras de Firewall
- Clique em **"Configurar acesso ao servidor"**.
- Permita acessos seguros, incluindo sua máquina local, marcando **"Adicionar meu IP"**.

## Passo 6: Finalize a Criação
- Revise todas as configurações.
- Clique em **"Criar"**.
- Aguarde a criação do banco de dados (pode levar alguns minutos).

## Passo 7: Conecte-se ao Banco de Dados
- Use ferramentas como **SQL Server Management Studio** ou **Azure Data Studio** para se conectar.
- Insira as credenciais configuradas anteriormente.

Agora você tem um banco de dados funcional no Azure!

