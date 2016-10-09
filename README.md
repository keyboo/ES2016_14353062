#Lab1配置&Lab2版本控制
##Description
1. **DOL Application Programming Interface:**The DOL defines a set of computation and communication routines that enable the programming of distributed, parallel applications for the SHAPES platform. Using these routines, application programmers can write programs without having detailed knowledge about the underlying architecture. In fact, these routines are subject to further refinement in the hardware dependent software (HdS) layer.  
2. **DOL Functional Simulation：**To provide programmers a possibility to test their applications, a functional simulation framework has been developed. Besides functional verification of applications, this framework is used to obtain performance parameters at the application level. 
3. **DOL Mapping Optimization：** The goal of the DOL mapping optimization is to compute a set of optimal mappings of an application onto the SHAPES architecture platform. In a first step, XML based specification formats have been defined that allow to describe the application and the architecture at an abstract level. Still, all the information necessary to obtain accurate performance estimates is contained. 
##How to install
1. **配置ubantu：**安装ubantu必要运行环境
2. **下载必要文件：**在虚拟机中下载systemc和dol压缩文件
3. **解压文件：**新建dol文件夹，将dol压缩包解压至新建文件夹中，之后解压systemc文件
4. **编译systemc：**进入sysmec-2.3.1目录下，创建临时文件夹，运行configure，记下文件夹所在路径
![1.png](https://ooo.0o0.ooo/2016/10/09/57fa3e5d006f0.png)
5. **编译dol：**进入dol文件夹修改biuld_zip.xml文件，编译运行即可![14353062_fumingxu-2016-09-28-10-13-14.png](https://ooo.0o0.ooo/2016/10/09/57fa3cd981040.png)
运行第一个样例结果如下：
![14353062_fumingxu-2016-09-28-10-09-38.png](https://ooo.0o0.ooo/2016/10/09/57fa3d2b8b1ba.png)

##Experimental experience
在这次的试验中，实验的难度并不是很大，工作量也并不是很多，在配置实验时进展还算顺利，在进行版本控制时，因为新接触了github和markdownpad2，刚开始的时候耗费了一些时间，但是实验文档上面写的还算详细，很快即可以上手，使用过时候，发现确实方便，只不过觉得添加图片好像有一些麻烦，不过还是觉得学会使用markdownpad2对以后的学习还是会有很大的帮助的。