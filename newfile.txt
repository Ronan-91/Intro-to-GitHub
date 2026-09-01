#include <stdio.h>

int main() {
	int array[] = {1, 2, 3, 4, 5};
	int sum = 0;
	int array_size = sizeof(array) / sizeof(array[0]);
	int i = 0;
	while (i < array_size) {
		sum += array[i];
		i++;
	}
	printf("The total sum of the array is: %d\n", sum);
	return 0;
}
