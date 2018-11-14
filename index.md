## 概念、数据结构

![data](assets/commit-tree-blob.png)

* commit
  * 包含commit message，author, committer
  * author (写代码的人) v.s. committer (把代码添加到项目的人): git am &lt;xxx.patch
  * git cat-file commit &lt;xxx&gt;
* tree
  * 文件夹，包含文件和嵌套文件夹的引用
  * git ls-tree &lt;xxx&gt;
* blob (binary large object)
  * 文件，snapshots of our files
  * git cat-file blob &lt;xxx&gt;

## 常用操作
* git help &lt;子命令&gt;
## 推荐书目
* progit