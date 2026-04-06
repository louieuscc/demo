Take notes for git operation.

And try some features on Sourcetree.

Try commit a file on different host, then check what happened on local Sourcetree:

<<<<<<< HEAD
1. 本地文件改动并保存（未add或commit）, Sourcetree能立即感应并在file status提示有文件pending，需后续操作

2. 输入注释并`commit`，Sourcetree的file status栏显示nothing to commit，即注释成功

3. 继续操作，`push`刚才改动的文件

4. Push成功，本地与远程同步

   
> 故本地Sourcetree能随时感知文件的改动。
=======
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
>>>>>>> d334fe3cd2ed27780ea4e8f389ab0dab2f966087
