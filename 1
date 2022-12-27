#include <stdio.h>
#include <stdlib.h>
#include <time.h>
#include <windows.h>

int main() {
	SetConsoleCP(1251);
	SetConsoleOutputCP(1251);
	srand(time(NULL));

	struct Node {
		int data = 0;
		Node* next = NULL;
	};
	int** G1, ** G2;
	int razmer = 0;
	printf("Введите размер матрицы: ");
	scanf_s("%d", &razmer);
	G1 = (int**)malloc(razmer * sizeof(int*));
	G2 = (int**)malloc(razmer * sizeof(int*));
	for (int i = 0; i < razmer; i++) {
		G1[i] = (int*)malloc(razmer * sizeof(int));
		G2[i] = (int*)malloc(razmer * sizeof(int));
	}
	Node** lastG1 = (Node**)malloc(razmer * sizeof(Node*));
	Node** lastG2 = (Node**)malloc(razmer * sizeof(Node*));
	for (int i = 0; i < razmer; i++)
	{
		lastG1[i] = (Node*)malloc(razmer * sizeof(Node));
		lastG2[i] = (Node*)malloc(razmer * sizeof(Node));
	}
	for (int i = 0; i < razmer; i++)
	{
		lastG1[i]->data = 0;
		lastG1[i]->next = NULL;
		lastG2[i]->data = 0;
		lastG2[i]->next = NULL;
	}

	for (int i = 0; i < razmer; i++) {
		for (int j = i; j < razmer; j++) {
			if (i == j) {
				G1[i][j] = 0;
				G2[i][j] = 0;
			}
			else {
				G1[i][j] = rand() % 2;
				G2[i][j] = rand() % 2;
				G1[j][i] = G1[i][j];
				G2[j][i] = G2[i][j];
			}
		}
	}

	printf("\nПервая матрица смежности:\n\n   ");
	for (int i = 0; i < razmer; i++)
		printf("  %d", i);
	printf("\n    ___________\n");
	for (int i = 0; i < razmer; i++) {
		printf(" %d | ", i);
		for (int j = 0; j < razmer; j++) {
			printf("%d  ", G1[i][j]);
		}
		printf("\n");
	}

	printf("\nПервый список смежности:\n\n   ");
	for (int i = 0; i < razmer; i++) {
		for (int j = 0; j < razmer; j++) {
			if (G1[i][j] == 1) {
				Node* switchCell = (Node*)malloc(razmer * sizeof(Node));
				if (lastG1[i]->next != NULL) switchCell->next = lastG1[i]->next;
				else switchCell->next = NULL;
				switchCell->data = j;
				lastG1[i]->next = switchCell;
			}
		}
	}
	for (int i = 0; i < razmer; i++) {
		Node* sw = (Node*)malloc(razmer * sizeof(Node));
		sw = lastG1[i];
		printf("%d:", i);
		while (sw->next != NULL) {
			printf(" %d", sw->next->data);
			sw = sw->next;
		}
		free(sw);
		printf("\n   ");
	}
	printf("\nВторая матрица смежности:\n\n   ");
	for (int i = 0; i < razmer; i++)
		printf("  %d", i);
	printf("\n    ___________\n");
	for (int i = 0; i < razmer; i++) {
		printf(" %d | ", i);
		for (int j = 0; j < razmer; j++) {
			printf("%d  ", G2[i][j]);
		}
		printf("\n");
	}

	printf("\nВторой список смежности:\n\n   ");
	for (int i = 0; i < razmer; i++) {
		for (int j = 0; j < razmer; j++) {
			if (G2[i][j] == 1) {
				Node* switchCell = (Node*)malloc(razmer * sizeof(Node));
				if (lastG2[i]->next != NULL) switchCell->next = lastG2[i]->next;
				else switchCell->next = NULL;
				switchCell->data = j;
				lastG2[i]->next = switchCell;
			}
		}
	}
	for (int i = 0; i < razmer; i++) {
		Node* sw = (Node*)malloc(razmer * sizeof(Node));
		sw = lastG2[i];
		printf("%d:", i);
		while (sw->next != NULL) {
			printf(" %d", sw->next->data);
			sw = sw->next;
		}
		free(sw);
		printf("\n   ");
	}
}
