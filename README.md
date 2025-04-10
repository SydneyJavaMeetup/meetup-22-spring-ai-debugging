# meetup-22-spring-ai-debugging

We had two awesome talks:

# Kim Horn on Spring AI:

Microsoft and Google have stated that today Java is the best language for developing AI based Applications. Recently, Spring has developed an application framework that tackles the AI integration problem, providing portable service abstractions to the majority of LLM vendors, such as OpenAI, Microsoft, Amazon, Google, Hugging Face and Ollama. The Framework includes ETL, data processing, PDF extraction, advanced prompting, integrating with most vector stores such as Chroma, Neo4j, PineCone,PGVector etc. It supports a range of model types such as Chat, Embeddings, Image, Audio, Text to Speech, Moderation, and patterns like RAG and agents. The framework is at 1.0.0.SNAPSHOT.  The talk will introduce the framework with two live examples. One is a PDF load and chat, the other is a Router Agent for customer support.

- My public presentations are all here: https://github.com/hornkim/public-presentations
- The Java Meetup presentation PDF is this one: AI-SPRING-SHORT-2025.pdf
- The examples for the talk are here: https://github.com/hornkim/examples
- The Spring-AI reference page https://docs.spring.io/spring-ai/reference/

# Burin Choomnuan on Clojure and Remote Debugging
## Interactive Debugging with Clojure

### Links to resources used during the talks

The following links are the foundation of the original talk:

- https://blog.andreyfadeev.com/p/how-to-save-redeployment-time-using - the article
- https://github.com/real-pravles/clojure-guest-post - The repository from the article
- https://engineering.telia.no/blog/clojure-vs-java-troubleshooting-prod-app - related article to remote debugging 
- https://engineering.telia.no/blog/java-troubleshooting-on-steroids-with-clojure-repl 
- https://github.com/dododcdc/wbrepl-spring-boot-starter - the actual project that uses the idea from the article
- https://github.com/spring-guides/tut-rest - example project used for testing

### Clojure Resources

- https://kimh.github.io/clojure-by-example/#about-this-page - Nice overview of Clojure
- https://clojure-doc.org/articles/language/interop/ - Good overview of how to work with Clojure/Java
- https://clojure.org/reference/java_interop
- https://babashka.org/ - GraalVM + Clojure
- https://book.babashka.org/ - Books
