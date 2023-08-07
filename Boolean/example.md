```
import Boolean;

println(Boolean.toInt(true));
println(Boolean.fromInt(1));
println(true.opposite());
println(false.opposite());
println(Boolean.compare(10 > 5));
println(Boolean.compare(2 > 5));
boolean a = Boolean.fromInt(0);
println("result:" a.opposite()); // println("result:" a.opposite()); == println("result:" + a.opposite());
```
Output:
```
1
true
false
true
true
false
result:true
```
