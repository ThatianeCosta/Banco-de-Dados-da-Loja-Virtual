# Banco de Dados da Loja Virtual 🛢

- O objetivo deste projeto foi criar a estrutura de um banco de dados utilizando a linguagem SQL, com base em um Diagrama Entidade-Relacionamento previamente definido. Após a criação das tabelas, inseri dados no banco de dados que desenvolvi. Em seguida, realizei consultas nos dados armazenados por meio da criação de uma VIEW, o que me permite visualizar as informações de maneira organizada e acessível.

<div>
  <img src="Banco de Dados/DER.png" width="500px">
</div>

# Como funciona: 📌
<table>
  <thead>
    <tbody>
      <tr>
      <td> • Criei uma base de dados chamada 'Loja' utilizando MySQL Server por meio do MySQL Workbench. Para isso, adicionei as estruturas de dados necessárias nesse banco, utilizando os comandos de definição de dados (DDL) da linguagem SQL, conforme o modelo que está definido no Diagrama Entidade-Relacionamento (DER) que eu tenho.</td>
      </tr>
      <tr> 
        <td>• Durante a criação do banco de dados conforme a figura, segui algumas regra importantes. Primeiro, defini todas as chaves primárias como autoincremento. Além disso, respeitei os relacionamentos,   tipos, precisões e restrições de não nulo para garantir a integridade dos dados </td>
      </tr>
      <tr>
        <td> • Especificamente, para o campo <b>'Situação' na tabela 'ContaReceber'</b>, optei por utilizar o tipo ENUM, limitando os valores a três opções: <br/>  <b>1 - Conta registrada</b>, <b> 2 - Conta cancelada</b> e <b>3 - Conta paga</b>.</td>
      </tr>
      <tr>
        <td> • Criei um script chamado "inserir.sql" que contém os comandos de manipulação de dados (DML). O objetivo desse script é popular todas as tabelas que existem na base dados. Para isso, inseri pelo menos três registros em cada tabela, garantindo que os dados fossem adequadamente preenchidos e representassem as informações necessárias para o funcionamento da aplicação.</td>
      </tr>
      <tr>
        <td> • Utilizei os comandos de consulta (DQL) da linguagem SQL para elaborar um script chamado "consulta.sql". Nesse script, criei uma visão (VIEW) que retorna todas as contas que ainda não foram pagas, ou seja, aquelas com a Situação Igual a 1. A visão inclui as seguintes informações: o ID da conta a receber, o nome e o CPF do cliente associado à conta e o valor da conta. Dessa forma, consigo obter uma visão clara das contas pendentes.</td>
      </tr>
      </tbody>
  </thead>
</table>


# Tecnologias Utilizadas: 🛠️

- <b>SQL:</b> Utilizada para a criação da estrutura do banco de dados, inserção de dados e consultas.
  
- <b>MySQL Workbench:</b> Ferramenta utilizada para design, desenvolvimento e administração do banco de dados MySQL.

- <b>MySQL Community Server:</b> Usado como o SGBD para armazenar e gerenciar os dados do projeto.

- <b>Diagrama Entidade-Relacionamento (DER):</b> Ferramenta para modelagem da estrutura do banco de dados.
