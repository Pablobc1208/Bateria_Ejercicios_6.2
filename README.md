# Bateria_Ejercicios_6.2
#Ejercicio 01
´´´ mermaid
classDiagram

class Usuario{
    Usuario : -String nombre
    Usuario : -String contrasena
    Usuario : +String correo
    Usuario: +cambiarContrasena(String) void
    Usuario : -validarEmail() void
}

´´´
