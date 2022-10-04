# Reverse Shell

En este caso el [[Host]] se pone a la escucha esperando a que un [[Client]] se conecte para darle a aceso a la shell de el cliente. Este metodo es el mas usado para conectarse a la victima debido a que esta actua como cliente y no requiere un software especializado para conectarse ademas de evitar [[Firewalls]].

Ademas este metodo es mas seguro ya que el que se conecta es el que cede su shell.

## Host
El host mas usado en [[Netcat]] ej: `nc -lnvp 443`

## Client
Muchos programas pueden ser usados como clientes como:
* [[Bash]]
* [[sh]]
* [[Python]]
* [[php]]
como algunos ejemplos

## Utilidades
* [Generador de Reverse shell](https://www.revshells.com/)
* [Extension con generador y estavilizador](https://addons.mozilla.org/es/firefox/addon/hacktools/)