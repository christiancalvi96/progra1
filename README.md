// modelo de examen.cpp : Defines the entry point for the console application.
//

#include "stdafx.h"
#include <iostream>
#include "conio.h"

using namespace std;

void main ()

{
	int a,b,producto,suma;
	cout<< "ingrese el primer valor: ";
	cin>> a;
	cout<< "ingrese el segundo valor: ";
	cin>> b;

	if ((a%2==0)&&(b%2==0))
	{ 
	producto=(a*b);
	cout<< "el producto es: "<<producto;
	}
	else suma=(a+b);
	{
	cout<< "la suma es: "<<suma;
	}
	
	getch();
}

