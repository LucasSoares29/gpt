## 🤖 Sobre o repositório `gpt`

Este repositório contém diversos notebooks explorando o uso prático de modelos de linguagem da OpenAI, com e sem o framework LangChain. Os notebooks abordam aplicações variadas, desde geração de imagens até transcrição e resumo de áudios longos.

---

### 📝 `Resumidor lives.ipynb` — **Destaque do Projeto**

Um dos destaques deste repositório. O notebook automatiza o processo de transcrição e resumo de **lives gravadas**:

- O áudio é dividido em 10 partes para evitar alucinações em transcrições muito longas.
- Cada trecho é transcrito com o modelo **Whisper**, da OpenAI.
- A transcrição completa é enviada ao **GPT-4o**, que gera um resumo coerente e objetivo da live.

Este projeto demonstra o uso avançado da **biblioteca oficial da OpenAI**, combinando modelos distintos em um pipeline funcional.

---

### 🖼️ `Dall-E.ipynb`

Notebook com implementação direta da API da OpenAI para geração de imagens com o modelo **DALL·E**. Ideal para aplicações criativas que envolvem transformação de texto em imagem.

---

### 📚 `Teste - Base de Conhecimento Customizada Langchain-GPT.ipynb`

Primeiro experimento com **RAG (Retrieval-Augmented Generation)** utilizando **LangChain**. 

- O notebook constrói um chatbot básico (sem memória), onde o usuário pode fazer perguntas com base no conteúdo de um arquivo PDF importado.
- Demonstra integração entre LangChain, embeddings e recuperação de contexto para resposta com base em dados customizados.

---

### 💬 `Teste - ChatGPT v4.ipynb`

Notebook simples e direto que demonstra como utilizar a **biblioteca da OpenAI** para interagir com o modelo **GPT-4** via API. Excelente ponto de partida para quem deseja fazer integrações básicas com modelos de linguagem.

---

### 🧠 `Teste - Langchain.ipynb`

Experimento com **LangChain** para criação de um **chatbot com memória**, capaz de manter o contexto entre as interações do usuário. Útil para entender como construir experiências conversacionais mais naturais e contínuas.

---

### 🔊 `Whisper.ipynb`

Exemplo prático de uso do modelo **Whisper** da OpenAI para **transcrição de áudio**. O notebook mostra como transformar arquivos de áudio em texto com alta precisão, ideal para aplicações de legendagem, resumos ou análise de conteúdo falado.

---

### 🧰 Tecnologias e habilidades aplicadas

- APIs da OpenAI (GPT-4, GPT-4o, DALL·E, Whisper)  
- Framework **LangChain**  
- Conceitos de **RAG** (Retrieval-Augmented Generation)  
- Manipulação de PDFs e áudios  
- Engenharia de prompts  
- Processamento de linguagem natural (NLP)  
- Construção de chatbots com e sem memória  
- Organização de pipelines de IA para aplicações práticas

---

Este repositório destaca o uso prático de modelos de IA para resolver problemas do mundo real, combinando criatividade, automação e engenharia de dados.
