# -
My personal repository
int climbStairs(int n) {
    int c, a = 1, b = 2;
    if(n == 1 || n == 2) return n;
    else{
        for(int i = 3; i <= n; i ++){
            c = a + b;
            a = b;
            b = c;
        }
        return c;
    } 
}
