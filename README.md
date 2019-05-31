# Direto ao Ponto

**Disciplina:**  Programação para Dispositivos Móveis

**Integrantes**  [Deivid Francis](https://github.com/DeividFrancis), [Itamar Alves](https://github.com/ItamarAlves), [Igor Almeida](https://github.com/IgorAlmeidabrt), [Bruno Rocha](https://http.cat/404)

**Tema:** Controle de ponto

**Entrega:** 03/06/2019

***

## Objetivos

- [X] O App deve ter uma tela para login com usuário e senha.

- [X] Uma tela que liste os usuários cadastrados.

- [X] A tela que lista o usuário, só pode ser vista pelo usuário de nível
"gerente" e ele pode excluir registros de lá.

- [X] Todos os dados devem ser armazenados em banco de dados.

- [X] O login deverá ter a opção para saber se quer "lembrar" dele para que
no próximo login ele já mostre o login do último usuário que logou e ao
entrar mostrar a data num “toast” da última vez que entrou na
aplicação. (salvar isso nas SharedPreferences).

- [X] Ter além da tabela de usuários, pelo menos mais 1 para armazenar
dados sobre o negócio da aplicação, ao menos um campo dessa outra
tabela tem que ser do tipo data.

- [X] Deverá usar os seguintes componentes obrigatóriamente (spinner,
progresssbar, SearchView e listas).

## Geral 
- Toda ação tem como retorno um `Toast` para dar um feedback para o usuário.

- Menu > Sair, faz logoff do usuário ativo, e desabilita a opção "Salvar senha", direcionando novamente para a tela de login.

## Telas

## SplashScreen

Simula o load necessário para carregar todo o APP. 

### Login

- [x] Entrar
- [x] Lembrar senha
- [x] Recuperar senha

### Cadastro
Uma pessoa pode se cadastrar, e o Gerente pode cadastrar uma nova pessoa pela tela de Usuários.

- [x] Selecionar papel (Spinner) 
- [x] Prencher dados
- [x] Mascaras (Cpf, Telefone)
- [x] Valida os dados (Cpf, E-mail, Senha) `progress bar`
- [x] Salva
- [x] Atualiza / Excluir (Somente Gerente)

### Dashboard

- [x] Mostra data e nome do usuário do último login `SharedPreferences`
- [x] Registar ponto (Somente pessoa logada)
- [X] Lista pontos
- [X] Atualiza lista de pontos `RefreshView`
- [X] Edita ponto (Somente Gerente) `TimePicker`
- [X] Dados do usuário logado / selecionado (Nome e papel)
- [X] Menu (item "usuários" visivel somente para gerente)

### Usuários
    
Visível somente para o gerente. 

- [X] Lista de usuários (Ordem alfabetica)
- [X] Pesquisa por nome `SearchView`
- [X] Cadastrar um novo usuário.
- [X] Click simples, exibe lista de pontos da pessoa selecionada
- [X] Click longo, edita ou exclui pessoa selecionada
- [X] Menu
