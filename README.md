# Desafio 1 -  Administração de Sistemas GNU/Linux: Fundamentos e Prática


> [!IMPORTANT]  
> Tópico 2: Introdução ao shell e comandos básicos 

###### 1. Entendendo informativos do bash no GNU/Linux


> [root@localhost var]#

- ```root```: usuário logado no terminal  
- ```localhost```: nome do computador
- ```var```: diretório atual 
- ```#```: Indica que o usuário atual tem permissões adminstratativas, ou seja, o root está logado no shell. 


> Observação: '$' Indica que o usuário atual é um usuário comum (sem privilégios administrativos).


---

###### 2. Função dos diretórios do GNU/Linux 📁

- ```/bin```: Diretório com os binários essensciais para o funcionamento do sistema, por exemplo, ```ls``` e ```cp```;
- ```/boot```: Arquivos responsáveis pelo processo de inicialização do sistema operacional;
- ```/etc```: Arquivos de gestão do sistema, por exemplo, gestão de grupos e usuários; 
- ```/home```: Contém os diretórios dos usuários, por exemplo,```/home/luiz``` onde vai ser a raiz do user. 
- ```/lib```: Contém bibliotcas utilizadas pelos softwares e pelo kernel em seu funcionamento, são arquivos que podem ser utilizados também por vários programas evitando código duplicado. 
- ```/proc```: Fornece informações sobre processos, hardware e configurações do sistema ↴

> *"Sistema de arquivos do kernel. Este diretório **não existe em seu disco rígido**, ele é criado pelo kernel e usado por diversos programas que fazem sua leitura. Através de seu conteúdo podemos verificar configurações do sistema ou modificar o funcionamento de dispositivos através de alterações em seus arquivos (como a função`de roteamento)."* - ```Guilerme Rodrigues Pereira```. 


###### 3. Significado do ~ no sistema operacional Linux 

O ~ representa o diretório do usuário logado no terminal atual, ou seja, se tiver com o user Luiz e navegar com ```cd ~``` vou ser direcionado para ```/home/luiz```


###### 4. Arquivos e diretórios com ```.```  no Linux 

Diretórios os arquivos com ```.``` são ocultos, ou seja, não podem ser visualizados com o parametro ```-a```


###### 5. Entendendo a navegação entre diretórios  

- ```caminho absoluto```: Nesse caso é necessário especificar do repositório raiz até o arquivo que você deseja, por exemplo, ```/home/luiz/projetos/estudando-linux```


- ```caminho relativo```: Nesse caso não é necessário especificar todo o caminho, pois o podemos utilizar o repositório atual e através dele conseguimos "cortar caminho", por exemplo para acessar a mesma pasta acima, mas considerando que estamos dentro do diretório ```projetos``` podemos acessar com ```cd estudando-linux```

> O comando para navegar entre diretórios é o cd (change directory)





