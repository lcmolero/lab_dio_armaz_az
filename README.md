# lab_dio_armaz_az
Laboratório DIO sobre Armazenamento na Azure

# Dominando o Armazenamento na Azure

## Introdução
Este readme aborda as os principais pontos vistos no laborátorio Dominando o Armazenamento na Azure.

## Tópicos

### 1. Comparando os Serviços de Armazenamento da Azure
- **Tipos de Armazenamento**: A Azure oferece diversos tipos de armazenamento, incluindo Blob Storage, File Storage, Queue Storage e Table Storage. Cada um serve a diferentes propósitos e necessidades de armazenamento.

### 2. Descrição das Camadas de Armazenamento
- **Camadas de Acesso**: As camadas incluem Hot, Cool e Archive, cada uma adequada para diferentes padrões de uso e retenção de dados.
- **Hot Tier**: Para dados que são acessados com frequência.
- **Cool Tier**: Para dados acessados raramente e armazenados por longos períodos.
- **Archive Tier**: Para dados raramente acessados e armazenados por longos períodos, onde a latência de recuperação pode ser alta.

### 3. Opções de Redundância
- **LRS (Locally Redundant Storage)**: Armazena três cópias dos dados em uma região.
- **GRS (Geo-Redundant Storage)**: Armazena seis cópias dos dados em duas regiões geograficamente distantes.
- **RA-GRS (Read-Access Geo-Redundant Storage)**: Igual ao GRS, mas permite leitura dos dados na região secundária.
- **ZRS (Zone-Redundant Storage)**: Armazena dados de forma redundante em três zonas dentro de uma região.

### 4. Contas de Armazenamento e Tipos de Armazenamento
- **Contas de Armazenamento**: Contas gerais (v1 e v2) e contas Blob Storage.
- **Tipos de Armazenamento**: Incluem Blob Storage (para grandes quantidades de dados não estruturados), File Storage (para compartilhamentos de arquivos gerenciados), Queue Storage (para mensagens de fila) e Table Storage (para armazenamento NoSQL).

### 5. Opções para Mover Arquivos
- **AzCopy**: Ferramenta de linha de comando para copiar dados de e para a Azure Storage.
- **Gerenciador de Armazenamento do Azure**: Interface gráfica para gerenciar e mover dados na Azure.
- **Sincronização de Arquivos do Azure**: Sincroniza pastas do Windows Server com compartilhamentos de arquivos na Azure.

### 6. Opções de Migração
- **Migrações para Azure**: Ferramentas e serviços para mover dados para a Azure, incluindo Azure Migrate.
- **Azure Data Box**: Dispositivos físicos para transferência de grandes volumes de dados para a Azure.
