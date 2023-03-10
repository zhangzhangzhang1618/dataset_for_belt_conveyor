# dataset_for_belt_conveyor
This is the dataset suitable for the monitoring of belt conveyor running status.

It comes entirely from surveillance video of the port of Qingdao, China.

The dataset includes three folders：

    image, which is responsible for providing original images，including 4291 images.
    
    det, providing the annocation information for bulk conveying foreign objects, as well as marking information for the edge of the conveyor belt, in Yolo format.
         its label including “left edge”, “right edge”, “large target”
         
        and the label method for belt edge could refer  https://www.sciencedirect.com/science/article/pii/S0959652622021758
        
         (and you can use some other tools to convert its format, such as voc-xml )
         
         (5699 labels for large conveyed foreign objects, 8563 labels for conveyor belt edges)
         
     seg，providing the annocation information for the load on the conveyor belt, it is serving the segmentation task！
           including 4291 segmentation labels
          (also you can change its format fron json to other format)

You can use it to perform integrated detection or any other single detection, such as only doing detection task or only segmentation task!

 Also you can re-lable it as it has many other target shown in the image, such as roller ans so on.


========================================2023.3.10
We have uploaded a video for the convenience of researchers, and you can carry out corresponding research work based on this dynamic video according to your own ideas. If you need more help, please contact us in time.
