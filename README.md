Java engineer. I build libraries small enough to read end to end in one sitting, and write about
the layer underneath the API you are calling.

### Libraries

<img src="https://github.githubassets.com/images/icons/emoji/unicode/1f9f5.png" height="16" alt="threads" /> **[java-concurrency-patterns](https://github.com/alxkm/java-concurrency-patterns)**
Concurrency examples that are measured, not asserted. Every performance claim has a benchmark
behind it, every antipattern has a test that catches it failing, and the memory model section
proves its point with jcstress instead of prose.

<img src="https://github.githubassets.com/images/icons/emoji/unicode/1f5c3.png" height="16" alt="cache" /> **[evictor](https://github.com/alxkm/evictor)**
Thirteen cache eviction policies behind one interface, with a harness that measures them against
each other on the same traffic. Open it when you want to know what LRU is costing you.

<img src="https://www.svgrepo.com/show/144446/mirror-horizontally.svg" height="16" alt="reflection" /> **[reflector](https://github.com/alxkm/reflector)**
A small layer over the Java Reflection API: read fields and methods, select annotated members,
build instances, dump an object to a map. Targets Java 8.

<img src="https://github.githubassets.com/images/icons/emoji/unicode/1f30a.png" height="16" alt="streams" /> **[streamer](https://github.com/alxkm/streamer)**
The collectors and stream helpers the JDK left out, in one utility class.

### Guides and practice

<img src="https://github.githubassets.com/images/icons/emoji/unicode/1f916.png" height="16" alt="ai" /> **[java-ai-cookbook](https://github.com/alxkm/java-ai-cookbook)**
Eighteen LLM patterns - RAG, agents, MCP, tool calling, guardrails, evals - each written twice,
once in Spring AI and once in LangChain4j, so the two frameworks can be compared on identical
ground. One folder per recipe, one command to run it, and tests that pass with no API key.

<img src="https://github.githubassets.com/images/icons/emoji/unicode/1f4da.png" height="16" alt="books" /> **[java-concurrency-interview](https://github.com/alxkm/java-concurrency-interview)**
166 Java concurrency interview questions, each answered the way you would have to answer it out
loud: the mechanism, the trade-off and the follow-up that comes next. Also a quiz that runs in the
terminal from a single file, with mock interviews, flashcards and a review of your misses.

### Writing

I publish on [Medium](https://medium.com/@alxkm), mostly about the JVM and what it does with the
code you hand it:

- [Java memory model](https://medium.com/@alxkm/java-memory-model-3b973e84dc8c)
- [JVM: the minimum every developer should know](https://medium.com/@alxkm/java-jvm-minimum-what-every-developer-should-know-226321cdffd0)
- [Classloaders, and writing your own](https://medium.com/@alxkm/java-classloaders-developing-own-classloader-d478c295b3af)
