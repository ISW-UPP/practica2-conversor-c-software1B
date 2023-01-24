#include <iostream>
using namespace std;

int main()

{
    int numeros[10];
    int i = 0;
    float sum = 0;
    int mayor = 0;
    int posicion = 0;
    int Opcion;
    for (i = 1; i < 11; i++)
    {
        cout << "Digite un numero: ";
        cin >> numeros[i];
    }
    cout << "¿Que accion deseas realizar?: [1] Invertir los numeros agregados  [2] Sacar la media aritmetica  [3] Cual es el mayor: " ;
    cin >> Opcion;
    switch (Opcion)
    {
      case 1:
          for (i = 10; i > 0; i--)
          {
              cout << numeros[i] << endl;
          }
      case 2:
          for (i = 1; i < 11; i++)
          {
              sum += numeros[i];
          }
          cout << "La media es: " << sum / 10;
      case 3:
          for (i = 1; i < 11; i++)
          {

              if (numeros[i] > mayor) {
                  mayor = numeros[i];
                  posicion = i;
              }
          }
          cout << " posicion: " << posicion << " numero:  " << mayor;
          break;




    }




}
