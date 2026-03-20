Guia de Instalação​

sudo apt-get update && sudo apt-get upgrade -y
===========================================================
reboot
===========================================================
cd /home
===========================================================
sudo apt install -y git && git clone https://github.com/thor4cba/chatbot.git akira && sudo chmod -R 777 akira && cd instalador && sudo ./instalar_primaria
===========================================================
Vamos adicionar o usuario deploy e dar permissão de root

adduser deploy
Digite a senha do deply

APERTAR O ENTER

APERTAR O ENTER

APERTAR O ENTER

APERTAR O ENTER

APERTAR O ENTER

Y
Vamos dar permissão agora.

adduser deploy sudo
===========================================================

💻 Bem-vindo(a) ao Gerenciador whaticket - Atendimento sem limites, selecione abaixo a próxima ação!
[0] Instalar whaticket
[1] Atualizar whaticket
[2] Deletar whaticket
[3] Bloquear whaticket
[4] Desbloquear whaticket
[5] Alter. dominio whaticket
> 0
===========================================================
💻 Informe um nome para a instância/Empresa que será instalada (Não utilizar espaços ou caracteres especiais, Utilizar Letras minusculas; ):
> whaticketinstancia
===========================================================
💻 Informe a Qtde de Conexões/Whats que a whaticketinstancia poderá cadastrar:
> 9999
===========================================================
💻 Informe a Qtde de Usuarios/Atendentes que a whaticketinstancia poderá cadastrar:
> 9999
===========================================================
💻 Digite o domínio do FRONTEND/PAINEL para a whaticketinstancia:
> seusite.com.br
===========================================================
💻 Digite o domínio do BACKEND/API para a whaticketinstancia:
> api.seusite.com.br
===========================================================
💻 Digite a porta do FRONTEND para a whaticketinstancia; Ex: 3000 A 3999
> 3300
===========================================================
💻 Digite a porta do BACKEND para esta instancia; Ex: 4000 A 4999
> 4400
===========================================================
💻 Digite a porta do REDIS/AGENDAMENTO MSG para a whaticketinstancia; Ex: 5000 A 5999
> 5500
===========================================================
💻 Fazendo download do código whaticket...
===========================================================

Caso de erro na instalação execute os dois comando abaixo sempre no diretorio raiz para cada código:
cd
cd /home/deploy/whaticketinstancia/frontend/
sudo npm run build
pm2 restart all
===========================================================

Limpe a instância para home com codigo:
cd
cd /home/deploy/whaticketinstancia/backend/
sudo npm run build
pm2 restart all
===========================================================
User: admin@admin.com
Senha: 123456
