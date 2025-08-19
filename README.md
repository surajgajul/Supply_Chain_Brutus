# Supply_Chain_Brutus
LLM trained to answer questions related to supply chain in academic and professional contexts.

Check out the tool here - [supplychainbrutus.com](https://supplychainbrutus.com/)


The jsonl file is a high-quality Q&A dataset constructed using a Reverse-RAG pipeline. We leveraged multiple LLM models (gpt 4.1, kimi-k2, claude sonnet 4, grok-4) and embedding models (large/small-3, titan) for this effort.

The db file is a demo milvus file with a single ebook pushed as a trial run (the actual file is quite large).

The jupyter notebooks contain the code for generating questions and their respective answers using our pipeline.

**Pipeline for the dataset explained - Initially, question sets were generated using multiple models and intricate prompting. These questions were divided into four splits and then RAG was implemented to get precise answers. Since similar topics maybe covered in multiple books, providing relevant texts from diverse sources would create more in-depth responses.**
