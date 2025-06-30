# az104-lab01-newvm
Resumo da Etapa de Implantação de Máquina Virtual na AZ-104

# Pré-requisitos
Ter uma assinatura ativa do Azure

Ter permissões de colaborador ou proprietário no grupo de recursos

# Passos para Implantação de VM no Azure (AZ-104)
## 1. Acessar o Portal Azure

- Acesse o **[Portal do Azure](https://portal.azure.com/)**;

## 2. Criar a Máquina Virtual

- Clicar em "Criar um recurso" > "Máquina Virtual"

## 3. Configurações Básicas

- Selecionar a assinatura

- Criar ou selecionar um grupo de recursos

- Definir nome da VM

- Selecionar região (localização)

- Escolher opções de disponibilidade (se necessário)

- Selecionar imagem do sistema operacional (Windows Server ou Linux)

## 4. Tamanho da Instância

- Escolher o tamanho adequado (CPU, memória, desempenho)

- Verificar custos estimados

## 5. Conta de Administrador

- Para Windows: definir nome de usuário e senha

- Para Linux: definir nome de usuário e chave SSH

## 6. Regras de Portas de Entrada

- Selecionar portas abertas (RDP 3389 para Windows, SSH 22 para Linux)

- Opção de usar Azure Bastion

## 7. Discos

- Tipo de disco do SO (Standard HDD, Standard SSD, Premium SSD)

- Configurar discos de dados adicionais (se necessário)

## 8. Rede

- Configurar rede virtual (VNet) e sub-rede

- Definir IP público (ou não)

- Configurar Grupo de Segurança de Rede (NSG)

## 9. Gerenciamento

- Configurar monitoramento e diagnósticos

- Definir políticas de desligamento automático (opcional)

## 10. Advanced/Advanced Tags

- Adicionar tags para organização (opcional)

## 11. Revisar + Criar

- Validar as configurações

- Clicar em "Criar" para iniciar a implantação

## 12. Monitorar Implantação

- Acompanhar o progresso no portal

- Verificar notificações para conclusão

## 13. Pós-Implantação
- Conectar à VM via RDP/SSH

- Verificar conectividade e recursos

- Configurar backups (Azure Backup)

- Implementar políticas de segurança adicionais

Esta etapa é fundamental no exame AZ-104, testando o conhecimento sobre configurações de VM, rede, armazenamento e gerenciamento no Azure.
