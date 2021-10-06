## 1、对代码工作原理的理解

文件编码方面，代码将.java文件的字节码整合一些关键信息，如文件名称长度、文件名、文件大小等，构成一个字节码数组。再将该字节码数组依次取两个比特，作为int型的0\~7，8\~15，16\~23位，而其24\~31位全1，构建一个int型数组编码进图片中。

文件解码方面，与编码步骤相反，将图片内的int型数组，按与编码相反的方式，逐个提取两个比特构成原先的字节码数组，根据关键信息获取需要的类文件。



## 2、快排和选择排序法的隐写术图

**快排**

![快速排序](http://m.qpic.cn/psc?/V52oXK4R3Wfdoc23ThPf0o9ZD71iqRbp/45NBuzDIW489QBoVep5mcZ7knjuwgZns25s.GtYrdBilAAiNgIYWGrB5l*Ruebpxc4vfX6LG28cKQ7.K*dfWlkxuovctBE19G6NJg5EcL.U!/b&bo=hAP.AQAAAAADN2o!&rf=viewer_4)

**选择排序**

![选择排序](http://m.qpic.cn/psc?/V52oXK4R3Wfdoc23ThPf0o9ZD71iqRbp/45NBuzDIW489QBoVep5mcfbJ0cGI1sqUdOuGGndbFcsBJbr7hu1HzxsJJCyW8MA*xKM4ve20qgRnKkbb9.gAGWmGpLCS8fdD8sXklO60UI8!/b&bo=hAP.AQAAAAADN2o!&rf=viewer_4)



## 3、排序结果

**选择排序结果**

[![](https://asciinema.org/a/ZiHIuIsH5ot8Gt5zegYHJ5fBp.svg)](https://asciinema.org/a/ZiHIuIsH5ot8Gt5zegYHJ5fBp)

**快速排序结果**

[![](https://asciinema.org/a/ZiHIuIsH5ot8Gt5zegYHJ5fBp.svg)](https://asciinema.org/a/ZiHIuIsH5ot8Gt5zegYHJ5fBp)



## 4、验证同学的隐写术图
**使用蒋梓栩同学的图片进行排序，结果正确**

**选择排序隐写术图**

![](http://m.qpic.cn/psc?/V52oXK4R3Wfdoc23ThPf0o9ZD71iqRbp/45NBuzDIW489QBoVep5mcaPwuhz2MafmxSXOhobd5H0MgxiurjQhuEZ.rdDcalciZh3PerASoXyt8eltuB6ZLCh6wtoUmcwOt3erKfr6FT0!/b&bo=yQVUAwAAAAADZ9k!&rf=viewer_4)

