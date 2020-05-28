# Vim

1. Mode
2. 命令模式
3. 配置文件

---

## Mode

- 命令模式;Insert模式;编辑模式
  
- a;A;i;I
  
  命令模式进入Insert模式

- Esc
  
  Insert模式回到命令模式

- ctrl+v
  
  进入竖选模式

  1. 光标竖选选中行
  2. shift+i
  3. //
  4. Esc
  
  注释代码

---

## 命令模式

- 删除和修改
  
  x;
  删除字符

  dd;
  删除一行

  [n]dd;
  删除n行

  dw;
  删除一个单词

- 行号
  
  :set nu;
  显示行号

- 粘贴
  
  p;

- 撤销
  
  u;

- 撤销撤销
  
  ctrl+r;

- 光标的快速移动

  gg;
  回到文件首部

  G;
  回到文件尾部

  w;
  光标往后移动一个单词

  b;
  光标往前移动一个单词

  :[n];
  去第n行

- 复制
  
  yy;
  复制一行

  [n]yy;
  复制n行

- 查找与替换
  
  /[str];n;shift+n
  查找

  :x,y /[str]/[dst]
  替换x行-y行

  :% /[str]/[dst]
  替换所有行

  :s /[str]/[dst]/ig
  i忽略大小写匹配;g单行全部

- 退出
  
  :q;
  退出

  :q!;
  不保存退出

  :wq;
  保存退出

- 保存
  
  :w;
  保存

- 多窗口
  
  :vnew FileName;
  打开新窗口

  ctrl+w,w;
  切换窗口

- 多标签
  
  :tabnew FileName;
  打开多标签

  gt;
  切换标签

- 代码对齐
  
  gg=G;
  全局代码对齐

---

## 配置文件

- .vimrc

