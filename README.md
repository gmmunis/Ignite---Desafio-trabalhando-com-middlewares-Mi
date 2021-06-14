<h1 align="center">Desafio 02 🚀</h1>
<p align="center">Ignite - <a href="https://rocketseat.com.br" target="_blank">Rocketseat</a> - Trilha Node js</p>
<h3>💻 Descrição</h3>
<p>Desenvolver middlewares para validação das rotas, com a aplicação de todo já criada. Dessa vez o usuário terá um plano, onde o ele só pode criar até dez todos e um plano Pro que irá permitir criar todos ilimitados.</p>
<h3>🛠️ Funcionalidades</h3>
<ul>
<li>Criar um usuário com name e username</li>
<li>Criar um novo todo</li>
<li>Listar todos os todos;</li>
<li>Alterar o title e deadline de um todo existente;</li>
<li>Marcar um todo como feito;</li>
</ul>
<h3>🔗 Rotas</h3>
<ul>
<li><p style="font-size:30px">POST /users → criar um usuário.</p></li>
<li><p style="font-size:30px">GET /users/:id → pesquisa um usuário pelo id</p></li>
<li><p style="font-size:30px">PATCH /users/:id/pro → atualiza o plano do usuário para PRO caso não seja.</p></li>
<li><p style="font-size:30px">GET /todos → lista com todas as tarefas do usuário.</p></li>
<li><p style="font-size:30px">POST /todos → criar um todo.</p></li>
<li><p style="font-size:30px">PUT /todos/:id → atualiza um todo.</p></li>
<li><p style="font-size:30px">PATCH /todos/:id/done → atualiza a propriedade done do todo para true.</p></li>
<li><p style="font-size:30px">DELETE /todos/:id → deleta um todo pela id.</p></li>
</ul>
<h3>📝 Clonagem e uso</h3>
<p>Clonar o repositório. Entre na pasta do projeto e rode yarn no seu terminal para instalar as dependências.
Com as dependências instaladas rode yarn dev para subir o servidor. Para rodar os testes rode yarn test.
</p>
