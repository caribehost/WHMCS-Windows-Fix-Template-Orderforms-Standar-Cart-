# WHMCS-Windows-Fix-Template-Orderforms-Standar-Cart-
Correción del Archivo scripts.js para WHMCS en Windows


El error en el Standar Cart de WHMCS en windows se debe a que en el SCRIPTS.JS la variable (data) no se lee en formato JSON sino como un String, por lo que toca volverla a codificar con la función <strong>JSON.parse(data)</strong>

Esta correción es compatible con las Versiones de WHMCS V7.X.X

<strong>INSTALACIÓN</strong>

Reemplace el archivo <strong>scrpts.js</strong> en la siguiente ruta: \whmcs\templates\orderforms\standard_cart\js\
Reemplace el archivo <strong>common.tpl</strong> en la siguiente ruta: \whmcs\templates\orderforms\standard_cart\


para soporte: soporte@caribehost.co

