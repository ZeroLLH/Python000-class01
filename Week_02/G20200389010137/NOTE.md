# 学习总结

## 作业

[week02_0137_996.py](./week02_0137_996.py)

上货：

goodsload()

tom 普通消费者，购物不满 200，不打折：

tom: normal, 15.40(折扣价) | 15.40(共消费) * 1(折扣) | 购物清单{'茄子': ('1.9', 2), '豆角': ('2.9', 4)}

jim 普通消费者，购物满 200，9 折：

jim: normal, 446.40(折扣价) | 496.00(共消费) * 0.9(折扣) | 购物清单{'茄子': ('1.9', 200), '豆角': ('2.9', 40)}

mike vip用户，购物满 200，8 折：

mike: vip, 396.80(折扣价) | 496.00(共消费) * 0.8(折扣) | 购物清单{'茄子': ('1.9', 200), '豆角': ('2.9', 40)}

kate vip 满 10 件不满 200， 85 折：

kate: vip, 160.18(折扣价) | 188.45(共消费) * 0.85(折扣) | 购物清单{'茄子': ('1.9', 1), '豆角': ('2.9', 1), '白菜': ('2.9', 1), '山药': ('18.9', 1), '菠萝': ('20.9', 1), '车厘子': ('99', 1), '土豆': ('3.99', 1), '西红柿': ('4.99', 1), '萝卜': ('9.99', 1), '芹菜': ('10.99', 1), '胡萝卜': ('11.99', 1)}

bill vip 满 10 件，满 200，8 折：

bill: vip, 1507.60(折扣价) | 1884.50(共消费) * 0.8(折扣) | 购物清单{'茄子': ('1.9', 10), '豆角': ('2.9', 10), '白菜': ('2.9', 10), '山药': ('18.9', 10), '菠萝': ('20.9', 10), '车厘子': ('99', 10), '土豆': ('3.99', 10), '西红柿': ('4.99', 10), '萝卜': ('9.99', 10), '芹菜': ('10.99', 10), '胡萝卜': ('11.99', 10)}

## 学习笔记

[闭包和装饰器](./NOTE_20200312.md)

[面向对象与设计模式](./NOTE_20200314.md)
