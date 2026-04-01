环境依赖
建议使用 Python 3.8 及以上版本。
常见依赖包括：
torch
torchtext
transformers
numpy
pandas
matplotlib
seaborn
jieba
wordcloud
tqdm
可以先手动安装，例如：
pip install torch torchtext transformers numpy pandas matplotlib seaborn jieba wordcloud tqdm
数据说明
仓库中包含若干示例数据和文本语料，例如：
cn_data/：中文分类示例数据
names/：姓名分类数据
eng-fra.txt：翻译数据
jay_chou.txt、shakespeare.txt：文本生成相关语料
部分脚本会自动下载公开数据集，例如 AG_NEWS 或 GLUE。
使用说明
运行文本预处理示例
python code/文本预处理/demo4.py
运行 RNN / Attention 示例
python code/RNN_code/demo_rnn.py
运行 Transformer 示例
python code/RNN_code/demo_t.py
运行 GLUE 微调
python code/run_glue.py
或者参考：
bash code/run_glue.sh
