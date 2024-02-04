# pricing_asian_call
Pricing an asian geometric call

Input:

   double S0=100.0, r=0.03, sigma=0.2;
   double T =1.0/12.0, K=100.0;
   int m=30;
   long N=30000;
   double epsilon =0.001;

Output:

Arithmetic call price = 1.42609
Error = 0.000138491
delta = 0.520246

Price by direct MC = 1.41326
Error = 0.0119483
delta = 0.525525