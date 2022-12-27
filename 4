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

void dekart(int n1, int n2, int** G, int** M)
{
	printf("\nДекартово произведение графов:\n");
	int** L = (int**)malloc(n2 * sizeof(int));
	int** K = (int**)malloc(n1 * sizeof(int));
	for (int i = 0; i < n2; i++)
	{
		L[i] = (int*)malloc(n2 * sizeof(int));
		for (int j = 0; j < n2; j++)
		{
			if (i == j)
				L[i][j] = 1;
			else L[i][j] = 0;
		}
	}
	for (int i = 0; i < n1; i++)
	{
		K[i] = (int*)malloc(n1 * sizeof(int));
		for (int j = 0; j < n1; j++)
		{
			if (i == j)
				K[i][j] = 1;
			else K[i][j] = 0;
		}
	}

	int** O = (int**)malloc((n1 * n2) * sizeof(int));
	for (int i = 0; i != n1; i++) {
		for (int j = 0; j != n2; j++) {
			O[i * n2 + j] = (int*)malloc((n1 * n2) * sizeof(int));
			for (int l = 0; l != n1; l++) {
				for (int v = 0; v != n2; v++) {
					if (i == l) {
						O[i * n2 + j][l * n2 + v] = M[j][v];
					}
					else if (j == v) {
						O[i * n2 + j][l * n2 + v] = G[i][l];
					}
					else O[i * n2 + j][l * n2 + v] = 0;
				}
			}
		}
	}

	for (int i = 0; i != n1 * n2; i++) {
		for (int j = 0; j != n1 * n2; j++) {
			printf("%d\t", O[i][j]);
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
	dekart(n1, n2, G, M);
}
