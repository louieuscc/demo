Take notes for git operation.

And try some features on Sourcetree.

Try commit a file on different host, then check what happened on local Sourcetree:

1. 本地文件改动并保存（未add或commit）, Sourcetree能同步感应并提示后续操作
<<<<<<< HEAD
2. 在本地sourcetree操作，输入注释并`commit`
3. 继续本地Sourcetree操作，`push`之前改动
4. 
=======
2. `add` 
3. Got respond after `commit` on other host.
4. after `push` on other host.
>>>>>>> 615d1e833cea8a98b76baef69f40fe67b25a94a5
5. 故本地Sourcetree不能感知外地分机对共有文件的改动，也无法感知远程库对应文件的变化