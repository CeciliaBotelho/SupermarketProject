# Sistema de Gerenciamento de Supermercado 🛒

Bem-vindo(a) ao repositório do Sistema de Gerenciamento de Supermercado! Este projeto é uma aplicação em Java que utiliza banco de dados para gerenciar as operações diárias de um supermercado. 🏪

## Tecnologias Utilizadas 🛠️

Este sistema foi construído utilizando:

- **Java**: A linguagem de programação escolhida para o desenvolvimento do backend.
- **MySQL**: Para o gerenciamento de banco de dados.
- **JDBC**: Para conectar a aplicação Java com o banco de dados MySQL.

## Funcionalidades 🌟

- **Gestão de Produtos**: Inclui adicionar, visualizar, atualizar e remover produtos do inventário.
- **Gestão de Vendas**: Permite a realização e rastreamento de vendas.
- **Relatórios**: Gera relatórios sobre vendas, estoque e outros dados relevantes.

## Estrutura do Projeto 📂

- `Guanabarays_dump_banco`: Dump do banco de dados MySQL.
- `build`: Diretório contendo arquivos compilados da aplicação.
- `nbproject`: Metadados do projeto se estiver usando NetBeans ou similar.
- `src/br/com/guanabaris`: Código-fonte Java da aplicação.
- `build.xml`: Arquivo de construção do Apache Ant, se aplicável.
- `guanabarays_comandos.sql`: Comandos SQL utilizados no projeto.
- `manifest.mf`: Arquivo de manifesto para aplicações Java.
- `mysql-connector-java`: Driver JDBC para MySQL.
- `rs2xml.jar`: Biblioteca para exibir os resultados do banco de dados em tabelas Java Swing.
- `tabelaDER.mwb`: Modelo de banco de dados MySQL Workbench.

## Configuração e Execução 🚀

1. **Configuração do Banco de Dados**

   Restaure o dump do banco de dados (`Guanabarays_dump_banco`) em sua instalação MySQL.

2. **Compilação do Projeto**

   Se estiver usando um IDE, importe o projeto e compile. Se estiver usando a linha de comando:

   javac -d build src/br/com/guanabaris/*.java


## Execução

Execute o programa principal a partir do diretório build.

java -cp .:mysql-connector-java-8.0.31.jar:rs2xml.jar br.com.guanabaris.Main
Nota: Atualize o classpath conforme necessário para as suas configurações.

## Contribuindo 🤝
Se você tem uma ideia ou encontrou um bug, por favor, sinta-se à vontade para contribuir! Faça um fork deste repositório, crie uma branch para suas mudanças e envie um pull request.

## Entre em Contato 📬

- Nome - Cecilia Botelho.
- E-mail - cescbotelho@gmail.com

