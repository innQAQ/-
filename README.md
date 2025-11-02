# -
My personal repository
int fib(int n) {
    int c, a = 0, b = 1;
    if(n == 0 || n == 1) return n;
    else{
        for(int i = 2;i <= n;i ++){
        c = a + b;
        a = b;
        b = c;
    }
    return c;
    }
}
