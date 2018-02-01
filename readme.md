# **Imagic**

0. 基于OpenCv对图像进行各种处理、检测及识别。

1. Usage 使用:

(注意：在windows系统下，如果默认的图片处理软件是系统内置的
windows照片查看器，首次使用本软件打开图片时可能会提示图片
不存在或已被删除，不需理会，再次选择图片即能正常打开，或直接识别即可。)

Detection模块：图像特性检测

edges detect:边缘检测。

Capture模块：摄像

light flow track:光流跟踪。打开摄像头，自动跟踪物体的移动。

object track：物体检测。打开摄像头后，用鼠标在屏幕中圈出
需要跟踪的物体，则自动跟踪指定物体的移动。

background subtractor:前景/背景分割。自动将摄像头画面
中的前景和背景进行分割。

Face模块:脸部检测

face recognize:人脸检测。标注出图片中的人脸及人眼等。

OCR模块：文字识别

general recognize:通用的文字识别器。

web image:在线图片的文字识别。需输入图片的链接。

id card:识别身份证。

bank card：识别银行卡。

driving license:识别驾驶证。

vehicle license:识别行驶证。

license plate:识别车牌。

business license:识别营业执照。

receipt:识别票据。

Classify模块：物体分类

car recognize:打开含有汽车的图片，识别图片中的车型。

logo recognize:识别商标。

animal recognize:识别动物。

plant recognize：识别植物。

Extra模块：
Sex Detector：色情内容鉴别，政治敏感内容鉴别。
可以鉴别本地或在线的图片是否含有“色情内容”，“性感”或“政治敏感”，
结果直接绘制在图片上，也可批量鉴别。

Face Detector:人脸鉴别。返回人物的年龄、性别、颜值、表情等信息，
结果直接绘制到图片上。

Face Match：人脸比对。选择两幅图片对比是否为同一个人，返回相似度信息。


## Change Logs:
-----------
0.1:含GUI，可打开图像，可打开摄像头，摄像头窗口图像为灰度图像。
0.2：增加保存图像功能，有保存的对话框，另外，摄像头窗口图像为彩色图像。
0.3:在Imgs.py中编写独立的显示多个图像的函数。
    增加图像相加功能。
    在GUI的左侧增加常用工具栏。
0.3.1:增加图像混合功能。
0.4:增加色情鉴别功能.
0.4.1:增加色情鉴别功能(针对在线图片)，增加批量本地图片鉴别功能.
0.4.2:增加政治敏感内容鉴别.
增加外貌鉴别，增加人脸对比。
增加通用文字识别，增加网络图片文字识别。
增加身份证识别，增加银行卡识别。
增加驾驶证识别，增加行驶证识别。
增加车牌识别，增加营业执照识别。
增加票据识别。
增加汽车识别。增加logo识别。
增加动物识别。增加植物识别。
0.5:增加人脸识别。
增加光流跟踪。增加对象跟踪。前景/背景分割。
增加边缘检测。


## To do:
-----------
1. 增加保存摄像的功能（即录制功能）。
2. 绘制图像轮廓。
3. 直线检测。
4. 圆环检测。
5. 分水岭算法分割图像。
6. 交互式前景提取。
7. 角点检测。
8. 图像匹配。
9. 增加仿射变换功能。
10. 增加透视变换功能。
11. 图像模糊处理。
12. 腐蚀图像。
13. 膨胀图像。
14. 利用kMeans算法实现图像压缩。
