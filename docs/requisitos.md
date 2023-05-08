# Superjunto - Requisitos

# Visão Geral

O Superjunto é um aplicativo que permite que usuários que moram na mesma região possam compartilhar listas de compras e encontrar outras pessoas para fazer compras juntas em um supermercado local. Os usuários podem atualizar a lista com base nos preços do supermercado e colaborar com outros usuários para manter uma base de dados colaborativa para preços de supermercados na região.

# Requisitos Funcionais

## Registro

- O usuário poderá criar uma conta no Superjunto informando seu nome completo, e-mail e senha.
- O usuário será solicitado a fornecer informações adicionais, como endereço, número do apartamento, nome do prédio ou nome da comunidade.
- O usuário deve concordar com os termos e condições do aplicativo antes de concluir o registro.
- Após concluir o registro, o usuário receberá um e-mail de confirmação para ativar sua conta.
- O administrador da comunidade deve confirmar que o usuário pertence àquela região antes que a conta seja totalmente ativada.

### Login

- O usuário poderá fazer login no Superjunto usando seu e-mail e senha cadastrados.
- O usuário poderá optar por salvar suas informações de login para acesso mais rápido no futuro.
- Se o usuário esquecer sua senha, ele poderá solicitar uma redefinição de senha por e-mail.
- O usuário não poderá fazer login até que sua conta tenha sido totalmente ativada pelo administrador da comunidade.

## Gerenciamento de Listas de Compras

- O usuário poderá criar uma lista de compras e adicionar itens a ela.
- O usuário poderá editar ou excluir itens de sua lista de compras.
- Ao adicionar um produto a lista de compras, o usuário deverá receber o preço médio nacional do produto, se disponível.
- Se houver dados de preços de supermercados próximos já cadastrados, o usuário poderá visualizar os preços dos produtos nesses supermercados.
- Quando o usuário estiver no supermercado, o aplicativo deve permitir que o usuário insira o preço e a quantidade dos produtos, informando o total da compra.
- Ao inserir o preço do produto e o supermercado, estes dados vão para a base de dados compartilhada.
- O usuário poderá compartilhar sua lista de compras com outros usuários da mesma região.
- Os usuários poderão colaborar em uma lista de compras em tempo real e ver as atualizações em tempo real.
- O aplicativo permitirá que os usuários classifiquem os itens por categoria para facilitar as compras no supermercado.

## Encontrar Companheiros de Compras

- Os usuários poderão ver outros usuários da mesma região que estão procurando por companheiros de compras.
- Os usuários poderão entrar em contato uns com os outros através do aplicativo para combinar um horário e local de encontro no supermercado.
- O aplicativo permitirá que os usuários classifiquem outros usuários por proximidade geográfica e interesse em comum em itens de sua lista de compras.

## Criação de Comunidade

- O Superjunto deve ter um processo seguro e confiável para permitir a criação de novas comunidades.
- Os usuários interessados em criar uma nova comunidade devem fornecer informações de contato e endereço para verificação.
- O Superjunto deve permitir que apenas um usuário seja definido como administrador da comunidade.
- O administrador da comunidade deve ser capaz de fornecer informações para verificação de sua identidade, como cópia de documentos pessoais ou comprovante de residência.
- A validação do cadastro da comunidade e de seu administrador deve ser realizada manualmente por um representante do Superjunto.
- O processo de validação manual deve incluir a verificação de informações fornecidas pelo usuário, como endereço e documentos de identidade.

### Gerenciamento de Comunidade

- O administrador da comunidade poderá editar informações gerais da comunidade, como nome e endereço.
- O administrador da comunidade poderá adicionar e remover usuários da comunidade.
- Apenas o administrador da comunidade poderá aprovar novos usuários para se juntar à comunidade.
- O administrador da comunidade poderá enviar notificações aos usuários da comunidade sobre eventos ou atualizações importantes do Superjunto.

## Funcionalidades de Compartilhamento de Preços

- O aplicativo permitirá que os usuários vejam uma lista de preços de supermercados próximos.
- Os usuários poderão colaborar para manter uma base de dados colaborativa com preços de supermercados na região.
- Os usuários poderão adicionar novos preços e atualizar preços existentes de produtos em supermercados próximos.

# Requisitos Não-Funcionais

- O aplicativo deve proteger a privacidade dos usuários, garantindo que seus dados pessoais e de compra sejam mantidos em sigilo e só sejam compartilhados com outros usuários com sua permissão.
- O aplicativo deve ser desenvolvido com medidas de segurança adequadas para proteger os dados dos usuários, como senhas criptografadas, autenticação de dois fatores e certificados SSL.
- O aplicativo deve ser fácil de usar e ter uma interface intuitiva.
- O aplicativo deve ser responsivo e rápido, mesmo em conexões de internet lentas.
- O aplicativo deve ser escalável para acomodar um grande número de usuários e comunidades.
