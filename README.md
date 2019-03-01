pinyin.py
=========

汉字转拼音,With Python


Example:

    from pinyin import PinYin
    
    test = PinYin()
    test.load_word()
    test.hanzi2pinyin(string='钓鱼岛是中国的')


Out:

    test.hanzi2pinyin(string='钓鱼岛是中国的')
    ['diao', 'yu', 'dao', 'shi', 'zhong', 'guo', 'de']    
    test.hanzi2pinyin_split(string='钓鱼岛是中国的', split="-")
    diao-yu-dao-shi-zhong-guo-de



https://www.cnblogs.com/franknihao/p/6541217.html
某位前辈的工作，稍微改了一下pinyin的源码
