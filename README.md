<h1 align="center"> Large Language Models Notebooks</h1>
<p align="center">
  🤗<a href="https://huggingface.co/prsdm">Hugging Face</a> • 💻<a href="https://medium.com/@prasadmahamulkar">Blogs</a>
</p>
<p align="center"> This repository contains all the large language models that I have worked on </p>

 ![llm tree-min](https://github.com/prasadmahamulkar/Large-Language-Models-llm-/assets/93597510/9da2115a-3eed-4f5f-ac72-125800a0eb6e)
 

<h2>Fine-tune Projects 📝</h2>
<p> Fine-tuning or instruction tuning is the process where the pre-trained model is further trained on the smaller dataset to adapt its knowledge for a specific task or domain. This process tweaks the model’s parameters to perform specific tasks.</p>


  | LLMs                      |Description| Dataset | Notebooks | 
|----------------------------|------------------------|-----------------------|-----------------------|
|  [Phi-2](https://huggingface.co/prsdm/phi-2-medquad)  |    This model has been fine-tuned on a Medical dataset to answer questions related to diseases and symptoms. (used SFT method)             | [Dataset](https://huggingface.co/datasets/prsdm/MedQuad-phi2-1k)                 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1zki5smRQDDIYGZ9LuTzVLV_qcq4dH8Aj)               |       
|  [modellink](https://huggingface.co/prsdm/phi-2-medquad)  |    This model has been fine-tuned on a dataset with human-generated prompts to answer questions related to general knowledge.  (used SFT method)    | [Dataset](https://huggingface.co/datasets/prsdm/MedQuad-phi2-1k)                 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1zki5smRQDDIYGZ9LuTzVLV_qcq4dH8Aj)               |   
<h2>RAG Projects 📝</h2>
<p> Retrieval-augmented generation (RAG) aims to improve prediction quality by using an external datastore at inference time to build a richer prompt that includes some combination of context, history, and recent/relevant knowledge. </p>


  | LLMs                      |Description| Dataset | Notebooks | Demo |
|----------------------------|------------------------|-----------------------|-----------------------|-----------|
|  llama-2   |       Developed a machine learning expert chatbot (using Q&A dataset) that exclusively answers questions related to machine learning only.       | [addlink](https://huggingface.co/datasets/prsdm/MedQuad-phi2-1k)                 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/prasadmahamulkar/Large-Language-Models/blob/main/RAG_llama_2_model.ipynb)           |   W.I.P |
