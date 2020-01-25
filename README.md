# Estacionamento Inteligente com RFID.

Projeto de Técnicas de Programação 2019.2 envolvendo Arduíno + Comunicação Serial e Servidor Web.

## SOBRE NOSSO PROJETO:

Projeto realizado com Arduino e QT Creator contendo comunicação serial entre eles, para a disciplina de Técnicas de Programação 2019.2, Curso de Engenharia Elétrica - IFPB. O projeto consiste na idealização de um estacionamento empresarial inteligente, capaz de monitorar o fluxo de entrada de funcionários já cadastrados na empresa,através de um leitor RFID localizado na entrada do estacionamento.

  
### PORQUE UTILIZAR ?

Diversos são os benefícios do estacionamento inteligente, dentre eles a segurança da empresa tendo em vista que apenas os funcionários já cadastrados e usuários liberados no gerenciador podem ter acesso a ele. Outro ponto é reduzir custos com funcionários, pois necessita de apenas um para gerenciar o estacionamento via computador.

### MANUAL DO ESTACIONAMENTO INTELIGENTE

Inicialmente os funcionários da empresa serão cadastrados no sistema e irão receber uma TAG, que será verificada pelo leitor RFID validando ou não a entrada do funcionário. Se após a verificação o leitor RFID constatar que aquela TAG está cadastrada no programa, a cancela irá subir permitindo a entrada do funcionário que deverá se dirigir a sua vaga, que também já está definida. Caso o usuário não leve sua TAG ele deverá se identificar na portaria do estacionamento para que através do controle realizado pela interface desenvolvida no Qt Creator, o funcionário da portaria possa liberar a cancela, permitindo assim a entrada do usuário no estacionamento.

![enter image description here](https://github.com/nicolasrls/EstacionamentoRFID/blob/master/Imagens/ideia2.png)

Para entrar no estacionamento o usuário devera posicionar sua TAG de forma que o leitor possa executar sua leitura, permitindo assim a entrada do usuário no estacionamento.
### A interface no Qt Creator:
Na interface desenvolvida através do Qt Creator é possível controlar e monitorar o comportamento do estacionamento no decorrer do dia. Após conectar o programa com o arduíno o usuário poderá liberar a cancela e alterar o estado das vagas manualmente, caso seja necessário. Uma aplicação bastante útil do programa seria liberar a cancela para um determinado usuário do estacionamento e modificar o estado da sua vaga para ocupado.

![enter image description here](https://github.com/nicolasrls/EstacionamentoRFID/blob/master/Imagens/interface%20grafica.png)

Ao observar a imagem evidencia-se a simplicidade de uso que o programa propicia ao seu usuário para que este possa tirar o maior proveito da ferramenta. A interface é bastante auto-explicativa sendo apenas necessário que o usuário estabeleça a conexão entre o programa e o arduíno, para isso ele deverá clicar no botão "conectar", sendo assim possível controlar e monitorar o estacionamento.


### COLABORADORES:
### LEANDRO GONÇALVES DE ALENCAR
### EMAIL: leandro.alencar@academico.ifpb.edu.br

### NICOLAS RIBEIRO LIMA DE SOUZA DOMICIANO
### EMAIL: nicolas.ribeiro@academico.ifpb.edu.br  

### DANUBIO EDGAR SILVA FILHO
### EMAIL: danubio.filho@academico.ifpb.edu.br
