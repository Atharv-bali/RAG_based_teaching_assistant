# RAG_based_teaching_assistant
In this there are 3 videos of a web development course that I collected, convert speech to text using whisper, and made vectors using  bge-3 model inside cosine_similarity library, then using ollama llama 3.2 version generated the response

## Why Useful ?

If there is a playlist of over 150 videos and he want to go to a specific video then this LLM will give huim the video number by giving the top 5 chunks, so efforts will be greatly reduced

## Architecture 

Step 1: Video to text (Using whisper)

Step 2: Chunking 

Step 3: Text to vectors (Cosine Similarity, using bge-3 model)

Step 4: Query to vectors (Cosine Similarity, using bge-3 model)

Step 5: Rag Setup

Step 6: Get response from llm
