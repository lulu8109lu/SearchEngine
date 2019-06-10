## 搜索引擎四要素：
- 搜索器：相当于爬虫
- 索引器：对内容进行处理，形成索引
- 检索器：高效检索后，将数据返回给用户
- 用户接口：网页和APP的前端界面

## 提高搜索效率方法
- Bags Of Words：词袋
- Inverted Index：倒序索引
- LRU缓存：利用pylru库实现

## 多重继承
- 初始化方法
  - super(BOWInvertedIndexEngineWi..., self).__init__()：直接初始化继承的第一个父类，但要求最顶层的父类必须继承object
  - LRUCache.__init__(self)：传统方法
