vector <int> factors;
void factorize( int n ) {
    int sqrtn = sqrt ( n );
    for ( int i = 0; i < prime.size() && prime[i] <= sqrtn; i++ ) {
        if ( n % prime[i] == 0 ) {
            while ( n % prime[i] == 0 ) {
                n /= prime[i];
                factors.push_back(prime[i]);
            }
            sqrtn = sqrt ( n );
        }
    }
    if ( n != 1 ) {
        factors.push_back(n);
    }
}
