# Atividade-Javascript - Avaliação 2

O grupo deve realizar a implementação da *API* para realizar a inserção de mensagens e a criação de ambiente de leitura das mensagens recebidas (apenas por pessoas autorizadas);

Na página de contato, deve ser implementada a função de "Enviar Mensagem", por meio do uso da função **inserirMensagem(mensagem)** (presente no arquivo `api.js`).

Deve ser criada uma nova página chamada `admin.html`, com um formulário e dois campos: E-mail e Senha. Essa página deve autenticar o e-mail e senha informado por meio da função **validarUsuario(objLoginSenha)** (presente no arquivo `api.js`). Essa função retorna o valor True, caso o e-mail e senha estejam corretos, e False, caso contrário. Se os dados estiverem corretos, a página deve ser redirecionada para uma nova página chamada mensagens.html, senão, mostrar uma mensagem informado "E-mail e Senha inválidos".

Deve ser criada uma nova página chamada `mensagens.html`. Essa página deve carregar todas as mensagens recebidas, utilizando a função **obterMensagens()**. Essa função retorna um Array de objetos contendo as mensagens. Deve ser criada uma tabela, de forma dinâmica, com os dados recebidos.

Alunos: 

