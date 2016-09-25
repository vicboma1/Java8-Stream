# Java8 Stream


Interface Stream.Builder<T>
===
void 	accept(T t)
Adds an element to the stream being built.

default Stream.Builder<T> 	add(T t)
Adds an element to the stream being built.

Stream<T> 	build()
Builds the stream, transitioning this builder to the built state.