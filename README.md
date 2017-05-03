# Coffee Me Up! API doc

## Notas gerais

### Todas as mensagens enviadas devem ser enviadas seguidas de "\r\n" ao final do comando.

  Exemplo: O comando ```hora:07:03\r\n``` é válido, o comando ```hora:07:30``` não.

## Comandos

### hora:hh:mm

  Define a hora do alarme da cafeteira para hh horas e mm minutos, no formato de 24 horas
  (ou seja, 01:00pm é 13:00). Além disso, sempre enviar dois digitos tanto na hora quanto
  nos minutos e NÃO utilizar espaços entre os valores

  **Exemplo:** Para configurar a cafeteira para despertar as 7:30am deve-se utilizar o
  comando ```hora:07:30\r\n```. Comandos como ```hora: 07:30\r\n```, ```hora:7:30\r\n``` ou
  ```hora:07:30am\r\n``` são todos INVÁLIDOS.
