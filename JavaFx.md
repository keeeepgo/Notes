JavaFx

用fxml做布局

Button类扩展了Labeled类，可以显示文本，图像或两者都可以。



**什么是javabean**
1、Javabeans就是符合某种特定规范Java类。使用Javabeans的好处是【解决代码的重复编写】，减少代码冗余，功能区分明确，提高代码的维护性。
2、设计原则四点：公有类，属性私有，包含无参的共有构造方法，getter和setter方法封装属性



ObservableList
我们处理JavaFX的view classes需要在人员列表发生任何改变时都被通知. 这是很重要的,不然视图就会和数据不同步.为了达到这个目的,JavaFX引入了一些新的集合类. 



当将一切都在fxml文件中设置好之后, 应用程序会在fxml文件被载入时自动地填充这些变量. 让我们添加以下的代码:`@FXML`



