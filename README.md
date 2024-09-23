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
*********************************************

# Desafio 6 - Entendendo sobre a Segurança e Identidade no Azure
## 1. Configurar o Azure Active Directory (Azure AD)   
O Azure Active Directory (Azure AD) é o serviço de identidade no Azure, essencial para gerenciar logins, autenticação e controle de acesso. A primeira etapa é configurar o Azure AD.

### Acesse o Azure Portal.
[Portal do Azure](https://azure.microsoft.com/pt-br/)

No menu de serviços, procure por Azure Microsoft Entra ID.
![image](https://github.com/user-attachments/assets/f281c1d2-0267-4db2-9129-3bcba85a3da9)

No painel do Azure AD, você pode gerenciar usuários, grupos, aplicativos e funções.
![image](https://github.com/user-attachments/assets/03402436-6401-41d7-a03a-8bc4932bca26)

## 2. Adicionar Usuários ao Azure AD
Adicionar e gerenciar usuários no Azure AD é a chave para fornecer acesso seguro.
![image](https://github.com/user-attachments/assets/0d5d4bf4-b785-4124-b4ab-31677317f40d)


### Dentro do Azure AD, vá para Usuários e clique em Novo usuário.
Insira as informações do usuário, como nome, e-mail, e defina um método de autenticação (como senha temporária).
Você também pode adicionar usuários externos como convidados, permitindo colaboração segura.
![image](https://github.com/user-attachments/assets/c0ee647e-3838-402c-b388-de515d53b1b7)

## 3. Criar e Gerenciar Grupos de Segurança
Grupos são úteis para aplicar políticas de segurança de maneira centralizada. Você pode definir permissões de acesso com base nos grupos.
![image](https://github.com/user-attachments/assets/6d939920-f69a-4582-abc1-bfd1138b184f)

### No Azure AD, selecione Grupos e clique em Novo grupo.
![image](https://github.com/user-attachments/assets/d036dfd8-c6f2-4e24-a227-a6301188aaae)
Escolha o tipo de grupo: Grupo de segurança (para permissões) ou Grupo do Office 365 (para colaboração).
Adicione usuários ou outros grupos ao novo grupo criado.
![image](https://github.com/user-attachments/assets/37c0c7f8-077f-415d-b184-a2cf8aadd21b)

## 4. Configurar Funções e Controle de Acesso Baseado em Funções (RBAC)
O RBAC (Role-Based Access Control) é fundamental para garantir que os usuários só tenham acesso às funcionalidades necessárias para sua função.

### No Azure Portal, vá até o recurso que você deseja proteger, como Máquinas Virtuais ou Armazenamento.
Clique em Controle de Acesso (IAM).
Selecione Adicionar função e atribua uma das funções predefinidas (como Administrador, Colaborador, etc.) ou crie uma função personalizada.
Atribua esta função a usuários ou grupos.
![image](https://github.com/user-attachments/assets/100e3f59-458a-44c1-a05c-4cdc9482c7d4)

## 5. Implementar Autenticação Multifator (MFA)
A MFA adiciona uma camada extra de segurança, exigindo que os usuários verifiquem suas identidades com um método adicional (como um código enviado por SMS ou um aplicativo autenticador).
![image](https://github.com/user-attachments/assets/a8c0662f-1499-4816-9bcd-c4d82fa22292)

###  Azure AD, selecione Segurança e depois Autenticação multifator.
Escolha Métodos de autenticação e configure os métodos (como SMS ou aplicativos de autenticação).
Habilite a MFA para todos os usuários ou para grupos específicos.

## 6. Usar Políticas de Acesso Condicional
As políticas de acesso condicional permitem que você defina regras de acesso com base em condições como localização, dispositivo ou estado de risco.
### No Azure AD, vá até Segurança e clique em Acesso condicional.
![image](https://github.com/user-attachments/assets/52d2765b-c241-429c-ac9b-48a2ac7a0394)
Crie uma nova política e defina as condições, como:
Quem: Defina os usuários/grupos.
O que: Defina quais aplicativos ou recursos estão envolvidos.
Condições: Como IPs, localizações ou dispositivos.
Ações: Como permitir ou exigir MFA.

### 7. Gerenciar Identidades com o Azure AD Identity Protection
O Identity Protection no Azure AD oferece inteligência para identificar atividades suspeitas relacionadas a identidades.
![image](https://github.com/user-attachments/assets/3ac0347c-b844-4644-a0ca-b4bed82d928b)


## No Azure AD, vá até Segurança > Proteção de identidade.
Veja alertas e recomendações, como logins de risco ou tentativas de login fora do padrão.
Configure políticas de proteção automatizada para mitigar riscos.
![image](https://github.com/user-attachments/assets/cf0f43b0-33a8-4bc0-8b91-2ad19809e9d5)

### 8. Monitorar e Auditar Atividades com Azure Monitor e Log Analytics
A segurança requer monitoramento contínuo. Use Azure Monitor e Log Analytics para monitorar atividades, gerar alertas e realizar auditorias.
No Azure Monitor, crie alertas para atividades anormais (como tentativas de login falhas).
Use Log Analytics para verificar logs e eventos de segurança.
Defina auditorias regulares para analisar o uso de permissões e possíveis vulnerabilidades.
![image](https://github.com/user-attachments/assets/88614880-c443-4439-af64-3d7463678522)

### 9. Proteger Aplicações com Azure AD Application Proxy
Se você tem aplicativos locais que precisam ser acessados de forma segura pela internet, o Azure AD Application Proxy pode ajudar.
![image](https://github.com/user-attachments/assets/fc060c81-b933-4f9a-9588-1dbd83e5b9cc)

## No Azure AD, vá para Aplicativos empresariais e configure o Application Proxy.
Configure os aplicativos locais para serem publicados por meio do proxy, permitindo autenticação e acesso seguros via Azure AD.
![image](https://github.com/user-attachments/assets/f1dd6629-ade5-4afd-b354-7f03e9dd5b13)

### 10. Manter-se Atualizado com as Recomendações do Azure Security Center
O Azure Security Center fornece recomendações contínuas de segurança e monitoramento do estado de segurança dos recursos.


