Issues就是给这个没完成的仓库提问题。
仓库创始人开源了一个没写完的仓库，其他用户或者团队成员查看仓库里面的文件，发现了错误或是bug就点击Issues，新建一个Issues，编辑issues阐述错误内容，然后为这个issues添加一个标签，标明错误类型，之后提交这个issues。仓库的创始人可以查看到其他用户提交的issues，可以选择删除或者是解决这个issues，当仓库创始人解决了这个issues系统会自动对提交用户发送thank XXX，并删除这个issues。

一．	参与者 	

仓库创始人
队员和其他用户
系统管理员


二．	用例
 					 					 
（Check issues）（Close issues）（Solve issues）

（create issues）（Edit issues）（Submit issues）

（基本信息管理）			 					 



三．	用例和参与者之间的联系

参与者--------------------------用例

仓库创始人----------（Check issues）（Close issues）（Solve issues）

队员和其他用户------（create issues）（Edit issues）（Submit issues）

系统管理员----------（基本信息管理）


四．	用例之间的关系

包含关系

Submit issues------Edit issues

Edit issues--------create issues

Check issues-------Submit issues

Solve issues-------Reply

扩展关系

Add labels---------Edit issues

Solve issues-------Close issues


详情见Word文档
