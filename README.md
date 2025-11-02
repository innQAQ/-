# -
My personal repository
int tribonacci(int n) {
    long long d, a = 0, b = 1, c = 1;
    if(n == 0 || n == 1) return n;
    else if(n == 2) return 1;
    else{ 
    for(int i = 3; i <= n; i++){
        d = a + b + c;
        a = b;
        b = c;
        c = d;
    }
    return d;
    }
}
