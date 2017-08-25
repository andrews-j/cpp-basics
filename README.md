// Function to find the bigest of a set of 4 numbers, from Hacker Rank

#include <iostream>
#include <cstdio>
using namespace std;

int max_of_four(int a, int b, int c, int d){
    return(a>b && a>c && a>d)? a : (b>c && b>d)? b : (c>d)? c : d;
}

int main() {
    int a, b, c, d;
    scanf("%d %d %d %d", &a, &b, &c, &d);
    int ans = max_of_four(a, b, c, d);
    printf("%d", ans);
    
    return 0;
}
