Java engineer. I build libraries small enough to read end to end in one sitting, and write about
the layer underneath the API you are calling.

### Libraries

🧵 **[java-concurrency-patterns](https://github.com/alxkm/java-concurrency-patterns)**
Concurrency examples that are measured, not asserted. Every performance claim has a benchmark
behind it, every antipattern has a test that catches it failing, and the memory model section
proves its point with jcstress instead of prose.

🗃️ **[evictor](https://github.com/alxkm/evictor)**
Thirteen cache eviction policies behind one interface, with a harness that measures them against
each other on the same traffic. Open it when you want to know what LRU is costing you.

🪞 **[reflector](https://github.com/alxkm/reflector)**
A small layer over the Java Reflection API: read fields and methods, select annotated members,
build instances, dump an object to a map. Targets Java 8.

🌊 **[streamer](https://github.com/alxkm/streamer)**
The collectors and stream helpers the JDK left out, in one utility class.

### Writing

I publish on [Medium](https://medium.com/@alxkm), mostly about the JVM and what it does with the
code you hand it:

- [Java memory model](https://medium.com/@alxkm/java-memory-model-3b973e84dc8c)
- [JVM: the minimum every developer should know](https://medium.com/@alxkm/java-jvm-minimum-what-every-developer-should-know-226321cdffd0)
- [Classloaders, and writing your own](https://medium.com/@alxkm/java-classloaders-developing-own-classloader-d478c295b3af)
