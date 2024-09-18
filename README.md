# Resumo-do-lab


<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Microsoft Azure Essentials</span>
</h1>

Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO ** ** da [Digital Innovation One](https://www.dio.me/).

[![Link do Lab](https://img.shields.io/badge/▶-000?style=for-the-badge&logo=movie&logoColor=E94D5F)](https://web.dio.me/course/introducao-ao-bootcamp-azure-essentials/learning/f84e131a-8052-4722-a3c1-360070338a1e?back=/track/microsoft-azure-essentials&tab=undefined&moduleId=undefined) 


## Objetivo
Microsoft Azure - Localizando Serviços por Categoria.

## Ferramentas
[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=30A3DC)](https://docs.github.com/)
[![Git](https://img.shields.io/badge/Git-000?style=for-the-badge&logo=git&logoColor=E94D5F)](https://git-scm.com/doc) 

## Percurso
<table>
  <thead>
    <tr align="left">
      <th>Nº</th>
      <th>Desafios do Projeto</th>
    </tr>
  </thead>
  <tbody align="left">
    <tr>
      <td>01</td>
      <td>Microsoft Azure - Localizando Serviços por categoria</td>
    </tr>
    <tr>
      <td>02</td>
      <td>Criando maquinas Virtuais na Azure</td>
    </tr>
    <tr>
      <td>03</td>
      <td>Configurando uma instancia de banco de Dados na Azure</td>
    </tr>
    <tr>
      <td>04</td>
      <td>Contruindo Arquiteturas no Azure</td>
    </tr>
    <tr>
      <td>05</td>
      <td>Configurando Recursos e Dimensionamentos m Maquinas Virtuais na Azure</td>  
    </tr>
    <tr>
      <td>06</td>
      <td> Dominando o Armazenamentos na Azure</td>    
    </tr>
     <tr>
      <td>07</td>
      <td> Entendendo sobre Segurança e Identidade na Azure</td>    
    </tr>
     <tr>
      <td>08</td>
      <td> Explorando Arquitetura e Serviços Azure com logica de programação</td>    
    </tr>
     <tr>
      <td>09</td>
      <td>Otimizando custos na Azure</td>    
    </tr>
     <tr>
      <td>10</td>
      <td> Gerenciando politicas em Acessos Azure</td>    
    </tr>
     <tr>
      <td>11</td>
      <td> Ferramentas de implantação no Azure</td>    
    </tr>
     <tr>
      <td>12</td>
      <td> Monitoramentos Inteligente com o Azure</td>    
    </tr>    
  </tbody>
</table>

#Desafio 1 - Passo a Passo para Localizar Serviços por Categoria no Azure

### 1. Acessar o Portal do Azure
Acesse o [Portal do Azure](https://portal.azure.com) e faça login com suas credenciais da conta Microsoft.

## 2. Navegar para "Criar um Recurso"
Na tela inicial do Azure, no painel esquerdo, clique em **"Criar um recurso"**. Isso abrirá uma lista de serviços disponíveis.

## 3. Explorar por Categorias
Na página "Criar um Recurso", explore as seguintes categorias:
- Computação
- Redes
- Armazenamento
- Banco de Dados
- Web
- Mobile
- Inteligência Artificial + Machine Learning
- DevOps
- Segurança
- Monitoramento e Gerenciamento

## 4. Selecionar uma Categoria
Clique na categoria desejada para ver os serviços, como **Máquinas Virtuais**, **Containers**, etc.

## 5. Pesquisar por Nome ou Filtro
Use a barra de pesquisa ou filtros para refinar sua busca por serviço, tipo ou região.

## 6. Ver Detalhes do Serviço
Clique no serviço para ver mais detalhes, incluindo descrição, preços e opções de configuração.

## 7. Criar e Gerenciar Serviços
Siga as instruções na tela para configurar e implementar o serviço escolhido.



# Desafio 2 - Criando maquinas Virtuais na Azure

Este guia descreve os passos para criar e configurar uma Máquina Virtual no Portal do Azure.

## 1. Acessar o Portal do Azure

1. Navegue até [https://portal.azure.com/](https://portal.azure.com/).
2. Faça login com suas credenciais do Azure.

## 2. Criar uma Nova Máquina Virtual

1. Na barra de pesquisa, digite **"Máquinas Virtuais"** e selecione o serviço.
2. Clique em **"Criar"** e, em seguida, em **"Máquina virtual"**.

## 3. Configurar a Máquina Virtual

### Essenciais
- **Nome**: Atribua um nome descritivo à sua VM.
- **Grupo de Recursos**: Selecione um grupo de recursos existente ou crie um novo para organizar seus recursos.
- **Região**: Escolha a região do Azure mais próxima de você ou que melhor atenda às suas necessidades.
- **Imagem**: Selecione a imagem do sistema operacional desejado (Windows ou Linux).

### Tamanho
- Escolha o tamanho da VM que atenda às suas necessidades de CPU e memória.

### Discos
- Configure o tamanho do disco do sistema operacional.

### Redes
- **Rede Virtual**: Selecione uma rede virtual existente ou crie uma nova.
- **Sub-rede**: Escolha uma sub-rede dentro da rede virtual.
- **Endereço IP Público**: Se precisar de acesso externo à VM, habilite um endereço IP público.

### Gerenciamento
- Configure opções de monitoramento, diagnóstico e alertas.

### Avançado
- Explore opções adicionais como disponibilidade, identidade e tags.

## 4. Revisar e Criar

1. Revise todas as configurações antes de criar a VM.
2. Clique em **"Criar"** para iniciar o provisionamento.

## 5. Conectar-se à Máquina Virtual

- Após a criação, você poderá se conectar à sua VM usando o protocolo **RDP (Windows)** ou **SSH (Linux)**.
- As informações de conexão estarão disponíveis no Portal do Azure.



# Desafio 3 - Configurando uma Instância de Banco de Dados no Azure

### 1. Acessar o Portal do Azure
Acesse o [Portal do Azure](https://portal.azure.com) e faça login com suas credenciais.

## 2. Criar um Recurso
No painel esquerdo, clique em **"Criar um recurso"** e, em seguida, selecione a categoria **Banco de Dados**.

## 3. Selecionar o Tipo de Banco de Dados
Escolha entre as opções como **Azure SQL Database**, **MySQL**, **PostgreSQL**, ou **Cosmos DB**, de acordo com sua necessidade.

## 4. Configurar a Instância
Preencha os campos solicitados, como:
- Nome do servidor
- Região
- Plano de preços
- Tipo de armazenamento

## 5. Criar Usuário e Senha
Defina as credenciais de administrador para gerenciar o banco de dados.

## 6. Configurar Opções Avançadas
Configure réplicas, backups automáticos e outras opções avançadas, se necessário.

## 7. Revisar e Criar
Revise suas configurações e clique em **Criar** para provisionar a instância.

## 8. Acessar e Gerenciar o Banco de Dados
Após a criação, você pode acessar a instância pela sua **Connection String** e gerenciá-la no **Azure Portal** ou via cliente SQL.



# Desafio 4 - Construir Arquiteturas no Azure
# Construindo Arquiteturas no Azure

## 1. Identificar os Requisitos
Defina as necessidades do seu projeto, como escalabilidade, segurança, e tipo de aplicação ou serviço.

## 2. Escolher os Componentes
Selecione os principais serviços do Azure para sua arquitetura:
- **Computação**: Máquinas Virtuais (VMs), Containers, App Services.
- **Armazenamento**: Blobs, Discos, Armazenamento de Arquivos.
- **Banco de Dados**: SQL Database, Cosmos DB.

## 3. Criar a Arquitetura
Use o **Azure Architecture Center** ou o **Azure Portal** para criar diagramas e modelos de infraestrutura, integrando recursos como:
- **Rede**: VPN, VNET, Load Balancers.
- **Monitoramento**: Application Insights, Azure Monitor.
- **Segurança**: Azure AD, Key Vault, Firewall.

## 4. Implementar Automação e DevOps
Automatize o gerenciamento com ferramentas como **Azure DevOps**, **Terraform** ou **ARM Templates**.

## 5. Testar e Escalar
Teste a arquitetura e ajuste-a conforme necessário, usando políticas de escalabilidade automatizada e gerenciamento de tráfego.

## 6. Monitorar e Otimizar
Monitore o desempenho com **Azure Monitor**, configurando alertas e otimizando com base no uso de recursos.



# Desafio 4 - Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

### 1. Acessar o Portal do Azure
Entre no [Portal do Azure](https://portal.azure.com) e navegue até **Máquinas Virtuais**.

## 2. Selecionar a VM
Escolha a VM existente ou crie uma nova.

## 3. Configurar Tamanho e Tipos de Máquinas Virtuais
Na configuração de criação ou dentro da VM, selecione o **tamanho** da máquina. Escolha de acordo com a necessidade de CPU, memória e armazenamento:
- **Básico**: Para tarefas leves.
- **Avançado**: Para cargas de trabalho pesadas (uso de GPU, alta performance).

## 4. Escalonamento Manual
Você pode alterar manualmente o tamanho da VM a qualquer momento.

## 5. Escalonamento Automático (Auto-scaling)
Para dimensionamento automático, ative **Scale Sets**, definindo políticas para ajustar os recursos com base em métricas de desempenho.

## 6. Monitorar o Desempenho
Use o **Azure Monitor** para acompanhar o uso de recursos e ajustar conforme necessário.

# Desafio 5 -Dominando o Armazenamento na Azure

