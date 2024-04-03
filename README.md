# Factorial
#include &lt;stdio.h> int main() { int n, i; unsigned long long fact = 1; printf("Enter an integer: "); scanf("%d", &amp;n); // shows error if the user enters a negative integer if (n &lt; 0) printf("Error! Factorial of a negative number doesn't exist."); else { for (i = 1; i &lt;= n; ++i) { fact *= i; } printf("Factorial of %d = %llu", n, fact); } return 0; }
