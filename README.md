Perguntas de conclusão
1.  Explique por que o método GET é utilizado para listar produtos e quais são os benefícios de utilizar esse método em uma API RESTful.

        R: O GET é usado para listar os produtos porque ele apenas busca e mostra as informações que estão salvas, sem mudar nada no servidor, e os benefícios são padronizar a consulta de dados e facilitar a comunicação entre sistemas diferentes de forma segura.

3.  Por que o método POST é o mais adequado para adicionar novos produtos em uma API RESTful? Descreva o que ocorre no servidor quando o método POST é chamado.

        R: O POST é o mais adequado para adicionar produtos porque ele foi feito justamente para enviar dados novos para o servidor. Quando ele é chamado, o servidor pega as informações em JSON que foi mandado, adiciona o novo item na lista e avisa que foi criado com sucesso (código 201).

4.  Descreva o funcionamento do método DELETE em uma API RESTful. O que acontece quando tentamos remover um recurso que não existe e como a API deve responder nesse caso?

        R: O DELETE funciona encontrando um produto específico pelo ID na URL para poder apagá-lo. Quando tentamos apagar um recurso que não existe, o servidor não acha o item, e a API deve responder a esse caso retornando o código de erro 404 junto com uma mensagem de aviso informando que o produto não foi encontrado.
