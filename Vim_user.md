普通模式:

```vim
x 删除当前光标所在位置的字符
​dd 删除当前光标所在行
​dw 删除当前光标所在位置的单词
​d& 删除当前光标所在至行尾的内容
​J 删除所在行的行尾的换行符
​u 撤销前一编辑命令
​该模式下用以上命令删除的东西后，被删的数据会被保存再单独的一个寄存器中，按p可以取出来。
​y是复制命令，yw功能类似dw，y$类似d$,被y复制的也都会保存在那个寄存器中，也是用p取出。
​按v可选择需要选中的位置，v是可视模式。
​/ 该符号可以用来查找
```

插入模式：

命令模式:

```vim
q 未修改数据退出
​q!取消修改并退出
​w b 将目前文件保存到b文件中（在之前b文件不存在才行！！）
​wq 保存并推出
​wq! 强制保存并推出
```



