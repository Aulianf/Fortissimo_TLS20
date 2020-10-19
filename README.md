# Fortissimo_TLS20
Alika Amalia Putri, Aulia Nur Fajriyah, Maria Anastasia, Nisrina Ristyawati, Ruth Perdana Saragih, Theresia Avilla Krisnanda Sulistyo 

Kotak Melalui Terowongan

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
