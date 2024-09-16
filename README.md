# Resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO


# Guia para Criação de Máquina Virtual no Azure

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
