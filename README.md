###Criar CRUD de usuários

Nesta fase, a responsabilidade será desenvolver os códigos necessários para o novo CRUD (create, read, update e delete) de usuários.
Os testes desta atividade seguirão sendo realizados no aplicativo Insomnia.

Ao pressionar o botão SEND, o resultado aparecerá na janela à direita. O 200 OK é o código de resposta para requisição bem-sucedida
![Logo da Minha Empresa](https://github.com/diegobrl/crud-usuarios-api/blob/main/screenshot/0001.png)

Agora, teste o método Cadastrar (POST). Escolha o método POST.

![Logo da Minha Empresa](https://github.com/diegobrl/crud-usuarios-api/blob/main/screenshot/0002.png)

Você pode visualizar a lista de itens do banco de dados no novo projeto, alterando o método para GET e clicando em SEND. Os itens serão exibidos na janela lateral, conforme mostrado na imagem.
![Logo da Minha Empresa](https://github.com/diegobrl/crud-usuarios-api/blob/main/screenshot/0003.png)

Você também pode utilizar o método GET para visualizar registros individuais. Basta inserir a URL http://localhost:5038/api/usuarios/3 — substituindo o número 3 por outro ID que deseja consultar — e clicar em SEND. Nesse exemplo, o resultado exibirá o terceiro item do banco de dados.

![Logo da Minha Empresa](https://github.com/diegobrl/crud-usuarios-api/blob/main/screenshot/0004.png)

Substitua o código pelo indicado abaixo para atualizar o item 3 e clique em SEND. O resultado será o código 204 (indicação de que a solicitação foi realizada com sucesso), conforme definido na função Atualizar da classe UsuariosController.cs.

![Logo da Minha Empresa](https://github.com/diegobrl/crud-usuarios-api/blob/main/screenshot/0005.png)

![Logo da Minha Empresa](https://github.com/diegobrl/crud-usuarios-api/blob/main/screenshot/0006.png)

![Logo da Minha Empresa](https://github.com/diegobrl/crud-usuarios-api/blob/main/screenshot/0007.png)
