# Unity_PolygonImage

Welcome to the Unity_PolygonImage wiki!

This is a sample from my frend. In this sample，we use a number of polygons to surround the non transparent part of the Image.Then it will not render the transparent part, and reduce the fill rate. From the code, the original sprite have contained the enclosed polygon information, but there are too many polygons if it's generated by unity directly. It is proposed that we can used software like Texture Packer to generate the corresponding information.

The sample requirements version Unity 5.3.5f1 or above

这是一个来自我朋友的例子。主要作用是用多个多边形对一个Image里面的非全透明部分进行包围，避免全透明部分造成的填充率消耗。 由代码可知，原来的Image里面就带有了包围多边形的信息，但是如果这些信息是由Unity自己计算产生的话，多边形太多太多了。所以建议可以使用Texture Packer之类的软件来产生对应信息(版本要求：5.3.5f1 以上)
