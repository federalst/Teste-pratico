<p align="center"><img src="http://site.federalst.com.br/fsmail.jpg"></p>


# Teste prático - Federal Soluções Técnicas

## Instalação 
* Execute composer install
* Renomeie o arquivo .env.example para .env
* Configure o acesso do seu banco de dados postgree no arquivo .env
* Execute php artisan key:generate
* Execute php artisan migrate
* Execute php artisan db:seed

Esse é o teste prático - Federal Soluções Técnicas.
`Laravel 5.6` 
# Objetivos
  - Conhecer as habilidades em:
    - Programação PHP/Laravel (Conhecimentos básicos sobre Laravel)
    - Conhecimentos com PostgreSql
    - Organização (código/arquivos)
    - Controle de versão (Git)
    - Análise/Entendimento de requisitos
    - Capacidade de cumprir prazos
    - Determinação na busca novos conhecimentos

# Atenção
  - Tudo que for desenvolvido nesse teste não será comercializado ou utilizado comercialmente pela Federal ST ou algum de seus associados.
  - A única intenção é avaliar o conhecimento atual do candidato.

# Aplicação
Você deverá desenvolver uma simples aplicação, com login e nível de acesso simples.

O administrador do sistema deverá realizar a manutenção dos veículos. Os dados para a tabela de veículos são:
 - Placa
 - Renavam
 - Modelo
 - Marca
 - Ano
 - Proprietário
 
Todas as vezes que um veículo for cadastrado ou editado, deverá ser enviado um e-mail para o proprietário.

O e-mail do proprietário deverá ser buscado na tabela de usuários.

O CRUD do veículo deverá ficar em uma área de administração. O proprietário não poderá ter acesso a essa área.

Deverá haver uma área destinada ao proprietário. O proprietário deverá ser capaz de visualizar todos os seus veículos. Ele não pode editar, excluir ou cadastrar novos veículos, apenas visualizar.

### Usuários
Existem dois tipos diferentes de usuários na aplicação:
- Administrador
- Usuário

### Requisitos
- [ ] Usar Laravel
- [ ] Usar banco de dados Postgres
- [ ] Utilizar Soft Deleting ao excluir veículos.
- [ ] Não ter regra de negócio nos Controllers.
- [ ] Usar Event e Notifications para enviar os e-mail.
- [ ] Deixar informações no README.MD sobre como podemos executar sua aplicação.
- [ ] Usar o github.

### Validações
Os campos abaixo só podem ser aceitos no formato:
- Placa: Formato com três letras e quatro números (AAA1111).
- Ano: Formato apenas com números com, no máximo, 4 dígitos.

### Como participar?
- Fazer o fork desse repositório.
- Nos enviar o link do projeto do Github.

#### Dicas após baixar o projeto:
- Rode as migrations.
- Rode as seeders.
- Esteja atento aos usuários padrões contidos na Seeder.
- A senha dos usuários é 'secret'.

# Contato
- Email: suporte@federalst.com.br
- Telefone: 62 3414-9089

Entre em contato conosco, caso você tenha alguma dúvida ou quando terminar o projeto.

# Tempo de execução
- Você tem 2 dias pra realizar esse teste prático.

## SUBMETA SEU PROJETO, MESMO QUE VOCÊ NÃO O TERMINE. NESTE CASO, NOS EXPLIQUE QUAIS FORAM AS SUAS DIFICULDADES. 



