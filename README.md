# cep_correios
Consuta o cep no site dos correios e retorna um array

Como usar:
$cep = new CorreioCep();
$log = $cep->getLogradouroCorreio("74223060");

# Retorno:

```
Array
(
    [localidade] => Goiânia
    [uf] => GO
    [bairro] => Setor Bueno 
    [tipo_logradouro] => Avenida
    [logradouro] => Avenida T 10 
)


```
