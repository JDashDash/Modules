```
import Double;

double a = Double.min(10.0, 5.0);
double b = Double.max(10.0, 5.0);
println(a);
println(b);
double c = Double.max(a, b);
println(a ", " b ", " c);
c = Double.sum(c, 15.0);
println(c);
c = Double.sub(c, 10.0);
println(c);
c = Double.mul(c, 10.0);
println(c);
c = Double.div(c, 5.0);
println(c);
```
Output:
```
5.000000
10.000000
5.000000, 10.000000, 10.000000
25.000000
15.000000
150.000000
30.000000
```
