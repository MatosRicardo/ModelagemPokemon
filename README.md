# Atividade de Modelagem de Banco de Dados - Pokémon

Durante os estudos de **Banco de Dados** no Instituto PROA, realizei uma atividade prática de modelagem, criando um banco de dados para gerenciar informações do universo Pokémon. 
## Estrutura do Banco de Dados

- **Tabela: Pokémon**  
  - Colunas: `id`, `nome`, `tipo`, `nível`, `id_treinador`, `id_fazenda`.  
  - Relacionamentos: Cada Pokémon pertence a um treinador e pode estar registrado em uma fazenda.

- **Tabela: Treinador**  
  - Colunas: `id`, `nome`, `idade`, `cidade_origem`.  
  - Relacionamentos: Um treinador pode possuir vários Pokémons.

- **Tabela: Fazenda**  
  - Colunas: `id`, `nome`, `localização`, `capacidade`.  
  - Relacionamentos: Uma fazenda pode abrigar múltiplos Pokémons.

## Objetivo da Atividade

O objetivo foi entender os conceitos de modelagem relacional, identificar chaves primárias e estrangeiras, e construir relações entre as tabelas. Essa atividade ajudou a consolidar o entendimento de como organizar dados de forma e
