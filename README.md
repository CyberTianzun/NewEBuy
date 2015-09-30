# Git教学：如何找回Git删除的提交

仅仅是个演示如何找回Git删除的提交，我并没有源码

不要找我发邮件要源码了，我并没有源码。不过这个readme会更新的

## **中文：** 如何找回Git删除的提交

1. Clone一下这个仓库，下面教你找回代码. 

  ```
  git clone https://cnzx219@bitbucket.org/liruqi/newebuy.git
  ```

2. 找一找哪一个是代码删除之前的提交

  ```
  git log
  ```

3. 把git的HEAD头指向之前代码还在的hash

  ```
  git reset 45ac382f --hard
  ```

4. 哈哈，现在你找回来了

## **English:** Learn Git: Restore the commit which has already removed

It's only a demo. I don't have the source code.

1. Clone this repository. [origin url](https://gitlab.com/xd09/NewEBuy)

  ```
  git@gitlab.com:xd09/NewEBuy.git
  ```

2. Seek the commit before remove

  ```
  git log
  ```

3. Set Head to the commit before remove

  ```
  git reset 45ac382f --hard
  ```

4. Now you get the origin code
