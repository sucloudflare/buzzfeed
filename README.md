 <h1>Aplicativo de teste do BuzzFeed</h1>
    <p>Este é um projeto de aplicativo Angular para criar e responder a quizzes divertidos no estilo do BuzzFeed. Você pode personalizar facilmente os quizzes adicionando perguntas, opções e resultados.</p>

   <h2>Como usar</h2>
    <ol>
        <li>Clone este repositório para o seu ambiente local.</li>
        <li>Certifique-se de ter o Angular CLI instalado. Se não tiver, você pode instalá-lo globalmente com o seguinte comando:</li>
    </ol>
    <code>
        npm install -g @angular/cli
    </code>
    <ol start="3">
        <li>Navegue até o diretório do projeto e instale as dependências:</li>
    </ol>
    <code>
        cd buzzfeed-quiz-app<br>
        npm install
    </code>
    <ol start="4">
        <li>Inicie o servidor de desenvolvimento:</li>
    </ol>
    <code>
        ng serve
    </code>
    <p>Abra seu navegador e vá para <a href="http://localhost:4200/">http://localhost:4200/</a> para ver o aplicativo em ação.</p>
    <h2>Personalização</h2>
    <p>Você pode personalizar facilmente os quizzes alterando o arquivo <code>quizz.component.html</code>. Aqui estão algumas coisas que você pode fazer:</p>
    <ul>
        <li>Alterar o título do quiz: Você pode alterar o título do quiz atualizando a variável <code>title</code> dentro do componente.</li>
        <li>Adicionar perguntas e opções: Você pode adicionar mais perguntas e opções editando o arquivo <code>quizz.component.html</code>. Basta copiar e colar os elementos <code>&lt;div class="quizz_questions"&gt;</code> e <code>&lt;div class="quizz_options"&gt;</code> e ajustar os textos conforme necessário.</li>
        <li>Editar resultados: Os resultados finais do quiz são exibidos quando todas as perguntas foram respondidas. Você pode editar a aparência dos resultados ou adicionar mais detalhes conforme desejado.</li>
        <li>Reiniciar o quiz: Um botão de reinicialização é fornecido para permitir que os usuários reiniciem o quiz. Você pode ajustar o comportamento do botão de reinicialização conforme necessário.</li>
    </ul>

  <h2>Recursos</h2>
    <ul>
        <li>Angular CLI: Este projeto foi criado com o Angular CLI, facilitando a construção, teste e implantação de aplicativos Angular.</li>
        <li>Bootstrap: O Bootstrap é usado para estilos básicos e responsividade, facilitando a criação de interfaces de usuário atraentes e funcionais.</li>
        <li>FontAwesome: FontAwesome é utilizado para ícones, adicionando um toque visual extra ao aplicativo.</li>
    </ul>
    <p>Sinta-se à vontade para explorar e personalizar o projeto de acordo com suas necessidades e criatividade! Se você tiver alguma dúvida ou problema, não hesite em entrar em contato. Divirta-se criando quizzes incríveis! 🎉</p>
