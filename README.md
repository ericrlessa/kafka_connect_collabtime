# kafka_connect_collabtime

Criar a tabela no container do mysql:

CREATE TABLE IF NOT EXISTS product (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255) NOT NULL,
    price decimal(10,4) NOT NULL
);
