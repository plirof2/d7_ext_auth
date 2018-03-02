# d7_ext_auth
Drupal 7 extrernal auth tests




#Caslogut block (might implement this as external login block)

```php

<?php
//$block['cas_logout_test'] = '<button type="button">Click Me cas_logout_test!</button>';
//drupal_set_message("hello cas logout");
?>
<form action="http://hello.com/dev/caslogout">
    <!--<p class="rtecenter"><input type="submit" value="Εξοδος από ΠΣΔ" /></p>-->
    <p class="rtecenter"><button type="submit" class="btn btn-default">Εξοδος</button></p>
</form>


```