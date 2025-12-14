 ##  📌 Descripción

 - El programa muestra en pantalla los valores decrecientes de la variable n desde 15 hasta 1, uno por línea, utilizando una estructura de control do-while para ejecutar un bloque de código repetidamente mientras se cumpla una condición.
 - Este es un ejemplo básico de iteración controlada por contador, útil para ilustrar el uso de bucles que se ejecutan al menos una vez.

## 🚀 Estructura del Código
#### 1. #include <stdio.h>
  - Esta directiva del preprocesador incluye el archivo de cabecera estándar stdio.h (Standard Input/Output Header), que contiene las declaraciones de funciones para operaciones de entrada y salida como printf() y scanf(). Sin esta inclusión, el compilador no reconocería la función printf y generaría un error.

#### 2. int n = 15;
 - Se declara una variable global llamada n de tipo entero (int) y se le asigna el valor inicial 15. Al ser global, puede ser accedida desde cualquier función del programa, incluyendo main().

#### 3. int main()
 - Función principal del programa. Es el punto de entrada donde comienza la ejecución. Devuelve un valor entero (int) al sistema operativo al finalizar.
 - return 0; indica que el programa terminó correctamente.
 - Si se devuelve un valor distinto de cero, generalmente indica un error.
 - El valor return 0; indica que el programa terminó correctamente.

#### 4. Bucle Do-While
 - Este programa imprime los valores de n desde 15 hasta 1, decreciendo en cada iteración.
 - Primero imprime el valor actual de n.
 - Luego decrementa n en una unidad (n--).
 - Después verifica si n > 0.
 - Si la condición es verdadera, vuelve a repetir el ciclo.
 - El bucle do-while ejecuta un bloque de código al menos una vez, y luego repite la ejecución mientras la condición especificada sea verdadera.
 - A diferencia del while, el do-while evalúa la condición al final.
 - Si la condición es verdadera, vuelve a repetir el ciclo.
 - El bucle termina cuando n llega a 0.
 - El bloque  printf("Valor de n: %d\n", n); es un marcador donde va el código a ejecutar.

## 🖥️ Tecnologías Utilizadas:

- Lenguaje programación C
- Visual Studio Code

## 📦 Requisitos:

- Compilador gcc o cc.

## ⚙️ Compilación

- Compilación en sistemas GNU/Linux es el siguiente comando: **gcc do-while.c -o do-while**.
- En entornos Windows con Microsoft Visual C++, se utiliza el compilador cl.exe. Para compilar un programa, se debe abrir una ventana de símbolo del sistema para desarrolladores y ejecutar un comando como: **cl do-while.c**. Esto genera un archivo ejecutable llamado **do-while.exe**.

</br>

💙 <strong>Alejandra Contreras</strong></br></br>
<a href="https://www.linkedin.com/in/alejandraconb-dev/" target="_blank">
<img align="left" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
<img align="center" src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Relieved%20Face.png" target="_blank" height="40"></a>
