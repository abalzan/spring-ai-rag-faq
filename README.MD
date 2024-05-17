#Spring boot ai using RAG(Retrieval Augmented Generation) model

This project is a simple spring boot application that uses the OpenAI API to generate text using the RAG model. The RAG model is a model that combines a retriever and a generator to generate text based on a given prompt. The retriever is used to find relevant documents based on the prompt, and the generator is used to generate text based on the retrieved documents.

## test the application
replace the `OPENAI_API_KEY` in the `application.properties` file with your OpenAI API key.
To test the application, you can run the following command:

```
mvn spring-boot:run
```

Then you can access the application at `http://localhost:8080/faq` and enter a prompt to generate text.
if not text is passed, the default prompt ```How can I buy tickets fot the Olympic Games Paris 2024``` is used
