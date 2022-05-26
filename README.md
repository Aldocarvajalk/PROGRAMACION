# **PROGRAMAS EN C++ DE CARVAJAL ALDO**

## **INFORMACION PERSONAL**

**Nombres:** *CARVAJAL ALDO*

**Correo electronico de contacto:** aldo.carvajal.klinger@utelvt.edu.ec

En el siguiente link podran ver la primera actividad que fue un video en el que hable un poco sobre: [INTRODUCCION DE LA COMPUTADORA Y LENGUAJES DE PROGRAMACION] (https://youtu.be/GtDLi1HrmG8) y tambien en este otro link podran ver como se usan los comandos basicos en termux (la version que se asemeja a linux en android) (https://youtu.be/M4nSfRYKrtg)

## **A CONTINUACION SE MOSTRARAN LOS PROGRAMAS QUE HE DESARROLLADO:**

### COMPARACIÓN DE DOS NÚMEROS

#### Descripción del problema
Con la ayuda de este programa en C++ eh ingresando dos números, podremos saber cual  de los dos números es mayor al otro o si ambos son iguales.


#### Funcionalidad 

float CA_A, CA_B;

#### Salida

if(CA_A==CA_B) son iguales.

if(CA_A<CA_B) a es el mayor.


### CALCULA LA CANTIDAD DE MONEDAS 

#### Descripción del problema
Con la ayuda de este programa en C++ podremos saber cuantas monedas de 2 denominaciones hemos ingresado (0.10 ctvs y 0.25 ctvs) asi como tambien nos mostrara la suma total de todas las monedas y la suma independiente de cada denominacion por separado.

#### Funcionalidad

int CA_n, CA_c= 0 , CA_c1= 0 , CA_c2= 0;

flotante CA_x, CA_a= 0 , CA_a1= 0 , CA_a2= 0 , CA_m= 0.10 ;

#### Salida

if(CA_x==CA_m).    El total de monedas de 0.10 y 0.25 ingresadas

while(CA_c<CA_n);  El total de dinero ingresado.

### CALCULA LA EDAD DE UNA PERSONA 
 

#### Descripción del problema
Con la ayuda de este programa en C++ podremos saber cuantos años tiene una persona ingresando su: día, mes y año de nacimiento. Este programa aparte de calcular los años que tiene una persona tambien nos muestra los días y meses que tiene.

#### Funcionalidad

int CA_aa,CA_ma,CA_da,CA_an,CA_mn,CA_dn,CA_a,CA_m,CA_d;

#### Salida

if(CA_da<CA_dn)

if(CA_ma<CA_mn)    La edad de la persona.

### PUNTO DE VENTA

#### Descripción del problema
Con la ayuda de este programa en C++ ingresando diferentes precios de productos nos ayuda a calcular el iva a pagar, el descuento y el total a pagar. Al momento de pagar el monto total mostrara el iva que debera pagar la persona, el descuento total de su compra y el precio final.

#### Funcionalidad

int CA_c=0, CA_P;

float CA_A=0,CA_x,CA_Tb,CA_Piva,CA_Pdsc,CA_iva=0.12,CA_dsc=0.30,CA_vt;

#### Salida

while(CA_c<CA_P)

CA_vt=CA_A+CA_Piva-CA_Pdsc       valor final a pagar

### SUMA DE DOS NÚMEROS

#### Descripción del problema
Con la ayuda de este programa en C++ se suman varios números el cual el usuario debera ingresar y este le mostrara la suma total. 

#### Funcionalidad

int CA_c=0, CA_n;

float CA_s=0, CA_x;

#### Salida

while(CA_c<CA_n)       el resultado de la suma total

## INSTALACIÓN 

### DESCARGAR EL REPOSITORIO

1.- clonar el repositorio en la máquina local.

git clone https://github.com/Aldocarvajalk/PROGRAMACION.git

"cd" más el nombre de la carpeta que vizualisan en mi repositorio de github.


### COMPILAR Y EJECUTAR

g++ CarvajalAldo-SumaN.cpp -o CarvajalAldo-SumaN

./CarvajalAldo-SumaN

**(Estos pasos son en base al uso de la aplicacion termux o el uso del sistema operativo linux)**
