```
import String;

println("hi".concat("cc"));
println("hi".getIndexFromChar("h"));
println("hi".getCharFromIndex(0));
println("hi".getCharFromIndex(1));
println("hi".getCharFromIndex(2));
println("hi".equals("hi"));
println("hi".equals("Hi"));
println("hi".equalsIgnoreCase("hi"));
println("hi".equalsIgnoreCase("hI"));
println("hi".equalsIgnoreCase("HI"));
println("".isEmpty());
println("c".isEmpty());
println("cc".isEmpty());
println("CC".toLowerCase());
println("CC".toUpperCase());
println("cc".toUpperCase());
println("ccaa bb".replace("a", "b"));
println("ccaa bb".replace("b", "a"));
println("".valueOf(10));
println("".valueOf(true));
println("".valueOf(false));
println("".valueOf(10.5));
println("".valueOf("cc"));
string m = "hello";
println(m.concat("bye bye"));
println(m.isEmpty());
m = "";
println(m.isEmpty());
println(String.valueOf(50));
int a = 10;
println(String.valueOf(a));
```
Output:
```
hicc
0
h
i

true
false
true
true
true
true
false
false
cc
CC
CC
ccbb bb
ccaa aa
10
true
false
10.5
cc
hellobye bye
false
true
50
10

```
