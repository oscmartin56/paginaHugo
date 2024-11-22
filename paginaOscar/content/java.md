+++
title = 'Java'
date = 2024-10-04T14:01:01+02:00
draft = false
+++

# 1. Introducción a Java

Java es un lenguaje de programación orientado a objetos, diseñado para ser portátil, seguro y escalable. Su sintaxis es similar a C++, y permite crear aplicaciones para diversos dispositivos, como móviles y servidores.

## 2. Primer Programa en Java

Un programa básico en Java consiste en crear una clase con un método main, que es el punto de entrada del programa.
Ejemplo:

```java
public class HolaMundo {
public static void main(String[] args) {
System.out.println("¡Hola, Mundo!");
}
}
```

## 3. Tipos de Datos y Variables

Java tiene tipos de datos primitivos como int, double, char, boolean y String para cadenas de texto.
Ejemplo de declaración de variables:

```java
int numero = 10;
double precio = 19.99;
String saludo = "Hola";
```

## 4. Estructuras de Control

Condicionales: if, switch para tomar decisiones.
Bucles: for y while para repetir acciones.
Ejemplo de bucle for:

```java
for (int i = 0; i < 5; i++) {
System.out.println(i);
}
```

## 5. Programación Orientada a Objetos (OOP)

Java es un lenguaje orientado a objetos. Una clase es un molde para crear objetos, y cada objeto tiene atributos y métodos.
Ejemplo de clase:

```java
public class Persona {
private String nombre;
public void saludar() {
System.out.println("Hola, soy " + nombre);
}
}
```

## 6. Excepciones

Java maneja errores con excepciones utilizando bloques try y catch.
Ejemplo:

```java
try {
int resultado = 10 / 0;
} catch (ArithmeticException e) {
System.out.println("Error de división");
}
```

## 7. Colecciones

Java ofrece estructuras de datos como listas y mapas en el paquete java.util.
Ejemplo de lista:

```java
ArrayList<String> frutas = new ArrayList<>();
frutas.add("Manzana");
```
