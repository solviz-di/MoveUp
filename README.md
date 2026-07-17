# MoveUp
Repositório destinado ao desenvolvimento do sistema MoveUP, contendo documentação, diagrama UML e protótipo da aplicação
# Equipe:
- Ana Clara Ambrozio Soares
- Brenda Maria da Silva
- Carlos Eduardo Crecencio Silva Sousa
- Maria Clara Alves da Silva
- Nauhana Stephany Marques dos Santos Silva
# Sobre o projeto:
  O MoveUp é uma aplicação desenvolvid para auxiliar no acompanhamento de avaliações físicas, metas e evolução dos usuários.
# Casos de Uso:
Caso de Uso 1 - Realizar Login

Ator: Avaliador / Administrador

Objetivo: Permitir o acesso ao sistema.

Fluxo Normal

1. O usuário abre o aplicativo.
2. O sistema exibe a tela de login.
3. O usuário informa e-mail e senha.
4. O sistema valida as credenciais.
5. O sistema direciona o usuário para a tela principal.

Fluxo Alternativo

* A1. E-mail ou senha incorretos.
    * O sistema informa que os dados são inválidos.
    * O usuário pode tentar novamente.


Caso de Uso 2 – Cadastrar Avaliado

Ator: Avaliador

Objetivo: Registrar um novo avaliado.

Fluxo Normal

1. O avaliador acessa a tela de cadastro.
2. Preenche os dados do avaliado.
3. Clica em “Salvar”.
4. O sistema valida os dados.
5. O cadastro é armazenado.

Fluxo Alternativo

* A1. Algum campo obrigatório não foi preenchido.
    * O sistema informa o erro.
    * O cadastro não é realizado.
      

  Caso de Uso 3 – Registrar Avaliação

Ator: Avaliador

Objetivo: Registrar os resultados da avaliação física.

Fluxo Normal

1. O avaliador seleciona um avaliado.
2. Informa os resultados dos testes.
3. Clica em “Salvar”.
4. O sistema calcula automaticamente a classificação PROESP-BR.
5. A avaliação é armazenada.

Fluxo Alternativo

* A1. Algum valor informado é inválido.
    * O sistema exibe uma mensagem de erro.
    * O usuário corrige os dados.


Caso de Uso 4 – Visualizar Avaliações

Ator: Avaliador / Administrador

Objetivo: Consultar avaliações registradas.

Fluxo Normal

1. O usuário acessa a tela de avaliações.
2. O sistema apresenta a lista.
3. O usuário seleciona uma avaliação.
4. O sistema exibe seus detalhes.

Fluxo Alternativo

* A1. Não existem avaliações cadastradas.
    * O sistema informa que não há registros.




# Links:
  # Protótipo Figma:

  # Documentação:
