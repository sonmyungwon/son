# son
#define _CRT_SECURE_NO_WARINGS #include &lt;stdio.h> #include &lt;stdlib.h>  int solution(int a, int b) {        int answer = 0;     scanf("%d %d", &amp;a, &amp;b);     int i, c;     int d = a;     if (a - b &lt; 0) {             for (i = 1; i &lt;= b - a; i++) {                 c = a + i;                 d = d + c;             }answer = d;         }     if (a - b > 0) {         for (i = 1; i &lt;= a - b; i++) {             c = a - i;             d = d + c;         }answer = d;     }     if (a - b == 0) { answer=a ; }     printf("%d", answer);     return answer;     }
