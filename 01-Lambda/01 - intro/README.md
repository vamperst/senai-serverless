# Aula 01 - Lambda


1. No terminal do IDE criado no cloud9 execute o comando `cd ~/environment/senai-serverless/01-Lambda/01\ -\ intro/` para entrar na pasta que fara este exercicio.
 2. Iniciar o repositório de trabalho `sls create --template "aws-python3"`
 ![img/slscreate.png](img/slscreate.png)
 3. Explore os arquivos criados(serverless.yml e handler.py) pelo comando anterior utilizando o menu de navegação lateral:
    ![img/explore.png](img/explore.png)
 4. No terminal do IDE faça deploy da função criada com o comando `sls deploy`
 ![img/slsdeploy.png](img/slsdeploy.png)
 5. Testar remotamente a função `sls invoke -f hello`
![img/slsinvoke.png](img/slsinvoke.png)
 6. Altere a versão do retorno da função para 1.1 no arquivo "handler.py" como na imagem e salve com as teclas "CTRL + S"
   ![img/altereversao.png](img/altereversao.png)
 7. Faça um teste local da sua função no terminal com o comando `sls invoke local -f hello` 
![img/slsinvokelocal.png](img/slsinvokelocal.png)
 8. Para deletar a função que esta no lambda utilize o comando `sls remove`
![img/slsremove.png](img/slsremove.png)
