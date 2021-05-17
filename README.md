# Formação AWS

## Free Tier

Free Tier, normalmente é tempo que você tem para uso gratuito para utilização da AWS. 
Para alguns serviços temos até 12 meses sem cobranças, mas depende do serviço e como será o uso desse
serviço.
Exemplo: t2.micro tem um limite de 750hrs por mês.

## Ec2
Explicando de modo simples, consiste em uma máquina virtual hospedada no AWS.
E temos dois tipos sistemas operacionais padrões disponiveis :  Linux e Windows.
Para acessar a máquina Linux, normalmente ssh e para windows, terminal service.
A cobrança pelo serviço normalmente é cobrado pelo recurso computacional utilizado por segundos
ou por hora, sem compromisso. Ou seja, pode se subir / ligar uma máquina utilizar por pelo periodo
que deseja e depois desligar. Detalhe importante é que a cobrança minima é de 60 segundos.

As instancias disponiveis podem ser encontradas no link a seguir
https://aws.amazon.com/pt/ec2/instance-types/

Normalmente o nome de uma instância é composta por uma sigla como por exemplo : a1.large, onde
abaixo descrevemos mais sobre.


| Familia        | Geração          | Tamanho da Instância  |
| ------------- |:-------------:| -----:|
|  a    | 1 | large |

Em cada tamanho distância temos a variação vCpu (processamento da máquina) e na memoria.
Ebs only é o mesmo que não existe nenhum disco atachado a ela, precisamos alocar um disco pra ela,
quando matarmos a instância, o disco/conteúdo será armazenado sem perda de dados.
Já disco efemero, significa que quando desligarmos a máquina o disco também será descartado, é um
disco temporário, apenas para funcionamento da máquina.

Link para comparação de instâncias ec2 : https://instances.vantage.sh/

## RDS

Serviço da AWS para hospedagem de banco.