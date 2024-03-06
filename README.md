# ROCKSET Workshop 

Use "microsoft_annual_report_2022.pdf" for external document info for RAG pattern
After vectorization, this pdf will be a set of overlapping chunks, with numeric vectors.
RocksetDV is a vectorDB (high performance real-time cash), and on input "concept" RocksetDB will provide "context" 
for each input prompt string. Context string is augmenting input prompt, and togehter [input_prompt, answer_context] will 
provide enough info for ChatGPT 4.0 (LLM) to generate relevant and precise output result.

# SELF-RAG Pattern

"Self-RAG" is a pattern described in the paper (2210-11511 arcxiv paper - see below). 
Various input prompts and corresponding answered contexts from RocksetDB, are combined in a meaningful way (self-reflection),
to construct chain of thought prompts and contexts which are then fed to LLM for more precise and accurate result retrieval.

https://github.com/rockset 


# LANGCHAIN orchestration of RAG and Self-RAG:
				   https://github.com/langchain-ai/langgraph/blob/main/examples/rag/langgraph_crag.ipynb
				   https://github.com/langchain-ai/langgraph/blob/main/examples/rag/langgraph_self_rag.ipynb
				   https://github.com/ntrajic/langgraph/blob/main/examples/rag/langgraph_self_rag.ipynb (fork)

# Rockset_Workshop_Feb29_Ankit_Build_RAG_Chatbot.ipynb (rockset)
https://colab.research.google.com/github/cohere-ai/notebooks/blob/main/notebooks/RAG_Chatbot_with_Chat_Embed_Rerank.ipynb   (cohere)

resources: ankitkhare@rockset.com  dev-evangelist-lead   
https://rockset.com/index-conf    May 16, 2024          (forth comming conference)
https://github.com/ankit1khare?tab=repositories   _ 
workshop: self-rag: https://drive.google.com/drive/folders/19Iw8XoO_tpGVDAcQw-cfR5I4mOLhfgfe?usp=sharing
                   https://www.youtube.com/channel/UCy4qLzJ7yuEmsIN2Mm5Pn-w?sub_confirmation=1   subscribe to rockset workshops



2024-03-05  06:21 PM         1,405,127 2310.11511-Learning-to-Retrieve-Generate-n-Critique-Through-Self-Reflection.pdf
2024-03-05  06:06 PM        18,591,382 chunks_with_embeddings.json
2024-03-05  06:15 PM             1,093 LICENSE
2024-03-05  06:05 PM         1,285,495 microsoft_annual_report_2022.pdf
2024-03-05  06:26 PM             1,628 README.md
2024-03-05  06:05 PM           264,915 Rockset_RAG_Chatbot_Workshop_Notebook.ipynb
2024-03-05  06:05 PM         1,224,521 Rockset_Workshop_Feb29_Ankit_Build_RAG_Chatbot.pdf
2024-03-05  06:04 PM         8,186,973 Rockset_Workshop_Feb29_Ankit_Build_RAG_Chatbot.pptx