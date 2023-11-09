# BioNLP-课程论文-数据和代码

## 文件说明

### 1. 数据文件

- `data/`：数据文件夹
  - `data/json/`：数据处理过程中的JSON格式的中间文件
  - `data/txt/`：数据处理过程中的TXT格式的中间文件
  - `data/table/`：数据处理前后表格格式的中间文件

- `raw_data.zip`：原始下载的论文摘要文本压缩包
- `raw_data_clean.zip`：清洗后的论文摘要文本压缩包

### 2. 模型文件

- `lsa_model`：潜在语义分析模型文件

### 3. 代码文件

- `download_abstract.ipynb`：下载论文摘要文本的相关代码
- `extract_abstract.ipynb`: 提取论文摘要文本的相关代码
- `LSA.ipynb` ：潜在语义分析的相关代码
- `abstrate_to_embedding.ipynb`: 将论文摘要文本转换为文本嵌入的相关代码
- `text_ming_via_embedding.ipynb`: 基于文本嵌入搜索和GPT模型的文本挖掘的相关代码


## 代码运行环境
* 系统：Windows 10
* Python版本：3.9.16
* Python包：
    ```text
    nltk                              3.8.1
    langid                            1.1.6
    gensim                            4.3.2
    scipy                             1.10.1
    tiktoken                          0.3.3
    openai                            0.27.8
    ```

## 代码运行说明

* 您需要自行安装上述环境和包，并安装Jupyter Notebook。
* 文本嵌入的生成和GPT模型的使用需要OpenAI的API Key，您需要自行申请并设置环境变量`OPENAI_API_KEY`为你的API key。
* 部分数据文件和中间文件的路径已改变，您需要自行修改代码中的路径。