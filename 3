#include <stdio.h>
#include <windows.h>
#include <time.h>

void generation(int n, int** Z)
{
	printf("Матрица смежности:\n");
	for (int i = 0; i < n; i++)
	{
		Z[i] = (int*)malloc(n * sizeof(int));
	}

	for (int i = 0; i < n; i++)
	{
		for (int j = i; j < n; j++)
		{
			Z[i][j] = rand() % 2;
			if (i == j)
			{
				Z[i][j] = 0;
			}
			Z[j][i] = Z[i][j];
		}
	}

	for (int i = 0; i < n; i++)
	{
		for (int j = 0; j < n; j++)
		{
			printf("%d\t", Z[i][j]);
		}
		printf("\n");
	}
}

void operations(int n1, int n2, int** G, int** M)
{
	int m, b;
	int** L, ** P, ** J;
	if (n1 <= n2) {
		m = n1;
		b = n2;
		J = M;
	}
	else {
		m = n2;
		b = n1;
		J = G;
	}

	printf("\nПересечение:\n");
	L = (int**)malloc(m * sizeof(int));
	for (int i = 0; i < m; i++)
	{
		L[i] = (int*)malloc(m * sizeof(int));
		for (int j = 0; j < m; j++)
		{
			if (G[i][j] + M[i][j] == 2)
				L[i][j] = 1;
			else L[i][j] = 0;
		}
	}
	for (int i = 0; i < m; i++)
	{
		for (int j = 0; j < m; j++)
		{
			printf("%d\t", L[i][j]);
		}
		printf("\n");
	}

	printf("\nКольцевая сумма:\n");
	P = (int**)malloc(b * sizeof(int));
	for (int i = 0; i < b; i++)
	{
		P[i] = (int*)malloc(m * sizeof(int));
		for (int j = 0; j < b; j++)
		{
			P[i][j] = J[i][j];
		}
	}
	for (int i = 0; i < m; i++)
	{
		for (int j = 0; j < m; j++)
		{
			P[i][j] = G[i][j] ^ M[i][j];
		}
	}
	for (int i = 0; i < b; i++)
	{
		for (int j = 0; j < b; j++)
		{
			printf("%d\t", P[i][j]);
		}
		printf("\n");
	}

	printf("\nОбъединение:\n");
	for (int i = 0; i < m; i++)
	{
		for (int j = 0; j < m; j++)
		{
			if (G[i][j] + M[i][j] == 1)
				J[i][j] = 1;
		}
	}
	for (int i = 0; i < b; i++)
	{
		for (int j = 0; j < b; j++)
		{
			printf("%d\t", J[i][j]);
		}
		printf("\n");
	}
}

int main(void)
{
	SetConsoleOutputCP(1251);
	srand(time(NULL));
	int n1, n2, ** G, ** M;
	printf("Введите n1: ");
	scanf_s("%d", &n1);
	G = (int**)malloc(n1 * sizeof(int));
	generation(n1, G);
	printf("\nВведите n2: ");
	scanf_s("%d", &n2);
	M = (int**)malloc(n2 * sizeof(int));
	generation(n2, M);
	operations(n1, n2, G, M);
}
