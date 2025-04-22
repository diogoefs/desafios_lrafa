
---

# **Missão: Configurando e Administrando um Servidor Ubuntu**  

Você está encarregado de configurar e gerenciar um **servidor Ubuntu Server** para uma equipe de desenvolvimento. Sua missão é instalar serviços essenciais, administrar usuários, gerenciar processos e garantir um ambiente funcional. Complete cada etapa da missão e envie os prints comprovando suas ações! 🚀  

---

## **1. Instalando e configurando serviços essenciais**  

🔹 Instale os seguintes pacotes no sistema usando o **APT**: **SSH, SFTP, Nginx, Cron, vim, Postfix e MariaDB**.  
📸 **Envie um print mostrando que os pacotes foram instalados corretamente.**  

🔹 Agora, instale o programa **htop** de forma manual, utilizando o **DPKG**. O HTOP permite monitorar processos do sistema e não possui dependências complexas. Para isso, acesse um site confiável como **pkgs.org**, baixe o pacote `.deb` e instale-o.  
📸 **Envie um print mostrando o download do arquivo.**  

🔹 Instale o pacote **htop** manualmente com **dpkg** e confirme se a instalação foi bem-sucedida.  
📸 **Envie um print mostrando que o programa foi instalado corretamente.**  

🔹 Verifique se os pacotes instalados aparecem na listagem do sistema.  
📸 **Envie um print mostrando a listagem dos pacotes instalados.**  

---

## **2. Monitoramento e encerramento de processos**  

🔹 Verifique se os serviços **Nginx, MariaDB e Postfix** estão rodando no sistema e identifique seus processos (PIDs).  
📸 **Envie um print mostrando a listagem de processos e os serviços ativos.**  

🔹 O serviço do **Nginx** apresentou instabilidade e precisa ser encerrado. Finalize o processo corretamente.  
📸 **Envie um print mostrando que o processo foi encerrado.**  

🔹 **Você iniciou um editor de texto no terminal chamado Vim, mas esqueceu de fechá-lo. O processo está rodando e consumindo recursos desnecessários. Encontre o processo do Vim e finalize-o corretamente.**  
📸 **Envie um print mostrando que o processo foi encerrado.**  

---

## **3. Gerenciando múltiplos processos**  

🔹 O serviço do **MariaDB** gerou vários processos no sistema. Encerre todos de uma vez.  
📸 **Envie um print mostrando que os processos foram encerrados.**  

🔹 A equipe deseja monitorar quais processos estão consumindo mais CPU e memória. Exiba um relatório com essas informações.  
📸 **Envie um print mostrando a listagem dos processos mais pesados.**  

---

## **4. Trabalhando com processos em segundo plano**  

🔹 Crie um arquivo de texto vazio chamado `meuarquivo.txt` e abra-o no editor **Vim** em segundo plano.  
📸 **Envie um print mostrando que o processo foi iniciado em segundo plano.**  

🔹 Liste os processos rodando em segundo plano e confirme se o **Vim** está ativo.  
📸 **Envie um print mostrando os processos ativos.**  

🔹 Traga o **Vim** para o primeiro plano e feche-o corretamente.  
📸 **Envie um print mostrando que o processo foi movido para o primeiro plano e encerrado.**  

---

## **5. Criando scripts e permissões de execução**  

🔹 Crie um script que exibe uma mensagem personalizada qualquer (Olá, boom dia, boa tarde, boa noite!!!) ao ser executado pelo usuário.  
📸 **Envie um print mostrando o conteúdo do script.**  

🔹 Ajuste as permissões para permitir que qualquer usuário do sistema possa executar esse script.  
📸 **Envie um print mostrando as permissões atribuídas.**  

🔹 Adicione-o ao **PATH**, garantindo que ele possa ser executado apenas digitando o seu nome, sem precisar informar o caminho (path) completo.  
📸 **Envie um print mostrando a execução do script sem o caminho completo.**  

---

## **6. Buscando arquivos importantes no sistema**  

🔹 Atualize o banco de dados de arquivos do sistema para garantir buscas mais rápidas.  
📸 **Envie um print mostrando a atualização do banco de dados.**  

🔹 Encontre o arquivo de configuração do **Nginx** e exiba seu caminho completo.  
📸 **Envie um print mostrando a localização do arquivo.**  

🔹 Liste todos os arquivos com a extensão `.log` que estão armazenados no sistema.  
📸 **Envie um print mostrando os arquivos encontrados.**  

---

## **7. Criando e controlando usuários**  

🔹 Crie um usuário chamado `developer` e defina uma senha segura para ele.  
📸 **Envie um print mostrando a criação do usuário.**  

🔹 Troque para o usuário `developer` sem encerrar a sessão atual.  
📸 **Envie um print mostrando a troca de usuário.**  

🔹 Execute um comando administrativo sem precisar trocar de usuário, utilizando permissões elevadas.  
📸 **Envie um print mostrando a execução do comando.**  

🔹 Liste todos os processos que pertencem ao usuário `developer`.  
📸 **Envie um print mostrando os processos ativos desse usuário.**  

---

## **8. Manipulando permissões de arquivos**  

🔹 No diretório do usuário `developer`, crie um arquivo chamado `config.cfg` e ajuste as permissões para que apenas o dono possa modificá-lo.  
📸 **Envie um print mostrando as permissões aplicadas.**  

🔹 Crie um grupo chamado `dev_team` e adicione o usuário `developer` a esse grupo.  
📸 **Envie um print mostrando o usuário adicionado ao grupo.**  

🔹 Crie um diretório dentro de "/var/tmp/diretorio_teste", bem como 02 arquivos dentro dele (teste01.txt e texte02.txt) e defina permissões para garantir que apenas membros do grupo `dev_team` tenham acesso a este diretório, bem como todo o seu conteúdo.  
📸 **Envie um print mostrando as permissões configuradas para o grupo.**  

---

## **9. Configurando acesso remoto e transferências de arquivos**  

🔹 Ative o serviço **SSH** para permitir conexões remotas ao servidor.  (lembrando que para este serviço (SSH) existem o client e o server)
📸 **Envie um print mostrando a configuração do SSH.**  

🔹 Faça login na sua própria máquina usando **SSH (localhost)** e confirme o acesso remoto.  
📸 **Envie um print mostrando a conexão remota realizada com sucesso.**  

🔹 Utilize **SCP** para copiar um arquivo qualquer para localhost (dentro de localhost, escolha um diretório qualquer para armezenar o arquivo copiado via scp) e verifique se ele foi transferido corretamente.  
📸 **Envie um print mostrando que a transferência foi concluída.**  

---

## **10. Configurando serviços para iniciar automaticamente**  

🔹 Configure os serviços **Nginx, Postfix e MariaDB** para iniciarem automaticamente quando o sistema for ligado.  
📸 **Envie um print mostrando que os serviços foram configurados para iniciar com o sistema.**  

🔹 Reinicie o servidor e verifique se os serviços foram iniciados corretamente após a reinicialização.  
📸 **Envie um print mostrando que os serviços continuam rodando após o reboot.**  

---

### **Missão concluída!**  
🎉 Parabéns! Você configurou o servidor, monitorou processos, gerenciou usuários e acessou remotamente seu ambiente Linux!  😃🚀

---