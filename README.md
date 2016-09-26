# Java 8 - Stream


##[Interface Stream.Builder<T>](https://github.com/vicboma1/Java8-Stream/blob/master/src/test/java/BuilderTest.java)

* void 	                      accept(T t)
* default Stream.Builder<T> 	add(T t)
* Stream<T> 	                build()



##[Interface BaseStream [ T, Stream T ] - Generators](https://github.com/vicboma1/Java8-Stream/blob/master/src/test/java/BaseStreamTest.java)
```
DoubleStream, IntStream, LongStream, Stream<T>
```

* static T Stream T concat(Stream<? extends T> a, Stream<? extends T> b)
* static T Stream T of(T... values)
* static T Stream T of(T t)
* static T Stream T empty()
* static T Stream T generate(Supplier<T> s)
* static T Stream T iterate(T seed, UnaryOperator<T> f)
* static IntStream 	   range(int startInclusive, int endExclusive)
* static IntStream 	   rangeClosed(int startInclusive, int endInclusive)
