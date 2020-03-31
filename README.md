# Semana Omnistack11 - Rockseat
![logo](https://user-images.githubusercontent.com/49286223/77972266-40d54b00-72c7-11ea-9ccc-3c41a7c68e7c.png)

### **Be the Hero**
Conteúdo do projeto desenvolvido com o material cedido e aplicado pela equipe **Rocketseat** na **Semana OmniStack 11**.

Linguagens e tecnologias aplicadas no projeto:
- HTML
- CSS
- JavaScript
- Node.js
- ReactJS
- React Native
- Insominia

#### Objetivo
A aplicação desenvolvida, chamada de **Be The Hero**, tem o objetivo relacionar pessoas que querem ajudar há ONGs que necessitam de doações.

#### Passo a Passo
>Escolhemos a linguagem JavaScript com base central por ela ser utilizada em toda Stack.

Primeiro criamos nosso back-end utilizando do Node.js e conjuntamente o banco de dados com uso do sqlite e migrations.
Posteriormente fomos para o desenvolvimento do Front-end com o uso do ReactJS, e nele foi no qual estilizamos toda pagina Web. 
Ao final da semana usamos o React Native junto a aplicação EXPO para finalizarmos com o Mobile.

Na ultima aula vimos sobre TDD e adicionamos a verificação de dados nas rotas.

#### MVP - Web
Abaixo estão as screenshots da aplicação em funcionamento.

##### Logon
![HOME](https://user-images.githubusercontent.com/49286223/77973032-7844f700-72c9-11ea-89a6-b6815185a27c.png)

- Identifica pelo ID da ONG cadastrada se pode realizar o login ou não.
##### Cadastro de ONGs
![CADASTRO_ONGS](https://user-images.githubusercontent.com/49286223/77973054-872ba980-72c9-11ea-8aba-a6b9ae92a4e4.png)

- Aplica uma validação dos dados inseridos e cadastra a ONG, retornando seu ID de acesso.
##### Visualização de Casos
![PESQUISA_CASOS](https://user-images.githubusercontent.com/49286223/77973048-8430b900-72c9-11ea-9709-357faf55ddee.png)

- Cada caso pode ser excluido manualmente pela ONG nesta tela.
- Apenas a ONG vinculada aquele caso pode exclui-lo.
##### Cadastro de Casos
![CADASTRO_CASOS](https://user-images.githubusercontent.com/49286223/77973049-85fa7c80-72c9-11ea-81c4-665b81c05aa7.png)

- Aplica uma validação dos dados inseridos e cadastra o caso referente a ONG logada.
#### MVP - Mobile
##### Inicialização / Splash
![splash](https://user-images.githubusercontent.com/49286223/77973134-bfcb8300-72c9-11ea-9a34-e603d3e1c20e.png)
##### Pesquisa de Casos
![Screenshot_20200330-205028](https://user-images.githubusercontent.com/49286223/77973173-e12c6f00-72c9-11ea-9445-c4fcb6981dc9.jpg)

- Aparecem todos os casos cadastrados no app.
- Aplicado uma barra de rolagem infinita para a pesquisa de casos.
##### Detalhamento de Caso
![Screenshot_20200330-205021](https://user-images.githubusercontent.com/49286223/77973176-e1c50580-72c9-11ea-8977-4d1cc2c23371.jpg)

- Onde ficam as formas para contatar a ONG necessitada.
