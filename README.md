# Face-Recognition-Hadoop
>&emsp;基于计算机、网络传输以及图像处理等技术的视频监控系统被广泛应用于城市安防监控网络的建设中。一些视频处理技术，如人脸识别、车牌识别等的使用，使视频监控逐渐走向自动化、智能化，摆脱了传统视频监控中仅凭人肉眼观察不可靠的缺陷。	针对目前监控视频人脸识别系统存在两大问题：<br/>
&emsp;①当人脸数据库存在大量人脸数据时，人脸识别速度也会非常慢；<br/>
&emsp;②当监控视频资源库中视频数据增多时，检索某一目标人物在摄像头出现的相关信息的速度会越来越慢。<br/>
>&emsp;对于这两个问题，虽然能够通过优化算法和采用高性能的服务器来做出一定的缓解，但是，算法优化难度大、耗时，且高性能服务器价格高昂，这与人脸和监控视频数据会持续增多形成矛盾，无法从根本上解决问题。<br/>
>&emsp;该项目提出了将当前流行的Hadoop处理技术和监控视频人脸识别技术相结合，开发一套基于Hadoop视频图像检索的人脸识别系统。主要完成了一下工作：<br/>
&emsp;①分析了国内外在人脸识别方面的现状，了解了人脸识别的原理。为本课题的探索和系统开发提供了理论和实践指导。<br/>
&emsp;②在Linux系统下搭建伪分布式的Hadoop运行环境。Hadoop的设计初衷在于处理海量的结构化的文本数据，故无法处理非结构化的视频和图像数据。本文在研究Hadoop的输入输出和数据类型的基础上，实现了图像和视频数据的处理，即使用FFmpeg对视频进行格式转换以及将视频按一定的帧速率转化成图片，并结合OpenCV识别技术完成了该系统。<br/>
>&emsp;基于以上工作，实现了一套基于Hadoop的视频图像检索的人脸识别系统。通过运行测试，可以较好的识别出视频中的人脸，在处理速度方面相比传统的人脸识别系统有了很大的改进，这将对治安管理、刑侦执法起到更多的辅助作用。
