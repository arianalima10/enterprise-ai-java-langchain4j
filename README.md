## Serviço de IA Corporativa com RAG

Implementação de um serviço de IA corporativa utilizando **Java, Quarkus, LangChain4j e Ollama**, incluindo:

* Criação e configuração do projeto Quarkus com integração ao Ollama.
* Implementação de um `AiService` declarativo com LangChain4j.
* Exposição do serviço por meio de endpoint REST `/travel`.
* Configuração e testes do fluxo de perguntas e respostas.
* Implementação do **Easy RAG** para fornecer conhecimento específico do negócio ao modelo.
* Inclusão de documentos de conhecimento sobre pacotes de viagem.
* Configuração do carregamento dos documentos via `application.properties`.

O RAG permite que o serviço forneça respostas específicas com base nos documentos disponibilizados, reduzindo respostas genéricas do modelo.
