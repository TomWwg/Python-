# Python-
                                                            Python学习
  Python 3基础语法
  编码
  默认情况下，Python 3源码文件以UTF-8编码，所有字符串都是unicode字符串。当然你也可以为源码文件制定不同的编码：
  # -*- coding: cp-1252 -*-
  上述定义允许在源文件中使用Windows-1252字符集中的字符编码，对应适合语言为保加利亚语、白罗斯语、马其顿语、俄语、塞尔维亚语。
  
  标识符
  第一个字符必须是字母表中字母或下划线_。
  标识符的其他部分由字母、数字和下划线组成。
  标识符对大小写敏感。
  在Python 3中，非ASCII标识符也是允许的了。
  
  Python保留字
  保留字即关键字，我们不能把它们用作任何标识符名称。Python的标准库提供了一个keyword模块，可以输出当前版本的所有关键字：
  >>>import keyword
  >>>keyword.kwlist
