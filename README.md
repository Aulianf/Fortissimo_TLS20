# Fortissimo_TLS20
Alika Amalia Putri, Aulia Nur Fajriyah, Maria Anastasia, Nisrina Ristyawati, Ruth Perdana Saragih, Theresia Avilla Krisnanda Sulistyo 

[KOTAK MELALUI TEROWONGAN]

#include <stdio.h>

int main () 
{	
	int n,b,c,i;
	int p[n], l[n], t[n], v[n];
	
	printf ("masukkan jumlah kotak:");
	scanf("%d", &n);
	
	b=0;
	for (i=0; i<n ; i++)
	{
		printf ("masukkan panjang, lebar, tinggi:", i);
		scanf("%d %d %d", &p[i], &l[i], &t[i]);
		if (t[i] < 41)
		{
		v[b] = p[i]*l[i]*t[i];
		b = b+1;
		}
	}
	for (c=0; c<b ; c++)
	{
		printf("\n%d", v[c]);
	}
	return 0;
}

[ADU LONCATAN JANGKRIK]

#include<stdio.h>

int main(){
	int x1, v1, x2, v2, n;
	
	printf("Posisi awal jangkrik 1 : ");
	scanf("%d", &x1);
	printf("Jarak lompatan jangkrik 1 : ");
	scanf("%d", &v1);
	printf("Posisi awal jangkrik 2 : ");
	scanf("%d", &x2);
	printf("jarak lompatan jangkrik 2 :");
	scanf("%d", &v2);
	
	n=1+(x1-x2)/(v2-v1);
	
	if(n>0 && (int)n-n == 0){
		printf("YES\n");
		printf("Jangkrik berada pada posisi yang sama");
	}
	else{
		printf("NO\n");
		printf("Jangkrik berada pada posisi berbeda");
	}
	
	return 0;
}
