Link da página hospedada: https://wpfsilva.000webhostapp.com/

Foi utilizado muito bootstrap, um pouco de CSS, javascript e PHP,já fiz questão de fazer o uso do Banco de Dados como aprendizado. As verificações estão todas funcionando no formulário, visto que todos os essenciais se encontram, no formulario foi usado Input do tipo text, text area, radios e checkbox. Só abre o modal se tudo estiver correto, todos os botões pedidos no modal foram adicionados.
Todos os tratamentos pra evitar SQL Injection e XSS Injection foram inseridos.

Utilizado o PHP Data Objects ( PDO https://www.php.net/manual/pt_BR/book.pdo.php ) pra fazer a conexão, inserção e os querys no banco.
O método prepare $pdo->prepare(...) prepara a consulta tratando os valores fornecidos como dados e não como parte da instrução SQL.

O footer e o header são incluídos através do include "pagina.php" como pedido, com isso surgiu um problema de como deixar o ativo na cor, então inseri um script pra cada página, foi meio que uma gambiarra, mas é o q eu pensei na hora, talvez eu pense futuramente em outra forma.

A pagina ver_bd.php, retorna todos as linhas do banco de dados.

Na segunda fase atualizo com mais coisas caso seja necessário!