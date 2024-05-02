# CODEBLOCKS-
Problem Slove
#include <stdio.h>

int main() {
    int t;
    scanf("%d", &t);

    while (t--) {
        int a, b;
        scanf("%d %d", &a, &b);

        while (1) {

            if (a == 0) {
                printf("Bob\n");
                break;
            }
            if (a >= b) {
                printf("Alice\n");
                break;
            }
            a--;


            if (b == 0) {
                printf("Alice\n");
                break;
            }
            if (b >= a) {
                printf("Bob\n");
                break;
            }
            b--;
        }
    }

    return 0;
}

