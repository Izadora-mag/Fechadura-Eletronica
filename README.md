# Fechadura-Eletronica

![image](https://user-images.githubusercontent.com/75693606/101530249-6cd5bf80-3970-11eb-98dd-31417b92c097.png)
## Funcionamento e Funcionalidade
A _Fechadura-Eletronica_ possui funções que podem ser acessadas através do **Teclado Matricial**. São elas:

1. Definir uma senha;
2. Destravar;
3. Travar;
4. Consultar histórico.

Na tela inicial, mostrada na imagem acima, o  usuário poderá definir uma senha, que irá aparecer nos displays de sete segmentos, e poderá ser usada posteriormente para destravar
ou travar a fechadura.  Após definida a senha, a fechadura é travada e cabe ao usuário digitar a senha para destravá - la. Toda vez ela é travada ou destravada, a ventoinha é ligada, 
simulando um motor.  No modo destravado, o usuário terá acesso a duas opções: **consultar histórico** e **travar**, na  opção consultar histórico é possivel visualizar a quantidade
de vezes que a fechadura foi travada ou destravada. 

##  Como simular

Para desenvolver o projeto foi usada a plataforma [MPLAB X IDE](https://www.microchip.com/mplab/mplab-x-ide) e o compilador XC8, juntamente com o simulador[PICSimLab](https://github.com/lcgamboa/picsimlab),
que simula a placa PICgenius, com o processador PIC18F4520.
Para simular, basta baixar os arquivos compactados, abrir o simulador, e clicar em  _Files_ -> _Load Hex_. O arquivo desejado está em ‘Projeto_Fechadura.X\dist\default\production’.

## Créditos
O presente projeto foi desenvolvido na Universidade Federal de Itajubá, como avaliação para as disciplinas de Programação Embarcada e Laboratório de Programação Embarcada, ministradas
pelos professores  [Rodrigo Almeida](https://github.com/rmaalmeida) e [Otavio Gomes](https://github.com/osmgomes).
