# comandos-autentica-o-SSH
para guardar comandos de autenticação da máquina cliente com gitHub

Siga os passos para autenticar sua máquina no gitHub:
1 - settings -> SSH and GPG Keys -> New SSH key -> você precisará preencher os seguintes campos -Name e Key. O campo Name pode ser um nome que te lembre do que se trata aquilo.
2 - abra seu prompt no Windows e digite o seguinte comando -> ssh-keygen -t rsa -b 4096 -C "ellianee@hotmail.com" -> clique Enter -> nom campo e-mail substitua ao seu email do GitHub. Você precisará cadastrar uma senha. e confirmar a senha. Ao final esse comando terá gerado suachave criptografada e salva no seguinte arquivo.

Enter file in which to save the key (C:\Users\ellia/.ssh/id_rsa):
Created directory 'C:\\Users\\ellia/.ssh'

você poderá abrir diretamente pelo terminal ou o arquivo salvo na pasta indicada acima.

3 - volte ao guitHub, após abrir o arquivo criado acima e copia os itens do documento e cole no campo key do GitHub -> clique em Add SSH key.

4- volte ao prompt e digite ssh -T git@github.com
você deverá ter uma mensagem como a que esta abaixo:

The authenticity of host 'github.com (20.201.28.151)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes

Parabéns você configurou sua máquina para acessar o GitHub e equipe. BOra trabalhar ;)
