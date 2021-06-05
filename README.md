# c-algorithm-4
four fundamental rules of arithmetics algorithm1
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>
int main() {
	int i, n, sum[100], a, b;
	scanf("%d", &n);
	for (i = 1; i<=n; i++) {
		scanf("%d %d", &a, &b);
		sum[i] = a + b;
	}
	for (i = 1; i <= n; i++) {
		printf("Case #%d: %d\n", i, sum[i]);
	}
	return 0;
}
