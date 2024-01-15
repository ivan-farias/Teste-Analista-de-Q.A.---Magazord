# Teste-Analista-de-Q.A.-Magazord

## Teste

Para validar se os campos estão funcionando conforme o esperado após as alterações, realizaria os seguintes passos:

No campo de nome completo:

- Testar com um algum nome válido (ex: Ivan Farias);
- Testar com caracteres inválidos (ex: números);
- Testar com campo vazio;
- Testar com apenas um nome (ex: Ivan).

No campo de e-mail:

- Testar com um e-mail válido (ex: ivanfarias27@magazord.com);
- Testar com e-mail inválido (ex: sem @);
- Testar com campo vazio;
- Testar o formato (ex: testar com e-mails que tenham subdomínios, caracteres especiais: !,#).

No campo de número de telefone:

- Testar com número válido (com e sem DDD, com e sem código do país);
- Testar com caracteres não numéricos (ex: letras, símbolos);
- Testar com quantidade de dígitos incorretos;
- Testar com campo vazio.

No campo de data de nascimento:

- Testar com uma data válida;
- Testar com formatos de data inválidos;
- Testar com datas futuras;
- Testar com campo vazio.

No campo de endereço:

- Rua: Testar com nome da rua válido, com caracteres inválidos, campo vazio, limite de caracteres;
- Cidade: Testar com nome da rua válido, com caracteres inválidos, campo vazio, limite de caracteres;
- Estado: Testar com campo vazio;
- CEP: Testar com um CEP válido, testar com formato inválido (letras, menos/muitos dígitos), campo vazio.

## Desafio
O erro está apontando que o campo `guias` > `itensGNRE` > `item` > `referencia` está divergindo do campo `guias` > `itensGNRE` > `item` > `dataVencimento`, porém, analisando a ferramenta do GNRE, os campos não tem relação entre si, sendo um o período de referência do item da guia, e o outro a data de vencimento.
