
#include <iostream>
#include <cmath>
#include <term.h>
#include <curses.h>
using namespace std;
float x,y;

void ClrScr()
  {
  printf("\033[2J");
  }


int wybor;
int main()
{
    for (; ;)
    {
    cout<<"Podaj 1 liczbe:"<<endl;
    cin>>x;
    cout<<"Podaj 2 liczbe:"<<endl;
    cin>>y;
    cout<<"MENU"<<endl;
    cout<<"--------------------------"<<endl;
    cout<<"1.Dodawanie"<<endl;
    cout<<"2.Odejmowanie"<<endl;
    cout<<"3.Mnozenie"<<endl;
    cout<<"4.Dzielenie"<<endl;
    cout<<"5.Pierwiastek"<<endl;
    cout<<"6.Ktora wieksza"<<endl;
    cout<<"7.Wyjscie"<<endl;
    cout<<endl;
    cout<<"wybierz:"<<endl;
    cin>>wybor;

    switch(wybor)
    {
        case 1: cout<<"suma="<<x+y;
            cout<<endl;
    break;
        case 2: cout<<"roznica="<<x-y;
             cout<<endl;
    break;
        case 3: cout<<"iloczyn="<<x*y;
             cout<<endl;
    break;
        case 4: if(y==0) cout<<"nie dzielimy przez zero";
       else cout<<"iloraz="<<x/y;
             cout<<endl;
    break;
        case 5: cout<<"Pierwiastek z liczby pierwszej to:"<<sqrt(x)<<endl<<"Z drugiej:"<<sqrt(y);
             cout<<endl;
    break;
        case 6: cout<<"Wieksza liczba to:";
            if(x>y)
            {cout<<x;}
            else
            {cout<<y;}
             cout<<endl;
    break;
        case 7: exit(0);
    break;
            getchar();getchar();
           
    }
         system("clear");
    }
    void ClrScr();
    return 0;
    }
