## Debug no Adianti Framework

Para facilitar a depuração de dados no **Adianti Framework**, você pode adicionar as funções abaixo no arquivo `init.php`:

```php
function dd($ResponSer) {
    return MasterClass::Debug($ResponSer);
}

function ddd($ResponSer) {
    echo '<pre>';
    print_r($ResponSer);
}
