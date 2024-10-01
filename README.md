#include <iostream>

using namespace std;

int main(){

    int parcial1, parcial2, parcial3;
    
    int practico;
    int examenfinal;
    float notafinal;
    float sumaparciales;
    float practico1;

    cout << "Ingrese por favor la nota de su 1er parcial: ";
    cin >> parcial1;

    cout << "Ingrese por favor la nota de su 2do parcial: ";
    cin >> parcial2;

    cout << "Ingrese por favor la nota de su 3er parcial: ";
    cin >> parcial3;

    cout << "La nota del proyecto: ";
    cin >> practico;

    cout << "Por ultimo la nota del examen final: ";
    cin >> examenfinal;

    
    sumaparciales = ((parcial1 + parcial2 + parcial3) / 3.0) * 0.40; 

    practico1 = (practico *20.0/100); // Practico por 0.20 

    notafinal = sumaparciales + practico1 + (examenfinal * 40.0 /100);

    cout << "La nota final del estudiante es: " << notafinal << endl;

    return 0;
}
