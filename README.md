# Banco-de-Dados-Mysql
Meu Primeiro Projeto de Banco de Dados 
// 1 - Crie um novo banco de dados no MySQL usando o seguinte comando:

CREATE DATABASE IF NOT EXISTS notas_fiscais;

// 2 - Use o banco de dados recém-criado:

USE notas_fiscais;

// 3 - Crie uma tabela chamada "notas_fiscais" com as colunas necessárias:

CREATE TABLE IF NOT EXISTS notas_fiscais (
  id INT AUTO_INCREMENT PRIMARY KEY,
  numero VARCHAR(50),
  data DATE,
  valor_total DECIMAL(10, 2),
  cliente VARCHAR(100),
  endereco VARCHAR(200),
  cidade VARCHAR(100),
  estado VARCHAR(50)
);
