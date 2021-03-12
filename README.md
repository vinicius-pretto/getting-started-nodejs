# Iniciando com Node.js

## Referências

- https://nodejs.org/dist/latest-v14.x/docs/api/

## Atividades

1. Crie um programa de linha de comando que solicite o `nome` e a `data de nascimento` do usuário.
   Após a inserção dos dados, imprima-os no console. Ex.: `Vinicius 31 anos`

2. No mesmo programa adicione uma condição, se a idade do usuário for menor de `18` anos, o programa deve imprimir a mensagem `"Você precisa ter mais de 18 anos."` caso contrário finalize o programa.

3. Continuando no mesmo programa, adicione validação para os campos `nome` e `data de nascimento`.

**Validações:**

**Nome**<br>
validação: não pode ser `vazio` e deve conter entre `3` e `15` caracteres<br>
mensagens de erro:

- se o campo for vazio imprimir a mensagem `"O campo nome não pode ser vazio"`
- se o campo conter menos de `3` caracteres imprimir a mensagem `"O campo nome deve ter no mínimo 3 caracteres"`
- se o campo conter mais de `15` caracteres imprimir a mensagem `"O campo nome deve ter menos de 15 caracteres"`

**Data de nascimento**<br>
validação: não pode ser `vazio` e deve seguir o formato `DD/MM/AAAA`<br>
mensagens de erro:

- se o campo for vazio imprimir a mensagem `"O campo data de nascimento não pode ser vazio"`
- se o campo não seguir o formato correto imprimir a mensagem `"Data de nascimento inválida"`
