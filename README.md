# MoveUp
Repositório destinado ao desenvolvimento do sistema MoveUP, contendo documentação, diagrama UML e protótipo da aplicação
# Equipe:
- Ana Clara Ambrozio Soares
- Brenda Maria da Silva
- Carlos Eduardo Crecencio Silva Sousa
- Maria Clara Alves da Silva
- Nauhana Stephany Marques dos Santos Silva
# Sobre o projeto:
  O MoveUp é uma aplicação desenvolvido para auxiliar no acompanhamento de avaliações físicas, metas e evolução dos usuários.
# Casos de Uso Principais:
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


Caso de Uso 5 – Gerar Relatório PDF

Ator: Avaliador

Objetivo: Gerar um relatório das avaliações.

Fluxo Normal

1. O usuário seleciona uma avaliação.
2. Escolhe “Gerar Relatório”.
3. O sistema reúne os dados.
4. O PDF é gerado.
5. O usuário pode visualizar ou salvar o arquivo.

Fluxo Alternativo

* A1. Não há dados suficientes.
    * O sistema informa que não foi possível gerar o relatório.


Caso de Uso 6 – Exportar Dados

Ator: Avaliador / Administrador

Objetivo: Exportar avaliações para outro formato.

Fluxo Normal

1. O usuário acessa a opção de exportação.
2. Seleciona o formato desejado.
3. O sistema gera o arquivo.
4. O arquivo é disponibilizado para download.

Fluxo Alternativo

* A1. Ocorre uma falha durante a exportação.
    * O sistema informa o erro.
    * O usuário pode tentar novamente.
 
# Casos de Uso Complementares:

Caso de Uso 7 – Editar Avaliado

Ator: Avaliador

Objetivo: Atualizar as informações de um avaliado.

Fluxo Normal

1. O avaliador acessa a lista de avaliados.
2. Seleciona o avaliado desejado.
3. Altera as informações necessárias.
Clica em “Salvar”.
4. O sistema atualiza os dados.
 
Fluxo Alternativo

* A1. Dados inválidos ou obrigatórios não preenchidos.
   * O sistema informa o erro.
   * O avaliador corrige os dados e tenta novamente.

Caso de Uso 8 – Excluir Avaliado

Ator: Avaliador

Objetivo: Remover um avaliado do sistema.

Fluxo Normal

1. O avaliador seleciona um avaliado.
Clica em “Excluir”.
2. O sistema solicita confirmação.
3. O avaliador confirma.
4. O sistema remove o cadastro.
   
Fluxo Alternativo

* A1. O avaliador cancela a exclusão.
   * O sistema mantém o cadastro.
   * Nenhuma alteração é realizada.

Caso de Uso 9 – Editar Avaliação

Ator: Avaliador

Objetivo: Alterar uma avaliação já cadastrada.

Fluxo Normal

1. O avaliador acessa a lista de avaliações.
2. Seleciona uma avaliação.
3. Altera os dados necessários.
Salva as alterações.
4. O sistema atualiza a avaliação.
   
Fluxo Alternativo

* A1. Dados informados são inválidos.
   * O sistema exibe uma mensagem de erro.
   * O avaliador corrige as informações.

Caso de Uso 10 – Excluir Avaliação

Ator: Avaliador

Objetivo: Remover uma avaliação cadastrada.

Fluxo Normal

1. O avaliador seleciona uma avaliação.
Clica em “Excluir”.
2. O sistema solicita confirmação.
3. O avaliador confirma.
4. A avaliação é removida.
   
Fluxo Alternativo

* A1. O avaliador cancela a exclusão.
   * A avaliação permanece cadastrada.

Caso de Uso 11 – Calcular Classificação PROESP-BR

Ator: Sistema (executado durante o registro da avaliação)

Objetivo: Calcular automaticamente a classificação do avaliado.

Fluxo Normal

1. O sistema recebe os dados da avaliação.
2. Processa as informações conforme os critérios do PROESP-BR.
3. Calcula a classificação.
4. Exibe o resultado.
   
Fluxo Alternativo

* A1. Dados insuficientes para o cálculo.
   * O sistema informa que não foi possível calcular.
   * O avaliador deve completar os dados.

Caso de Uso 12 – Sincronizar Google Planilhas

Ator: Avaliador

Objetivo: Sincronizar os dados do sistema com o Google Planilhas.

Fluxo Normal

1. O avaliador acessa a opção de sincronização.
2. O sistema conecta ao Google Planilhas.
Os dados são sincronizados.
3. O sistema informa que a sincronização foi concluída.
   
Fluxo Alternativo

* A1. Falha na conexão.
   * O sistema informa o erro.
   * O avaliador pode tentar novamente.

Caso de Uso 13 – Acessar Área da Ajuda

Ator: Usuário / Avaliador

Objetivo: Consultar orientações sobre o uso do sistema.

Fluxo Normal

1. O usuário acessa a Área da Ajuda.
2. O sistema apresenta as orientações e vídeos explicativos.
3 O usuário consulta as informações desejadas.

Fluxo Alternativo

* A1. O conteúdo não está disponível.
   * O sistema informa indisponibilidade temporária.

Caso de Uso 14 – Consultar Política de Privacidade

Ator: Usuário

Objetivo: Visualizar a política de privacidade do sistema.

Fluxo Normal

1. O usuário acessa a opção “Política de Privacidade”.
2. O sistema exibe o documento.
3. O usuário consulta as informações.
   
Fluxo Alternativo

* A1. O documento não pode ser carregado.
   * O sistema informa o erro.
   * O usuário pode tentar novamente mais tarde.
# Links:
  # Protótipo Figma: 
https://www.figma.com/make/ciV8MWfvES4QA05w2IWWXK/User-Authentication-Screens?t=uDod0prtS9BKqev0-1

