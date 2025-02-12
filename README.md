# MES-RAG

**MES-RAG: Bringing Multi-modal, Entity-Storage, and Secure Enhancements to RAG**


## Pipeline
![pipeline](/assets/pipeline.png)

## Installation

### Git clone

```bash
git clone https://github.com/wpydcr/MES-RAG.git
cd MES-RAG
```

### Conda environment

```bash
conda create -n mes-rag python=3.10 -y
conda activate mes-rag
pip install -r requirements.txt
```

## Dataset

you can download dataset with this [link](https://drive.google.com/drive/folders/1KcqhTAt5dBc17iHGvBsak9-oYJCYXVac), and place it in `data/`.

Note: If it's the first time running and gpt-3.5-turbo is available, it will automatically generate the corresponding embedding file for the data. If you don't want to regenerate it, you can also download the embedding file through this [link](https://drive.google.com/drive/folders/1KcqhTAt5dBc17iHGvBsak9-oYJCYXVac) and place it in `data/`.

## Use in Gradio

### Config

You need to configure gpt-3.5-turbo properly in `config/base.json`.

### Start

run `python webui.py` to start.