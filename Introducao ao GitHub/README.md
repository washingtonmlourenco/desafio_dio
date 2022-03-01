                ##### 							Dicas essências para começar a realizar seus primeiros **commits** no **Github**.



- Passo um acesse o seu **Github**, pelo link a seguir [Github](https://github.com/), clique sobre a imagem do seu **avatar** no canto superior direito. 				
  - ![avatar](https://user-images.githubusercontent.com/67602627/156264435-35a43118-c83c-4482-b2f9-8602c2d094b5.png)


- Clique em **Settings**:

    
     ![settings](https://user-images.githubusercontent.com/67602627/156264635-e023d8ea-9777-41ec-aa6d-debc93cc269f.png)


- Na aba de **Acess** clique em **SSH and GPG Keys**, posteriormente clique em generating ssh keys como mostra a segunda imagem abaixo:

  ​													![sshandgpg](https://user-images.githubusercontent.com/67602627/156264872-d756b389-257c-4adf-8d0e-82ab74981945.png)

  

  ​									![image-20220301181105465](C:\Users\WashingtonMagelaLour\AppData\Roaming\Typora\typora-user-images\image-20220301181105465.png)							

  

  - Posteriormente você será redirecionado para o link a seguir [Githib Docs](https://docs.github.com/en/authentication/connecting-to-github-with-ssh), dentro da página que será aberta procure pelo link a seguir [Generating a new SSH Key and adding it to the ssh-agent ](https://docs.github.com/en/authentication/connecting-to-github-with-ssh), dentro do link anterior encontrará o comando que vamos utilizar em nosso Git Bash para gerar nossa chave SSH.	

    - [x] Utilize um dos dois comando abaixo em seu terminal **Git Bash**, substituindo o e-mail atual pelo seu e-mail do **Github**.

      - Pressione **enter** 

      ```shell
      $ ssh-keygen -t ed25519 -C "your_email@example.com"				
      ```

      ```shell
      $ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
      ```

​			

- Posteriormente será gerada a chave via terminal, temos duas opções onde a mais performática é fazer um **cat c:/caminhoarquivo/.ssh/id_rsa**,  ou ir até o caminho do arquivo e abrir manualmente, copie todo o código abaixo e voltamos no **Github**.

  ​							![image-20220301185226254](C:\Users\WashingtonMagelaLour\AppData\Roaming\Typora\typora-user-images\image-20220301185226254.png)				



- Clique no Seu **avatar** no canto superior direito,  clique em **settings ->** **Acess**  **->** **SSH and GPG Keys**, clique em **New SSH Key**, posteriormente de um título para sua chave SSH  e cole todo o código que copiou no campo **Key**, como mostra a imagem abaixo.

​						<img src="C:\Users\WashingtonMagelaLour\AppData\Roaming\Typora\typora-user-images\image-20220301192008187.png" alt="image-20220301192008187" style="zoom: 80%;" />



- Agora está pronto para subir seus primeiros projetos, comandos básicos, porém muito utilizados.

  - **git init** - Inicializa e rastreia seu repositório.
  - **git status** - Mostra os arquivos que foram alterados.
  - **git add 'nomea_aquivo'** - Adiciona os arquivos que deseja subir para o git.
  - **git commit -m 'nome_do_primeiro_commit'** - Confirma as alterações dando um nome a seu primeiro commit.
  - **git branch -M main** - Renomeia a **branch** padrão **master** para a **branch main**.
  - **git remote add origin** - Adiciona um novo repositório remoto.
  - **git push -u origin main** - Envia seu **branch** local para uma **branch** remota chamada **main**.

  

  - [x] Prontinho!!!

    - Todos os exemplos acima, são para fins didáticos!

    - **Fontes**:

      ​	[Git Docs](https://docs.github.com/pt)

      

  ​		

  

  ​				

  

  ​	

