# ProjectStart

### AI框架选择
* 三叶草竞赛：TensorFlow Caffe Torch MXNet Theano 等
* Intel杯竞赛： Caffe(C++) Chainer(Python) pyTorch(Python)
* 欲参加两次比赛：初步选择Caffe框架（C++）

### 模块A - 移动端
* 可选0：Unity3D安卓应用（C#）
* 可选1：原生安卓开发(Java Android 扩展学习) + Unity3D(C#) （有一定经验）
* 可选2：网页混合开发(Html+Css+Js) + 基于WebGL （作为预习）

### 模块B - 服务端
* 可选1：Java Servlet （Java EE 扩展学习，经验充足）
* 可选2：PHP （作为预习）
* 数据库：MySQL
* 部署：腾讯云（或阿里云）服务器

### 模块C - AI
* 可选1：服务器放置AI模块（更简单）
* 可选2：移动端放置AI模块（更复杂，但不需联网即可使用该模块）

### 技术调研
* A0 - Unity3D调用安卓摄像头
* A1 - 安卓与Unity3D交互（根据界面需求可以不做Unity3D开发）
* A2 - 混合开发调用安卓摄像头WebGL技术调研（根据界面需求）
* B2 - PHP技术调研
* C1 - Java Servlet调用C++代码
* C2 - Java Android调用C++代码
* C - Caffe技术调研

### 项目起步
* 1.功能设计，界面控件、界面跳转、界面功能、数据（前端显示+前端存储+后端存储）
* 2.选择技术，Unity3D技术确认；AI技术确认。
* 3.搭建环境：
* 3.A0 Unity3D + VisualStudio （需要调研Unity3D可调用安卓摄像头）
* 3.A1 IDEA Ultimate + Android SDK + 安卓测试机 (+A0) （时无法U3D调用安卓摄像头）
* 3.B1 IDEA Ultimate + Java EE (Maven) + Tomcat9.0 + MySQL5.7 （无需调研，工作量可估计，不确定性小）
* 3.C VisualStudio 或 Clion (基于机器学习框架的开发)
* 4.版本管理：git + Github
* 5.保证全栈开发，分工

### 进度预期
* 预计按照 A0+B1+C1 计划
* 在年前完成前三步，可以开发简单U3D应用（U3D + C#），运用Caffe框架开发程序(Caffe + C++)，一个人负责服务器开发（Java EE + MySQL）
* 摄像头相关调研，优先度低（默认不做，可替换为“访问相册”）
* Java EE 或 Java Android 与 C++ Caffe的交互或单方调用，必做，优先度普通，推荐年后做
* 期间：“中期文档”，“交付文档”与“交付产品”；
* 3.8真正完成编程（3.9 3.10现场测试）；
* 3.10产生视频Demo，添加于答辩PPT；
* 3.11答辩评奖；

### 功能设计
* 立体周历
* 详细信息日历
* 缩略月历与年历（节假日）
* 拍照或读取照片（识别笑脸）
* 地点定位，天气信息
* 输入文字（根据照片、定位、天气）
* 注册登录，同步数据，找回密码
* 历史日记信息浏览
