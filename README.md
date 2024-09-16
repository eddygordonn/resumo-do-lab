# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

Passo a Passo para Criação de uma Máquina Virtual (VM) no Azure
1. Acesso ao Portal do Azure:

Login: Acesse o portal do Azure (https://portal.azure.com/) e faça login com suas credenciais.
2. Criação de uma Nova Máquina Virtual:

Pesquisar: Na barra de pesquisa, digite "Máquinas Virtuais" e selecione o serviço.
Criar: Clique em "Criar" e, em seguida, em "Máquina virtual".
3. Configuração da Máquina Virtual:

Detalhes da Instância:
Nome: Defina um nome para sua VM.
Região: Escolha a região do Azure onde sua VM será hospedada.
Grupo de Recursos: Selecione um grupo de recursos existente ou crie um novo para organizar seus recursos.
Imagem: Escolha a imagem do sistema operacional desejado (Windows ou Linux).
Tamanho:
Tamanho: Selecione o tamanho da VM, que define a quantidade de CPU e memória.
Discos:
Disco do Sistema Operacional: Configure o tamanho do disco para o sistema operacional.
Redes:
Rede Virtual: Selecione uma rede virtual existente ou crie uma nova.
Sub-rede: Escolha uma sub-rede dentro da rede virtual.
Endereço IP Público: Se precisar de acesso externo à VM, habilite um endereço IP público.
Gerenciamento:
Monitoramento: Configure as opções de monitoramento, como diagnóstico e alertas.
Extensões: Adicione extensões para funcionalidades adicionais, como o agente do Azure para Linux.
Avançado:
Disponibilidade: Configure opções de alta disponibilidade, como conjuntos de disponibilidade.
4. Revisão e Criação:

Resumo: Revise todas as configurações antes de criar a VM.
Criar: Clique em "Criar" para iniciar o processo de provisionamento da VM.
5. Conexão à Máquina Virtual:

Endereço IP Público: Se você habilitou um endereço IP público, poderá acessar a VM usando o protocolo RDP (para Windows) ou SSH (para Linux).
Conectar: Clique no botão "Conectar" na página da VM para obter as informações de conexão.
