# er#include <stdio.h>
#include <conio.h>
#include <iostream.h>
#define max 50

void main()
{
	struct
	{
		char ht[30];
		char sbd[10];
		float dt, dl, dh, td;
	}

	a[max];
	float dc;
	int i, j, n;
	clrscr();
	cout << "Nhap so thi sinh n<=" << max << ", n= ";
	cin >> n;
	cout << "Nhap du lieu cua cac thi sinh :\n";
	for (i = 0; i < n; i++)
	{
		cout << "Thi sinh thu " << i + 1 << " :\n";
		cout << "Ho ten : ";
		gets(a[i].ht);
		cout << "So bao danh : ";
		gets(a[i].sbd);
		cout << "Diem toan : ";
		cin >> a[i].dt;
		cout << "Diem ly : ";
		cin >> a[i].dl;
		cout << "Diem hoa : ";
		cin >> a[i].dh;i].dh, a[i].td);
	cout << "\nGo Enter Tiep tuc ...";
	getch();g");
	for (i = 0, j = 0; i < n; i++)
		if (a[i].td >= dc)
		{
			j++;
			printf("%-4d%-20s%-10s%-10.1f%-10.1f%-10.1f%-10.1f\n",
				j, a[i].ht, a[i].sbd, a[i].dt, a[i].dl, a[i].dh, a[i].td);
		}

	cout << "\nGo Enter ket thuc ...";
	getch();
}
