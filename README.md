# -4
#include <iostream>
using namespace std;

int main()
{
    int i;
    float sumx=0,sumy=0,sumxy=0,sumxx=0;
    int x[i];
    for (int i=0; i<11; i++)
    {
        cout<<"Введите значение x"<<'\n';
        cin>>x[i];
        sumx += x[i];
    }
    cout<<sumx<<'\n';
    int y[i];
    for (int i=0; i<11; i++)
    {
        cout<<"Введите значание y"<<'\n';
        cin>>y[i];
        sumy += y[i];
    }
    cout<<sumy<<'\n';
    for (int i=0; i<11; i++)
    [
        sumxy += x[i] * y[i];
        sumxx += x[i] * x[i];
    }
    cout<<sumxy<<'\n';
    cout<<sumxx<<'\n';
    float a = ((11 * sumxy) - (sumx * sumy)) / ((11 * sumxx) - (sumx * sumx));
    float b = (sumy - a * sumx) / 11;
    cout<<a<<'\n';
    cout<<b<<'\n';
    cout<<"y="<<a<<"x+"<<b<<'\n';
  }
    

        
