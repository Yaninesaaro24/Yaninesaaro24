/**************************

 Dado un numero entero n encontrar la sumatoria de numeros impares y numeros pares valor r .

***************************/
#include <iostream>
using namespace std;

int main()
{
    int n,c,sumai=0,sumap=0;
    
    cout<<"Ingrese el valor de x";
    cin>>n;
    
    for (c=1;c<=n ;c++)
    { if (c%2==0)
    {sumap=sumap+c;}
        else
        sumai=sumai+c;
    }
        cout<<"La suma de los numeros pares es:"<<sumap<<endl;
        cout<<"La sumande los numeros impares es"<<sumai<<endl;

    return 0;
}
