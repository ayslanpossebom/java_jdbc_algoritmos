Arquivo **ConexaoBD.jar**: usado para conexão com MySQL
ConexaoMySQL con = new ConexaoMySQL(
    "localhost", 3306, "database", "usuario", "senha"
);

Arquivo **ConexaoPostgreSQL.jar**: usado para conexão com PostgreSQL
ConexaoPostgreSQL con = new ConexaoPostgreSQL(
    "localhost", 5432, "database", "usuario", "senha"
);
