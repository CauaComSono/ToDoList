# ToDoList
Repo dedicado ao último trabalho do professor Elenilton

Eu escolhi fazer uma lista da afazeres(To Do List) com Spring Boot e um Banco de Dados em Memória(H2), nesta lista você pode criar usuários, cadastrar tarafes, listar as tarafes e atualiza-las.

Para podermos fazer as request para cadastrar o usuário ou as tarafes será necessário utilizar Rest Client como Insomnia, Postman ou Apidog, no meu caso vou estar utilizando do Apidog.

Para cadastrar um usuário será necessário colocar seguinte url http://localhost:8080/users/ com o metodo POST, já no json você utilizará "name", "username", "password".

![image](https://github.com/CauaComSono/ToDoList/assets/130913401/c6b61320-ca6e-4dd9-b934-ca783bbcb0a7)

Já para cadastrar a tarefa será necessário colocar a url http://localhost:8080/tasks/ com o metodo POST, já no json você utilizará "title", "description", "priority", "startAt", "endAt".


![image](https://github.com/CauaComSono/ToDoList/assets/130913401/4881c21d-fa51-408b-ac16-677743fb0f74)

Também será necessário ir na aba Auth e colocar seu username e sua senha

![image](https://github.com/CauaComSono/ToDoList/assets/130913401/25a8f6b2-f58c-4b2b-80dd-a02e7f6da59c)

Para listar as tarefas, você usa a mesma url para cadastrar a tarefa mas o Metodo será o GET para poder listar as tarefas.

![image](https://github.com/CauaComSono/ToDoList/assets/130913401/369059f5-a8a0-4e55-ad54-472f3e43fb30)

Já para atualizar a tarefa, você usará a mesma url para cadastar a tarefa juntamente com o id da tarefa que deseja atualizar e utulizará o metodo PUT.
Você escolherá o que quer atualizar nela no json, e irá verificar se o usuário tem permissão para atualizar essa tarefa.

![image](https://github.com/CauaComSono/ToDoList/assets/130913401/87e8a764-3d59-48f3-9f1f-47129e301c6c)
![image](https://github.com/CauaComSono/ToDoList/assets/130913401/6ce4783d-1831-4793-8a4e-d16997f1db54)


Você também pode acessar o banco de dados em localhost:8080/h2-console

Username para acessar o banco: admin

Senha para acessar o banco: admin


