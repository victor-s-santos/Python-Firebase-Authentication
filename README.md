# PythonFireBase
`Neste projeto eu estudo o uso direto e simples do sistema de gerenciamento de usuários do FireBase.`

# Acessando o FireBase
* Primeiramente vá em https://console.firebase.google.com (com a sua conta de gmail previamente logada) -> Adicionar projeto e siga as três etapas simples de criação de um projeto;
![alt text](https://github.com/Beevi-Cognitive/PythonFireBaseAuthentication/blob/master/images/firebase1.png?raw=true)


* Dentro do seu projeto, acesse o item Authentication:
Imagem2
- Na aba Users é retornada as informações de cadastro dos usuários;

Imagem3
- Na aba Sign-in method é informado os tipos de cadastramento aceitos pelo Firebase(por email, pelo gmail, pelo facebook, pelo github,..., e até pelo smartphone, acredito que desta forma conseguimos implementar o sistema de segurança de dois passos);

Imagem4
- Na aba Templates é definido informações sobre o email que será enviado ao usuário cadastrado em algum dos três eventos:
    - Verificação do endereço de email (no momento do cadastro);
    - Redefinição de senha;
    - Alteração do endereço de email.

Imagem 5
- Na aba Usage é retornada informações referentes ao uso do serviço em relação ao período de faturamento.