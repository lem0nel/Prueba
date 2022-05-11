# Utilizando ramificaciones

Este repositorio está dedicado al testeo del trabajo en ramificaciones para la integración de código generado por varias personas.

Las líneas que se escriben en una rama no se superponen con las de la rama principal, son aperturas distintas.

Cuando el cuerpo de un archivo se ve modificado y existe más de una bifurcación a partir de un mismo punto hay que traer los cambios a cada una de las ramas para realizar un `merge` entre todos esos cambios para evitar que se pisen entre sí.

## Nuevo desafío: comprensión del manejo de ramas

A veces puede parecer complicado entender cómo es que realmente funcionan estas cosas, pero en la práctica son bastante más sencillas de lo que aparentan ser. Probaré aplicar cambios en el main y llevarlos a una rama.

Ahora bien, una práctica que se puede adoptar fácilmente es mantener los dos cambios cuando se realiza un `merge` y el mismo contiene un error. Puede haber ocurrido que en realidad hay dos versiones del código que insertan cosas distintas. Al aceptar los dos cambios es posible mantener ambos bloques de código o texto y estilizarlos para su posterior inserción en la rama `main`.

## Realizando *merges* contra la corriente
