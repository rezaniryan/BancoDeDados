**PARTE 1 E 2**

Este projeto SQL cria uma tabela chamada Produtos para gerenciar informações sobre produtos alimentícios. Ele inclui a definição da tabela, inserção de dados e diversas consultas para análise.

**Estrutura da Tabela**
A tabela Produtos contém os seguintes campos:
id_produto: Identificador único (INT, chave primária)
nome: Nome do produto (VARCHAR, não nulo)
preco: Preço do produto (DECIMAL, não nulo)
estoque: Quantidade em estoque (INT, não nulo)
perecivel: Indica se o produto é perecível (BOOLEAN, não nulo)
marca: Marca do produto (VARCHAR)
nacionalidade: Nacionalidade do produto (VARCHAR)
**Funcionalidades**
Inserção de Dados: Insere cinco produtos de exemplo na tabela.
Consultas:
Selecionar todos os produtos.
Contar o total de produtos.
Calcular o preço médio.
Agrupar produtos por tipo (perecível e não perecível) e calcular a média de preço.
Encontrar o produto mais caro.
Listar produtos com preço acima da média.
Contar produtos por nacionalidade.
**Como Usar**
Execute o script SQL em um banco de dados compatível (MySQL, PostgreSQL, etc.).
Utilize as consultas para obter insights sobre os produtos.

**PART 3**

**Resumo do Projeto**
Este projeto SQL cria duas tabelas: Cidades e Alunos, para gerenciar informações sobre cidades e seus respectivos alunos. O script inclui a definição das tabelas, inserção de dados e consultas para análise das relações entre alunos e cidades.

**Estrutura das Tabelas**
Tabela: Cidades
id: Identificador único da cidade (INT, chave primária)
nome: Nome da cidade (VARCHAR, não nulo)
populacao: População da cidade (INT)
Tabela: Alunos
id: Identificador único do aluno (INT, chave primária)
nome: Nome do aluno (VARCHAR, não nulo)
data_nasc: Data de nascimento do aluno (DATE)
cidade_id: Identificador da cidade (INT, chave estrangeira referenciando Cidades(id))
**Funcionalidades**
Inserção de Dados:
Insere cinco cidades com suas populações.
Insere doze alunos, alguns associados a cidades, outros sem associação.

**Como Usar**
Execute o script SQL em um banco de dados compatível (MySQL, PostgreSQL, etc.).
Utilize as consultas para obter informações sobre alunos e suas cidades.

