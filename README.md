# pinyinify

forked from peterolson/pinyinify

modified to return the whole internals including node-jieba method of chunking.

This lib uses NPM pinyin package
but adds a word dictionary to better guess the most frequent characters


转换汉字为拼音。 Convert Chinese characters to pinyin. 

    > pinyinify("转换汉字为拼音。")
    "zhuǎnhuàn hànzì wéi pīnyīn."

## 安装 Installation 

    npm install pinyinify
    
## 用法 Usage

    var pinyinify = require("pinyinify");
    console.log(pinyinify("你好！你今天吃饭了没？"));
    // nǐhǎo! nǐ jīntiān chīfàn le méi?
