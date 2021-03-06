![语言/Language: WXML&JavaScript (shields.io)](https://img.shields.io/badge/语言%2FLanguage-WXML%26JavaScript-orange)![版本/Version: 3.2 (shields.io)](https://img.shields.io/badge/版本%2FVersion-3.2-blue)![作者/Author: 丘天惠/Autumnhui (shields.io)](https://img.shields.io/badge/作者%2FAuthor-丘天惠%2FAutumnhui-yellow)

## 😁 代码开源，欢迎学习交流（大佬不要喷，自学JavaScript） 😁

## ⚠️ 拒绝一切将他人学习成果白嫖/盈利的行为 ⚠️ （已参加小程序应用大赛）

## 如果对你有用，可以Star✨一下

--- 

# Insight 微信图像识别小程序


<center>


  <img src="https://tva1.sinaimg.cn/large/008i3skNgy1gr1pjsql8sj3076076dgu.jpg" alt="insight_qrcode"  />

> 扫码体验

</center>


---

# 一、产品概况

## 1. 介绍与需求

### 1.1 产品简介

识相 Insight 是一款免费的 **快速识别图像，获取相关知识，提升生活信息认知** 的小程序。产品通过利用人工智能的图像识别技术，对图像进行快速识别分析，迅速给用户反馈结果。识相 Insight 小程序能够帮助你识别动物、植物、汽车、菜品、物体、Logo/公司名称、文字、甚至是手写文字，并且能记录识别结果以供反复查看。

### 1.2 目标用户

**产品是工具类小程序，对年龄没有限制，老少咸宜** ，针对不同人群，目标用户包括但不限于以下类别：

- 研究动植物的园林从业者或动植物专家、相关的教师/学生
- 业余的动植物爱好者或不了解植物、动物的新手小白
- 需要获取图片中文字内容的用户
- 经常想知道汽车型号的汽车爱好者或预购人士
- 看到美食却不知道菜品名字的吃货
- Logo设计师、需要获取商品/品牌名称的人士

### 1.3 使用场景

- **想知道这是什么：**在生活中、浏览互联网时，看到的动物、植物、汽车、菜品、Logo、物体想知道名字和相关知识；家长面对孩子关于植物、动物等不知道怎么回答......
- **了解相关知识：**学生完成老师布置的植物、动物等的相关作业、园林从业者积累相关的知识......
- **文字识别：**读书笔记摘录、将纸质文件转录为电子版、购物小票转为电子版保存、上课/会议PPT文字的快速记录，转为可编辑的文本进行复制......

### 1.4 用户痛点、需求和解决方案

|                           用户痛点                           |                             需求                             |                           解决方案                           |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 走在路上常常想知道看到不认识的 动物/植物/汽车/Logo公司/物体 的名称和相关知识 |        能够立马、快速知道未知事物的名称和获取相关知识        | 通过 拍照、上传图像 ，结合人工智能图像识别技术进行分析并返回对应的结果和相关信息给用户 |
| 园林从业者/农业养殖主 看到虫类不清楚是否为害虫，不能及时处理；想要快速了解动/植物习性 | 能够快速得知物种的名称，并了解是否对 植物/作物 有害和其习性  |  通过 拍照/上传虫类图像 进行识别，并给用户相应的结果和信息   |
|           读者想要摘抄 纸质书/电子书/笔记 中的内容           |  想要即刻转为可编辑的文本，高精度快速响应的图像文字识别功能  | 使用小程序的人工智能OCR文字识别快速将内容转为可编辑文本，并一键复制 |
| 学生党/与会者 参加 课程/会议 时， 不能快速记录 黑板/PPT 中的内容 | 能够当场拍照记录或 课后/会后 使用相册中的图像进行提取记录信息 | 使用小程序的人工智能OCR文字识别快速将 黑板上的手写文字/PPT内容 转为可编辑文本，并一键复制 |

### 1.5 创新与应用

#### 1.5.1 创新点

- **用完即走，轻便快捷**：据前期市场调查， **图像识别** 类产品更多是*传统的需要下载安装的APP*，如“形色”、“白描OCR”等产品，**识相Insight小程序**能够在完成用户需求的前提下，不占用用户手机太多的空间，用完即走，给用户更加快捷清爽的体验。
- **低成本运营**：**识相Insight**小程序采用 **[TencentTCB (腾讯云开发) ](https://github.com/TencentTCB/)** 提供的云开发功能，极大程度地便利了开发者——相较于传统APP需要服务器、域名等繁琐的前提准备，识相Insight小程序使用**云存储、云函数、云数据库**等功能，**不仅在运营、提供服务上都减小了开发成本，在更新迭代、升级维护和推广各方面**都相较于传统APP更快捷、更有优势。
- **功能齐全，操作简便**：识相Insight小程序对比其他图像识别类产品，功能更加丰富，**集合了“植物、动物、物体、汽车、菜品、Logo、文字和手写文字”**识别功能于一个小程序，且能够相关信息让用户对结果充分了解，在文字识别中提供可编辑文本以及一键复制功能，还能够查看历史记录。在操作上，小程序的UI以 **卡片式设计** 为主，功能分区明显直观，用户对功能一目了然，简单且容易上手。

#### 1.5.2 实践应用

<img src="https://tva1.sinaimg.cn/large/008i3skNgy1gr1pkasy4kj30cq0cn74l.jpg" alt="image-20210504161359080" style="zoom:;" />

在小程序后台统计数据中，可以看到用户从任务栏中进入的次数占比高达75%，说明识相Insight小程序已经融入成为用户的习惯操作中，在需要的时候打开微信下拉的操作简便且快速实现需求。

**识相Insight正是因为能够快速解决用户需求、提升用户对生活信息的认知，在传统的图像识别APP中脱颖而出，极大地便利了用户的生活。**



## 2. 产品设计

### 2.1 产品结构图

**识相 Insight 小程序产品功能结构的逻辑清晰易懂，用户上手即可掌握，用户使用过程中的每一步都可以明白对应的下一步操作，快速满足用户需求。**

![识相Insight-产品结构图 (2)](https://tva1.sinaimg.cn/large/008i3skNgy1gr1pkhgokfj318f0u07ci.jpg)

### 2.2 用户流程图

**用户使用流程清晰，部分步骤有关联但不会影响每一步的使用，用户旅程、操作逻辑简单而快速。**

![识相小程序 用户流程图 (1)](https://tva1.sinaimg.cn/large/008i3skNgy1gr1pkkude5j31240u0thf.jpg)



### 2.3 UI设计规范

<img src="https://tva1.sinaimg.cn/large/008i3skNgy1gr1pko1a44j30u01ondiw.jpg" alt="WechatIMG1640" style="zoom:25%;" /><img src="https://tva1.sinaimg.cn/large/008i3skNgy1gr1pksbf66j30u01szdi2.jpg" alt="WechatIMG1644" style="zoom:25%;" />

<img src="https://tva1.sinaimg.cn/large/008i3skNgy1gr1pky9s01j30u01qp0yq.jpg" alt="WechatIMG1645" style="zoom:25%;" /><img src="https://tva1.sinaimg.cn/large/008i3skNgy1gr1pl3g20fj30u01qp0xj.jpg" alt="WechatIMG1646" style="zoom:25%;" />



>  注：标注图以px为单位，实际在小程序中以rpx为单位。

#### 2.3.1 图标系统

- **TabBar中图标采用统一的颜色系统，选中时为蓝色（#2e51ff），未选中为灰色（#b1b1b2），清晰明显，对比度强，便于区别。**三个图标分别代表为“知识”“识别”和“我的”，其中“知识”用灯泡作为知识，也代表新想法、新知识、新idea的意思；“识别”的图标与小程序Logo相同，结合眼睛和放大镜，意为去搜查我们看到的事物；“我的”
- **“识别”页和“我的”页中的图标采用Font Awesome的图标系统进行嵌入，**“识别”页中用未填充的描线图标为辅助，帮助用户更快地找到需要的功能，选中后变为主色调蓝色（#2e51ff），未选中为黑色；“我的”页中「 更多功能 」卡片使用“填充”图标作为辅助，且与下方「 更多作品 」卡片作出区别（描线图标）以显示其重要级和优先级。

#### 2.3.2 颜色系统

- 识相 Insight 采用的功能、按钮、板块分区等区域 **主色调为蓝色，给用户清晰、纯净和理智的感觉，让用户对产品产生准确、睿智的第一印象。**
- 各页面导航栏、卡片角标、识别结果页列表表头使用渐变色对比色：蓝色-->草灰色`linear-gradient(45deg, #0081ff, #1cbbb4)`，**使用主色调的对比色，使用渐变色减少色彩的单调性，使画面颜色丰富**。

#### 2.3.3 界面规范

- 卡片间距：**整体设计遵循 8px设计原则**，大量采用40px、80px为间距，在保证内容能够得到展示的前提下，充分留白，让画面更加整齐，并能够让用户更迅速定位需要的内容/功能上。
- 圆角卡片：界面中多使用卡片为依托进行展示，**卡片圆角度数为 `20rpx `即 `  10px  ` 为标准**，减少视觉上生硬的感受，使画面显得活泼、减少单调。
- 图片比例：**“知识”页中的图片多采用比例为 2：1 的图片进行显示**，在不占用太大的屏幕比例的前提下充分显示图片内容；“识别”页中的图片以嵌入卡片的形式展示，需要考虑整个卡片的占比，故使用了比例为 4：3 的图片；“识别结果”页中使用比例为 5：4 的图片，分享卡片自动截取到的图像也为 5：4 比例，与分享卡片一致。
- 板式栏高：采用小程序默认的TabBar以及NavBar高度，标准且不占用过多空间，让用户更容易点击操作。

### 2.4 操作引导设计

1. 主页功能「 识别 」功能以卡片化设计为分区，识别功能的卡片可上下滑动以点击进入不同类型的识别功能；侧导航栏以辅助定位为主，辅助用户快速定位到需要的功能，且 设计在右侧，为用户单手使用提供更便捷的操作方式。
2. 明显、简洁的界面设计和简化的功能设计让用户能够一目了然，快速上手，无需复杂繁琐的点击即可完成需求：如在“识别”页中，点击需要识别的类型即选择相机或相册进行识别后跳转结果。

# 二、技术实现

![图片 1](https://tva1.sinaimg.cn/large/008i3skNgy1gqzkuhmectj30s80gdn3b.jpg)

## 1. 技术方案

- 识别功能：调用 **[百度图像识别](https://ai.baidu.com/tech/imagerecognition) **技术 API接口服务，并使用 **小程序云开发技术中的云函数** 进行封装部署，并将用户上传的图像使用 **小程序云开发中的云存储 **进行存储。当用户选择识别类型并上传图像后，将图像保存到 **云存储** 中，再通过调用对应的云函数，将图像的发送给云函数接口，进而返回对应的识别结果，再对识别结果进行处理后进行渲染到页面并实现交互功能，从而实现识别功能。

![image-20210516160041823](https://tva1.sinaimg.cn/large/008i3skNgy1gqzkui86tjj310g0orwl2.jpg)

>  不同功能实现使用不同的云函数

![image-20210516160420222](https://tva1.sinaimg.cn/large/008i3skNgy1gqzkuj77f6j317w0tmh14.jpg)

> 在对应功能中调用云函数



- 信息存储与展示：使用 **小程序云开发中的云存储和云数据库** 将文本、图像、识别结果、用户标记等内容进行存储，展示时再通过读取数据库内容进行渲染。

  ![image-20210516160453612](https://tva1.sinaimg.cn/large/008i3skNgy1gqzkujr4u4j310g0ordk1.jpg)

  > 用户上传到云存储中的文件

  ![屏幕快照 2021-05-16 下午4.05.39](https://tva1.sinaimg.cn/large/008i3skNgy1gqzkuknrcnj310g0oragf.jpg)

  > 用户识别后的结果记录

- 识别记录：使用 **小程序云开发中的云存储** 将图像进行保存，并记录识别结果和图像的url等内容保存到  **云数据库**  中，当用户打开“识别记录”、使用“分享”功能时，将 查询数据库 并使用用户的识标进行筛选，获取数据库信息后渲染到列表，当用户点击时同时将信息传送到结果页进行渲染。

  ![屏幕快照 2021-05-16 下午5.01.32](https://tva1.sinaimg.cn/large/008i3skNgy1gqzkulnis0j317w0tm7gs.jpg)

  > 识别记录页中的开发和操作逻辑

- 文章发布：在文章/热门识别内容管理数据中，将内容存储在数据库中，并使用 **云开发的内容运营** 对数据进行快速管理更新和发布。

  ![image-20210516160907194](https://tva1.sinaimg.cn/large/008i3skNgy1gqzkumk06nj314c0qkjzj.jpg)

  > 使用云开发-内容运营对内容进行快捷管理

## 2.系统实现

### 2.1 图像识别功能

![识相小程序 图像识别功能实现 流程图](https://tva1.sinaimg.cn/large/008i3skNgy1gqzkunjer4j30q31lx78i.jpg)

（使用的 **云函数** 可见  二、技术实现-1.技术方案）

### 2.2 跳转、分享功能

#### 2.2.1 文章类跳转

文章类卡片位于「 知识 」页，文章卡片内容都是来源自 **调取云数据库内容** ，进行缓存后再在页面使用 `wx:for` 进行展示，通过点击卡片进入各文章的详细页。因此，要跳转到对应的页面，需要有一个跳转的标识：在这里使用云数据库自带产生的 ` _id `  指标进行辨别，然后带着标识进入文章详细页后，再以 `_id`为查询条件 使用  **云数据库** 的查询语句，进行查询后渲染到文章详细页。

![屏幕快照 2021-05-16 下午4.12.22](https://tva1.sinaimg.cn/large/008i3skNgy1gqzkuori3lj317w0tmdxe.jpg)

![屏幕快照 2021-05-16 下午4.15.45](https://tva1.sinaimg.cn/large/008i3skNgy1gqzkuponiqj317w0tm7m1.jpg)

#### 2.2.2 识别结果历史记录跳转

「 识别记录 」页通过获取到用户唯一的 `openid` 识标进行在 **云数据库** 中进行索引查询，并将结果（用户识别图片的 云存储URL、识别结果、识别类型）进行渲染，在用户点击时，先判断识别类型再将结果传到对应的 「 识别结果 」页并渲染展示。

![屏幕快照 2021-05-16 下午5.01.32](https://tva1.sinaimg.cn/large/008i3skNgy1gqzkulnis0j317w0tm7gs.jpg)

![屏幕快照 2021-05-16 下午5.05.39](https://tva1.sinaimg.cn/large/008i3skNgy1gqzkur50ooj317w0tmwrn.jpg)

#### 2.2.3 分享功能

通过将页面数据进行赋值，传递值前需要先将数据进行编码操作 `encodeURIComponent()` ，在接收时需要 `decodeURIComponent()` ，使用官方提供的分享功能并将数据通过 `path` 中进行参数的传递。

![屏幕快照 2021-05-16 下午5.34.50](https://tva1.sinaimg.cn/large/008i3skNgy1gqzkurlfkxj317w0tmh2n.jpg)

## 3. 测试方案

### 3.1 稳定性测试

小程序功能简明，识别功能通过上传图像识别即可测试；文章是数据库内容，只要渲染模板正确即可，稳定程度高；识别记录是通过用户唯一的openid的对数据库的读取并渲染，不会出现错误。

小程序在上线后经过200+次用户识别和反馈测试，能够稳定使用，且后端使用 TCB云开发，官方支持不用考虑服务器问题，更加稳定运行。

### 3.2 机型测试

小程序核心功能使用的是 「 调用云函数 」，更多的是对小程序的样式的不同机型的适配工作。

开发时使用标准的 `rpx`进行，非常好的适配各类机型，在不同机型下都不出现错位等bug。

![1](https://tva1.sinaimg.cn/large/008i3skNgy1gqzkus2u3kj30n30f5guu.jpg)

## 4. 利用轮子（引用代码）

- 页面样式：页面部分样式和排版使用 **[Color UI](https://github.com/weilanwl/ColorUI)** 小程序组件库。
- **[图像识别技术](https://ai.baidu.com/tech/imagerecognition)** ：使用百度AI开放平台图像识别能力，使用SDK并部署到云函数。

- 文章详细页使用了 **[插件「 html2wxml](https://mp.weixin.qq.com/wxopen/pluginbasicprofile?action=intro&appid=wxa51b9c855ae38f3c) 」**将html内容渲染为wxml进行展示。
- 文章内容：来自公众号文章内容，已注明来源。

# 三、运营维护

1. 上线和指标

   小程序已经发布上线。

   根据小程序的运营状况，近3月运营违规和代码审核状况综合评估结果 **“运营指标” 为 优秀**，代码被驳回次数为 0 次，运营处罚 为0 次；根据小程序性能指标为 “ 良好 ”。

   ![屏幕快照 2021-05-17 上午9.01.54](https://tva1.sinaimg.cn/large/008i3skNgy1gqzkussud9j319j0u07u0.jpg)

2. 运营

   上线后的运营工作主要是「 知识页 」文章和热门识别结果的更新，通过 **TCB云开发的 内容运营CMS后台**，能够在网页端快速更新和修改内容，便捷的方式让运营成本大大降低的同时，更提高了更新维护的效率。

   ![image-20210516160907194](https://tva1.sinaimg.cn/large/008i3skNgy1gqzkumk06nj314c0qkjzj.jpg)

3. 应用效果

   自上线以来，已有 100+ 用户使用，通过云存储的使用空间推算（总共使用 279Mb / 每张图像约150 Kb ）约为 1900张 图像，即用户平均上传15+张图像，部分用户已经产生了对产品的黏性，当想到时会使用小程序，大大提升了生活的认知。

   ![image-20210517100746592](https://tva1.sinaimg.cn/large/008i3skNgy1gqzkutwwcrj31540r3tgo.jpg)

# 四、其他

- 服务提供商

  - **[百度AI开放平台](https://ai.baidu.com/)**
  - **[html2wxml富文本组件 | 小程序插件 | 微信公众平台 (qq.com)](https://mp.weixin.qq.com/wxopen/pluginbasicprofile?action=intro&appid=wxa51b9c855ae38f3c&token=627583336&lang=zh_CN)**
  - **[Color UI](https://github.com/weilanwl/ColorUI)**
  - 各公众号内容（已注明来源）
