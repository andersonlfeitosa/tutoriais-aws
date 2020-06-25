# AWS ECR
---

## OBJETIVO

Um guia visual prático, passo-a-passo, para criar um reposiório de imagens [Docker](https://docs.docker.com/) usando [ECR](https://aws.amazon.com/ecr/).

Esse guia não precisa de nenhum pré-requisito. 

## CRIANDO O REPOSITÓRIO

1. Acesse o https://console.aws.amazon.com/ para fazer o login na [AWS](https://aws.amazon.com/).

![Image](images/1.png)

2. Escolha a opção IAM user e preencha com suas informações de acesso (Account ID são 12 dígitos, o IAM user name é o e-mail e Password a senha).

![Image](images/2.png)

3. Após o login você será redirecionado para AWS Management Console.

![Image](images/3.png)

4. Para acessar o serviço [ECR](https://aws.amazon.com/ecr/), clique em Services e digite ECR na barra de pesquisa.

![Image](images/4.png)

5. Na tela que surge, escolha a opção Repositories sob Amazon ECR no menu lateral esquerdo.

![Image](images/5.png)

6. Na tela seguinte, escolha a opção Create Repository

![Image](images/6.png)

7. Nessa tela vamos configurar o nome do repository. Também é possível configurar esse repositório com a opção Tag immutability que restringe a substituição de imagens docker com a mesma tag (tipicamente a versão). Além disso, o serviço [ECR](https://aws.amazon.com/ecr/) oferece a opção Image scan settings para verificação de vulnerabilidades na imagem docker armazenada no repository. Clique em Create Repository para avançar.

![Image](images/7.png)

8. Pronto! O Amazon Elastic Container Registry foi criado com sucesso. 

![Image](images/8.png)

9. Clique no link do repository para mais informações.

![Image](images/9.png)

10. Para visualizar os comandos de push/pull para esse repositório, clique em View Push Commands.

![Image](images/10.png)


### TO DO

* Como apagar um repositório
