AUTOR DE LA RESOLUCIÓN
  -Usuario GitHub: josefielmachado
  -Legajo: 1593626
  -Apellido: Fiel Machado
  -Nombre: José Luis
  
NUMERO Y TÍTULO DEL TRABAJO
 01-Adición
HIPOTESIS
   Al tratarse de una adición debe tratarse de realizar la suma de dos números
   previamente pedidos
ENUNCIADO
   1)Obtener del usuario dos números y mostrarle la suma.
  
   2)Escribir, compilar, ejecutar, y probar Adición.cpp.
  
   3)Escribir el archivo readme.md que actúa como front page de la resolución que
   contenga lo solicitado en la sección “Carpetas para cada Resolución”, y en
   particular, el Análisis del Problema y el Diseño de la Solución
ETAPA #1: ANALISIS DEL PROBLEMA
   -Obtener del usuario dos números y mostrarle la suma.
   
   -Pedimos un número luego un segundo número y realizamos la adición (suma)
    de los números previamente declarados de que tipo son.
    Hipótesis:Al tratarse de una adición debe tratarse de realizar la suma de dos números
    previamente pedidos
   
   -Modelo IPO:
      -Entrada: En este caso ingresan 2 datos tipo double a y b 
                perteneciiente a los reales.
                #include <iostream>
                int main ()
                double a,b;
                std::cin>>a;
                std::cin>>b;
      -Proceso: Se realiza la lectura y procesamiento de los 2 datos ingresados
                para dar un resultado segun lo que se le pida.(todo esto se realiza
                con el compilador que elijamos el cual usa recursos como tiempo
                y espacio).
      -Salida: En este caso nos dara por salida el resultado de sumar los dos datos
               ingresados, resultado tambien pertenece a los reales.
               #include <iostream>
               int main ()
               std::cout<<a+b;
     
ETAPA #2: DISEÑO DE LA SOLUCIÓN
       -Léxico del algoritmo: a,b pertenecientes a los reales

       -Representación del algoritmo

         TEXTUAL (paso por paso)

           1)Ingresamos número y lo guardamos (a)
           2)Ingresamos otro número y lo guardamos (b)
           3)Hacemos la suma y la mostramos por pantalla (a+b)
         
         VISUAL (mostrada en la imagen adjunta)
