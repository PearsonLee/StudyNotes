# xml处理和使用



**20170506**

Q1：暂时还不清楚xml中DTD使用的好处，暂时先搁着

Q2：处理xml时，使用验证的好处？如何使用？

​	使用验证，就不需要在系统运行中对DOM树作分析



处理网格组布局的技巧

网格组是有行和列组成，

通常我们可以把它描述成一个行的序列，每一行都包含若干单元格





## XPath



主要应用场景：

如果需要获取xml文档中指定节点元素内容，采用遍历整个DOM树的节点来查找不是个好主意，

XPath可以获取指定节点元素，使访问树节点变得容易

XPath工厂函数创建对象：

XPathFactory xpathfactory = XPathFactory.newInstance();

XPath path = xpathfactory.newXPath();