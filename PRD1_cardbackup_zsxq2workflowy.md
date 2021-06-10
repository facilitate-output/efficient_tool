# 需求|卡片备份&维护：把知识星球内容导出到 WorkFlowy 

## 背景

目前个人输出工具流中，在积累、完善和留档复用卡片上，主要靠定期手动进行，从知识星球把内容整理到 WorkFlowy ，期待把这部分自动化。

## 具体需求

### 说明：

当前发布在知识星球的卡片内容样式如下，demo 见 https://t.zsxq.com/Nf2Nz7e

- 第一行：标签 等标准信息
- 第二行：内容要点/标题
- 第三行及往后：其余内容



### 期待：导到 WorkFlowy 后的效果

1. 内容分为标题+完整卡片全文：
    demo：
      - https://workflowy.com/s/ab286de2d4db/GVIvcRrlyTN35CKi
      - 完整版卡片列表：https://workflowy.com/s/5b059005d3f2/mrymoCiNq6vZlxmL


2. 具体细节：
    - 标题/要点：
      - 把知识星球卡片中的这个字段提出出来，放到 WorkFlowy 的一个 node 里
      - 并在前面加上 MarkDown 二级标题语法 `##` ，以便未来导到 MarkDown 文档里使用
    - 完整卡片全文：
      - 内容列到上述标题所在 node 对应的 note 里
      - 内容上，包含知识星球一张卡片的所有内容
      - 格式上，需要在第一行的最后加上标签 `#s1` ，以便在 WorkFlowy 里批量展开


## CHANGELOG 

- 210610 闪闪创建