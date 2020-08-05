#include<stdio.h>
#include<stdlib.h>
#include "Ordenamientos.h"

void CargarVector(int v[],int &cant);


main(){
	int v[500],Opc,cant, nromax,nromin =0,m;
	
	printf("\n\t**********************************************************\n");
	printf("\t**\t\t\t\ MENU PRINCIPAL\t\t\t**\n");
	printf("\t**********************************************************\n");	
	printf("\t**\tElija el metodo de ordenamiento a utilizar:     **\n");
