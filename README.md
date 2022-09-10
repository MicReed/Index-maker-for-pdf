# Index maker for pdf

 make index of a pdf from designated wordlist从指定的单词列表制作PDF的索引

## example of final index list示例

[example](words_index.txt)

the order of  words in index is the same as those in wordlist.索引中的单词顺序与单词列表中的顺序相同。

## how to use用法

Install Dependencies安装依赖项

pdfpluber

tqdm

Open the file directory, open the console, and enter.打开相应的文件目录，打开控制台，输入

```cmd
pip install -r requirements.txt

```

substitute the pdfpath and wordpath in the main part and run the notebook替换Main中的 pdf 路径和单词路径，然后运行笔记本

```python
pdfpath=r'test.pdf'
wordspath=r'words.txt'
```

## Acknowledgement

thanks for the module: **[PDF-Indexer](https://github.com/moste00/PDF-Indexer), some of the codes is learned from the module感谢该模块：**一些代码是从这个模块中学习的****
