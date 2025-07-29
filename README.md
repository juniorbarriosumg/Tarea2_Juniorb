# **Tarea 2 Junior Barrios** 
## - Junior Barrios 7690-25-16187
![Universidad Mariano Galvez](https://aprende.guatemala.com/wp-content/uploads/2016/09/guatemala-universidadmarianogalvez.jpg)


# Como usar estructuras de seleccion en C++
<img width="224" height="224" alt="image" src="https://github.com/user-attachments/assets/e7178265-56f2-4a00-8d8d-06263cf80003" />

### Primero debemos tener instalada la aplicación, en mi caso C++ [Link de instalación Dev C++](https://www.bloodshed.net/)

# Estuctura de Selección Simple IF/else
#### La estructura de selección simple if en C++ permite ejecutar un bloque de código si y solo si una condición específica es verdadera. Si la condición es falsa, el bloque de código se omite y el programa continúa con la siguiente instrucción
#### podemos utilizar esta estructura para diferentes algoritmos, como por ejemplo:
- Evaluar si una persona con la edad ingresada es mayor o menor de edad
- Dependiento de lo ingresado, mostrar diferentes mensajes.

## Ejemplo de como utilizar IF
#### Algoritmo que defina si una persona es mayor o menor de edad
- Codigo del Algoritmo

 ```
  #include <iostream>
using namespace std;
int main (){
	int edad;
	cout<<"Ingresa tu edad: ";
	cin>>edad;
	if (edad < 18){
		cout<<"Usted es menor de edad";
	}else{
		cout<<"Usted es mayor de edad";
	}
	return 0;
}
 ```
  + Ejecucion del Algoritmo

  
 <img width="502" height="158" alt="image" src="https://github.com/user-attachments/assets/19cd9413-19e7-4748-9dd3-c1bb005f0328" />
<img width="488" height="163" alt="image" src="https://github.com/user-attachments/assets/b8384d61-7e97-47bf-a08c-46587e4bcc32" />

# Estructura de Selección Multiple Switch 
#### La estructura switch en C++ es una estructura de control de selección múltiple que permite ejecutar diferentes bloques de código basados en el valor de una variable o expresión. Se utiliza cuando se necesita elegir entre varias alternativas basándose en el valor de una expresión simple, llamada selector. 
#### podemos utilizar esta estructura para diferentes algoritmos, como por ejemplo:
- Realizar una calculadora que realice diferentes operaciones
- Un menu de opciones

## Ejemplo de como utilizar Switch
#### Algoritmo que muestre una calculadora con 4 operaciones basicas
- Codigo del Algoritmo
  
  
```
#include <iostream>
using namespace std;
int main (){
 double n1,n2,resultado;
 int op;
 cout<<"Ingrese el primer numero: ";
 cin>>n1;
 cout<<"Ingrese el segundo numero: ";
 cin>>n2;
 cout<<"Ingrese el numero de opcion que desee: "<<endl;
 cout<<"1. +"<<endl;
  cout<<"2. -"<<endl;
   cout<<"3. *"<<endl;
    cout<<"4. /"<<endl;
    cin>>op;
    
    switch(op){
    	case 1:
    		resultado=n1+n2;
    		cout<<"El resultado es: "<<resultado;
    		break;
    		case 2:
    		resultado=n1-n2;
    		cout<<"El resultado es: "<<resultado;
    		break;
    		case 3:
    		resultado=n1*n2;
    		cout<<"El resultado es: "<<resultado;
    		break;
    		case 4:
    		resultado=n1/n2;
    		cout<<"El resultado es: "<<resultado;
    	
	}
	return 0;
}
```
- Ejecucion del algoritmo
  
<img width="502" height="230" alt="image" src="https://github.com/user-attachments/assets/c371a0c5-fd02-41da-8292-1a5a953674c4" />
<img width="460" height="234" alt="image" src="https://github.com/user-attachments/assets/9a1e1587-c994-42aa-a1cc-2cacc8272674" />
<img width="536" height="212" alt="image" src="https://github.com/user-attachments/assets/a4945d91-9aa0-49ca-b880-16b7fb2e9b0f" />
<img width="488" height="265" alt="image" src="https://github.com/user-attachments/assets/a3d6c512-bd09-43b6-9d31-0338d911a148" />

# Gracias por su Lectura

