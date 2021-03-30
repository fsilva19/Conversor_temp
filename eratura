#include <iostream>

using namespace std;

int main (){
    float temp, k, f, c; // variáveis para as temperaturas
    char u; // variável para a unidade

    //inicia o programa
    //recebe o valor
    cout << endl;
    cout << "qual o valor da temperatura? " << endl;
    cin >> temp;

    //recebe a unidade
    cout << "qual a unidade da temperatura?         *digitar em caixa alta*" << endl;
    cout << "'C' para Celsius;" << endl;
    cout << "'F' para Farenheit ou;" << endl;
    cout << "'K' para Kelvin." << endl;
    cin >> u;
    cout << endl << endl;

    //faz a conferência e imprime na tela o valor 
    //das três unidades. 
    switch (u){
        case 'C':
            c = temp;
            k = c + 273.15;
            f = c * 1.8 + 32;

            cout.precision(2);
            cout << std::fixed << "Celsius: " << c << endl;
            cout << std::fixed << "Farenheit: " << f << endl;
            cout << std::fixed << "Kelvin: " << k;            
            cout << endl; //apenas para separar no final.
            break;
        case 'F':
            f = temp;
            c = (f-32)/1.8;
            k = c + 273.15;

            cout.precision(2);
            cout << std::fixed << "Celsius: " << c << endl;
            cout << std::fixed << "Farenheit: " << f << endl;
            cout << std::fixed << "Kelvin: " << k;   
            cout << endl; //apenas para separar no final.
            break;

        case 'K':
            k = temp;
            c = k-273.15;
            f = c * 1.8 + 32;

            cout.precision(2);
            cout << std::fixed << "Celsius: " << c << endl;
            cout << std::fixed << "Farenheit: " << f << endl;
            cout << std::fixed << "Kelvin: " << k;   
            cout << endl; //apenas para separar no final.
            break;
    }
    
    return 0;
}
