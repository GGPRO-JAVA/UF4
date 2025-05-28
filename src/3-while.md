# 3. Bucle while

El bucle while es codifica de la següent forma: 

|Codi| Diagrama de flux|
|----|-----------------|
|**while (condició) { <br> bloc d'accions; <br> }**| ![Bucle while](/uf4/bucle_while.jpg)|

El bloc d'instruccions s'executa mentre es compleix una condició (mentre condició s'avalue a true). **La condició es comprova ABANS de començar** a executar per primera vegada el bucle, per la qual cosa si s'avalua a false en la primera iteració, llavors el bloc d'accions no s'executarà cap vegada. El mateix exemple 2 d’abans, fet amb un bucle while seria:

El mateix exemple 2 d’abans, fet amb un bucle while seria:

>**Exemple 3**:
>
>:::: tabs
>=== Java
>
>::: tabs
>== Codi
>
>```java
>public static void main(String[] args){
>   Scanner sc = new Scanner(System.in);
>   int max, cont;
>   System.out.print("Introdueix el número màxim: ");
>   max = sc.nextInt();
>   cont = 1;
>   while (cont <= max){
>       System.out.println("Número: " + cont);
>       cont++;
>   }
>}
>```
>
>== Eixida
>
>```plaintext
>Introdueix el número màxim: 5
>Número 1
>Número 2
>Número 3
>Número 4
>Número 5
>```
>
>:::
>::::