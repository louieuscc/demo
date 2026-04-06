Take notes for git operation.

And try some features on Sourcetree.

Try commit a file on different host, then check what happened on local Sourcetree:

1. 本地文件改动并保存（未add或commit）, Sourcetree能立即感应并在file status提示有文件pending，需后续操作

2. 输入注释并`commit`，Sourcetree的file status栏显示nothing to commit，即注释成功

3. 继续操作，`push`刚才改动的文件

4. Push成功，本地与远程同步

   
> 故本地Sourcetree能随时感知文件的改动。