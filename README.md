# YuriR
两个主题+一些函数
# 安装YuriR包
devtools::install_github("Yurisuriyel/YuriR")
# 加载的相关包
"rio":导入数据
"data.table":高性能处理数据
"tidyverse":ggplot2,dplyr,tidyr,readr,purrr,tibble,stringr,forcats
"jmv":类似SPSS
"gtsummary":列线标
"circlize":圈图
"ComplexHeatmap":复杂热图
"ggwordcloud":词云
"survival":生存曲线
"survminer":生存曲线
"customLayout":排版布局
"gghalves":左右分半
"glmnet":Lasso回归
"shiny":交互式
"Cairo":高质量输出
"patternplot":线型填充
"pacman":
"ggbreak":
"scales":
"tidyfst":
"ggpmisc":
"jiebaR":
"DMwR2":
"mice":
"tidytext":
"hunspell":
"tokenizers":
"udpipe":
"readtext":
"textreadr":
"udpipe":
"hunspell":
"tokenizers":
"skimr":
# 可选安装的包
## 基础包
install.packages("devtools")#从GitHub上下载R包
devtools::install_github("r-lib/devtools")
install.packages("remotes")#从GitHub上下载R包
devtools::install_github("tidyverse/tidyverse")#Tidy-R(1+7)
devtools::install_github("Yurisuriyel/YuriR")#
devtools::install_github("tidymodels/tidymodels")#Tidy-R'(1+13)
remotes::install_github("rstudio/rmarkdown")#写书
remotes::install_github("rstudio/bookdown")#写书
devtools::install_github("pzhaonet/bookdownplus")#写书+
install.packages('knitr')#文档编辑必要
remotes::install_github('yihui/xaringan')#幻灯片
remotes::install_github("gadenbuie/xaringanthemer")#幻灯片主题
install.packages('tinytex')#PDF输出
tinytex::tlmgr_repo('http://mirrors.tuna.tsinghua.edu.cn/CTAN/')#PDF输出
tinytex::install_tinytex()#PDF输出
remotes::install_github("plotly/plotly")#交互网页
devtools::install_github("r-lib/roxygen2")#R包
devtools::install_github("joshuaulrich/quantmod")
devtools::install_github("joshuaulrich/xts")
devtools::install_github("GuangchuangYu/rvcheck")#更新大部分平台的R包

## 数据部分
remotes::install_github("leeper/rio")#导入数据
install.packages("tidyfst")#dplyr类似,底层使用datatable
install.packages("data.table")#高性能数据处理
data.table::update.dev.pkg()#datatable最新版
install.packages("fBasics")#正态性检验1
install.packages("timeDate")#正态性检验2
install.packages("timeSeries")#正态性检验3
install.packages("car")#方差齐性检验
install.packages("psych")#相关性检验
install.packages("jmv")#jamovi
remotes::install_github("ddsjoberg/gtsummary")#基线资料表

## 主要绘图包
install.packages("MASS")#曲线拟合
install.packages("mgcv")#曲线拟合
install.packages("hexbin")#六边形封箱热图
devtools::install_github("ChrisLou-bioinfo/gg.gap")#截断坐标轴
install.packages("survival")#生存曲线
devtools::install_github("raivokolde/pheatmap")#热图
devtools::install_github("jokergoo/ComplexHeatmap")#热图*
devtools::install_github("r-lib/scales")#缩放刻度
devtools::install_github("zzawadz/customLayout")#图片排版
devtools::install_github("trinker/pacman")#参考文献
remotes::install_github("csdaw/ggprism")#用ggplot2输出GraphPad prism的图
remotes::install_github("r-tmap/tmaptools")#专题地图
remotes::install_github("r-tmap/tmap")#专题地图
devtools::install_github('badbye/baidumap')#百度地图
devtools::install_github("EmilHvitfeldt/paletteer")#配色
devtools::install_github("calligross/ggthemeassist")#主题调整

## 文本挖掘
devtools::install_github("quanteda/readtext")#读取文本pdf、docx、xml、json
install.packages("textreadr")#rtf、html、docx
install.packages("magick")#高级图像处理
install.packages("imager")#基于CImg的R图像处理库,可以快速处理多达4个维度的图像信息（两个空间维度、一个时间或深度维度,一个颜色维度）
install.packages("av")#对音频和视频进行分析的工具
install.packages("seewave")#分析、操作、显示、编辑和合成时间波的功能（特别是音频文件）
remotes::install_github("HenrikBengtsson/future.apply", ref="develop")#多个文件的并行读取
install.packages("skimr")#用最少的代码来获知数据框的方方面面
devtools::install_github("quanteda/quanteda")
install.packages("hunspell")#拼写检查
devtools::install_github("ropensci/tokenizers")#文本切分
devtools::install_github("mkearney/textfeatures")
install.packages("udpipe")
install.packages("stringdist")#距离计算
install.packages("RSentiment")
install.packages("sentimentr")
install.packages("SentimentAnalysis")
remotes::install_github("wrathematics/meanr")
devtools::install_github("SentometricsResearch/sentometrics")

## 其他
remotes::install_github("asteves/tayloRswift")#泰勒专辑配色
devtools::install_github("sjmgarnier/viridis")#配色
install.packages("patternplot")#黑白填充
install.packages("Cairo")#PDF字体
install.packages("shiny")#不用网页开发也可以写自己的网站
install.packages("sudoku")#可以设计数独,解数独
devtools::install_github("tidyverse/magrittr")#管道符号
install.packages("tm")#文本挖掘包
devtools::install_github("mjockers/syuzhet")#文本中提取情绪和基于情绪的情节弧线
remotes::install_github("juliasilge/tidytext")#文本挖掘
remotes::install_github("igraph/rigraph@master")# igraph 网络分析库
devtools::install_github('thomasp85/ggraph')#网络、图形和树
devtools::install_github("mjockers/syuzhet")#文本挖掘
remotes::install_github("juliasilge/tidytext")#文本挖掘
remotes::install_github("EmilHvitfeldt/textdata")#文本挖掘
install.packages("reshape2")#文本挖掘
pacman::p_load_gh("trinker/qdapDictionaries","trinker/qdapRegex","trinker/qdapTools","trinker/qdap")#6800个带标签的单词,经过严格审查的学术研究
install.packages("glmnet")#LASSO回归
devtools::install_github("ltorgo/DMwR2",ref="develop")#使用局部异常因子法(LOF法)检测异常值,LOF算法只对数值型数据有效。
devtools::install_github(repo = "amices/mice")#多重插补法

## 机器学习
install.packages("h2o")#
remotes::install_github("mlr-org/mlr3verse")#

## 深度学习
remotes::install_github("mlr-org/mlr3keras")#
remotes::install_github("mlverse/torch")#
install.packages("keras")#

## ggplot2包扩展
devtools::install_github("jokergoo/circlize")#弦图
remotes::install_github("IndrajeetPatil/ggstatsplot")#GitHub
devtools::install_github("terrytangyuan/autoplotly")#为热门统计结果自动生成交互式可视化CRAN
devtools::install_github("R-CoderDotCom/calendR")#准备打印月度和年历CRAN
devtools::install_github("krassowski/complex-upset")#可视化设置的交叉点并添加注释ggplot2CRAN
remotes::install_github("wilkelab/cowplot")#"ggplot2" 的流线型绘图主题和情节注释CRAN
devtools::install_github("tdhock/directlabels")#在格子或 ggplot2 绘图中添加直接标签的框架。CRAN
devtools::install_github("R-CoderDotCom/econocharts")#微观经济学与宏观经济学图表GitHub
remotes::install_github("dreamRs/esquisse")#与您的数据互动探索和可视化ggplot2CRAN
devtools::install_github("sctyner/geomnet")#地理网通过geom_net在 ggplot2 中实现网络可视化。CRAN
devtools::install_github("AckerDWM/gg3D")#ggplot2 的 3D 透视图图GitHub
remotes::install_github("corybrunson/ggalluvial@main", build_vignettes = TRUE)
remotes::install_github("corybrunson/ggalluvial", ref = "optimization")#冲积图的"ggplot2"扩展CRAN
devtools::install_github("ggobi/ggally")#通过添加多个功能来扩展"ggplot2",以降低将几何对象与转换数据相结合的复杂性。CRAN
devtools::install_github("hrbrmstr/ggalt")#"ggplot2" 的 "地理" 、 "coords" 和 "统计数据" 的简编。CRAN
devtools::install_github("jespermaag/gganatogram")#gganatogram 使不同生物体或细胞室的组织可视化成为可能。GitHub
devtools::install_github('thomasp85/gganimate')#动画图形的语法。CRAN
devtools::install_github("jhrcook/ggasym")#具有多个刻度图的不对称矩阵绘图。CRAN
devtools::install_github("eclarke/ggbeeswarm")#创建蜜蜂温暖图,从而避免数据点重叠。CRAN
remotes::install_github("GuangchuangYu/ggbreak")#为"ggplot2"设置轴断裂CRAN
devtools::install_github("davidsjoberg/ggbump")#凹凸图和西格诺曲线。CRAN
remotes::install_github("thomas-neitmann/ggcharts")#缩短从数据可视化构想到实际绘图的距离CRAN
devtools::install_github('Selbosh/ggChernoff')#使用人脸可视化多变种数据GitHub
devtools::install_github("teunbrand/ggchromatic")#"ggplot2"的色空间刻度GitHub
devtools::install_github("kassambara/ggcorrplot")#使用"ggplot2"可视化相关矩阵CRAN
devtools::install_github("malcolmbarrett/ggdag")#因果指示环形图(DAG)在ggplot2CRAN
devtools::install_github("nsgrantham/ggdark")#主题的黑暗模式ggplot2CRAN
devtools::install_github("mjskay/ggdist")#"ggdist" 提供统计数据和地理位置,用于可视化分布和不确定性。CRAN
remotes::install_github("jonocarroll/ggeasy")#轻松访问"ggplot2"命令CRAN
remotes::install_github("yonicd/ggedit")#ggedit 旨在以交互方式编辑 ggplot 层、刻度和主题美学CRAN
devtools::install_github("daattali/ggExtra")#ggExtra 允许您将边际密度图或直方图添加到 ggplot2 散射图中。CRAN
devtools::install_github("wilkox/ggfittext")#ggplot2地理位置, 以适应文本在一个盒子里CRAN
devtools::install_github("thomasp85/ggforce")#ggforce 旨在通过 ggplot2 v2.0.0 引入的扩展系统为 ggplot2 提供缺失的功能CRAN
devtools::install_github("ProjectMOSAIC/ggformulaExtra")#ggplot2通过配方和管道CRAN
remotes::install_github('sinhrks/ggfortify')#统一界面到 ggplot2 许多流行的统计帕克奇结果。CRAN
devtools::install_github('thomasp85/ggfx')#用于"ggplot2"和"网格"的像素过滤器CRAN
devtools::install_github("wilkox/gggenes")#ggplot2绘制基因箭头图的地理图CRAN
if (!requireNamespace("BiocManager", quietly = TRUE))
  install.packages("BiocManager")
BiocManager::install("ggtree")
devtools::install_github("thackl/thacklr")
devtools::install_github("thackl/gggenomes")#比较基因组学图形语法GitHub
devtools::install_github("teunbrand/ggh4x")#定制面、多个色度和杂项选项CRAN
devtools::install_github('erocoar/gghalves')#格哈夫斯增加了半地球仪。ggplot2CRAN
devtools::install_github("XiaoLuo-boy/ggheatmap")#ggplot2 版本的热图CRAN
devtools::install_github("rivasiker/ggHoriPlot")#地平线图ggplot2CRAN
remotes::install_github("statsmaths/ggimg")#图形层,用于绘制带有 ggplot2 的图像数据。CRAN
devtools::install_github("aphalo/gginnards")#查找、删除、插入和移动绘图层。从存储在 ggplot 对象中的数据对象中删除未使用的数据。将数据转储到 R 控制台。GitHub
remotes::install_github("davidchall/ggip")#IP 地址和网络的数据可视化CRAN
devtools::install_github('davidgohel/ggiraph')#htmlwidget 使 "ggplot" 图形交互。CRAN
devtools::install_github("graysonwhite/gglm")#线性模型诊断图的图形语法。CRAN
remotes::install_github("jjchern/gglorenz")#在 ggplot2 的祝福下绘制洛伦茨曲线。CRAN
devtools::install_github("haleyjeppson/ggmosaic")#格格马赛克通过geom_mosaic在 "ggplot2" 中实现马赛克地块。CRAN
devtools::install_github("robjohnnoble/ggmuller")#创建穆勒绘图,用于可视化进化动态。CRAN
remotes::install_github("briatte/ggnetwork")#gnetwork 包提供了一种用 ggplot2 构建网络绘图的方法。CRAN
install.packages("ggnewsccale")#在"ggplot2"中使用多个填充和色度。CRAN
devtools::install_github("EmilHvitfeldt/ggpage")#创建页面布局可视化。CRAN
devtools::install_github("martin-borkovec/ggparty",dependencies=TRUE)#ggplot2包的可视化partykitGitHub
remotes::install_github("coolbutuseless/ggpattern")#ggplot2 地理位置的模式填充。GitHub
devtools::install_github("eliocamp/ggperiodic")#自动增强周期性数据ggplot2GitHub
devtools::install_github("mikabr/ggpirate")#海盗阴谋ggplot2GitHub
devtools::install_github("aphalo/ggpmisc")#带标模型方程、ANOVA 表、摘要表的注释图;发现和标记山峰和山谷;注释支持分组和方面。CRAN
devtools::install_github("LKremer/ggpointdensity")#介绍 ： 散射图和二元密度图之间的交叉。geom_pointdensity()CRAN
devtools::install_github('erocoar/ggpol')#ggpol 将议会图表和其他几个地理图添加到 ggplot2 中。CRAN
devtools::install_github("aphalo/ggpp")#将绘图、表格和凹槽添加为绘图插图集;将标签从焦点或线路上移开;按局部密度过滤观测结果。CRAN
devtools::install_github("kassambara/ggpubr")#基于"ggplot2"的出版物准备绘图CRAN
devtools::install_github("kenithgrey/ggQC")#使用 ggQC 绘制单层、分面和多层质量控制图表。CRAN
#install.packages("ggQQunif")#制作大数据的QQ图,期望统一分布,例如p值
remotes::install_github("mitchelloharawild/ggquiver")#"ggplot2"的奎弗/速度图。CRAN
devtools::install_github("ricardo-bion/ggradar",dependencies=TRUE)#ggplot2构建雷达图表。CRAN
devtools::install_github('thomasp85/ggraph')#ggraph 是针对绘图般的数据结构(图形、网络、树木、层次结构...)量身定做的。CRAN
devtools::install_github('VPetukhov/ggrastr',build_vignettes = TRUE)#只对情节的特定层进行光击CRAN
devtools::install_github("slowkow/ggrepel")#将重叠的文本标签相互排斥。CRAN
remotes::install_github("wilkelab/ggridges")#里奇林情节地理为 "ggplot2"CRAN
remotes::install_github("nanxstats/ggsci")#受科学期刊和科幻电视节目启发的"ggplot2"调色板系列。CRAN
devtools::install_github("ellisp/ggseas/pkg")#ggplot2 的飞行扩展的季节性调整。CRAN
remotes::install_github("ggseg/ggseg")#绘制大脑地图集分割的多边形GitHub
devtools::install_github("omarwagih/ggseqlogo")#使用 ggplot2 的出版物就绪序列徽标。GitHub
devtools::install_github("marcmenem/ggshadow")#在线条下画一个阴影,使繁忙的情节更美观GitHub
devtools::install_github("jtlandis/ggside")#侧语法图形CRAN
remotes::install_github("const-ae/ggsignif")#"ggplot2"的"意义支架"。CRAN
devtools::install_github("oldlipe/ggsom")#此包的目的是提供基于自组织地图的图形的更多变异性。CRAN
install.packages("ggspectra")#"ggspectra"扩展了"ggplot2",并带有用于绘制光谱的统计数据、地理位置和注释。CRAN
devtools::install_github("lionel-/ggstance")#ggstance 实现普通 ggplot2 地理群系的水平版本。CRAN
remotes::install_github("IndrajeetPatil/ggstatsplot")#"ggstatslot"提供了一系列功能,以增强"ggplot2"图,并提供统计测试的结果。CRAN
devtools::install_github("ricardo-bion/ggtech",dependencies=TRUE)#ggplot2 技术主题、比例和地理位置。CRAN
remotes::install_github("wilkelab/ggtext")#改进的文本渲染支持ggplot2CRAN
devtools::install_github(c("hadley/ggplot2", "jrnold/ggthemes"))#一些额外的地理,尺度和主题为 ggplot 。CRAN
devtools::install_github('Mikata-Project/ggthemr')#格格洛特的主题GitHub
devtools::install_github('Ather-Energy/ggTimeSeries')#此 R 包提供新颖的时间系列可视化。CRAN
devtools::install_github("rnabioco/ggtrace")#Outline groups of data points using ggplot2
install.packages("ggtree")#gtree 专为可视化噬菌体树和不同类型的相关注释数据而设计。GitHub
devtools::install_github("const-ae/ggupset")#组合矩阵轴,用于"ggplot2"创建"上置"图CRAN
devtools::install_github("lepennec/ggwordcloud")#云文本地理图为"ggplot2"的单词。CRAN
devtools::install_github("brandmaier/ggx")#"ggplot2"的自然语言界面。CRAN
remotes::install_github("hrbrmstr/hrbrthemes")#额外的 [ggplot2] 主题、刻度和实用程序的汇编,包括绘图标签字段的拼写检查功能和对排版的整体强调。CRAN
devtools::install_github("benskov/humapr")#用胆汁可视化地形人类数据GitHub
devtools::install_github("stefanedwards/lemon")#重新定位图例并将括号添加到轴中以"ggplot2"。CRAN
devtools::install_github("yeukyul/lindia")#创建线性回归的诊断图CRAN
remotes::install_github("thomas-neitmann/mdthemes",upgrade="never")#将文本渲染为标记/HTML 的"ggplot2"主题GitHub
devtools::install_github("sachsmc/plotROC")#plotROC 提供用于 Web 使用的交互式 ROC 曲线图和打印版本的功能。CRAN
devtools::install_github("aloy/qqplotr")#"ggplot2" 的量子量和概率图扩展CRAN
install.packages("see")#可视化工具箱,用于"易数据"和"ggplot2"的额外地理、主题和调色板CRAN
devtools::install_github("statisticsNZ/simplevis")#简单的"ggplot2"可视化,脑力和打字更少CRAN
remotes::install_github("earowang/sugrrants")#支持图表分析时间数据ggplot2CRAN
devtools::install_github("kassambara/survminer",build_vignettes=FALSE)#使用"ggplot2"绘制生存曲线CRAN
devtools::install_github("wilkox/treemapify")#绘制树图ggplot2CRAN
devtools::install_github("Ryo-N7/tvthemes")#ggplot2热门电视节目的主题和调色板！CRAN
devtools::install_github("zanidean/xmrr")#从时间系列数据生成 XMR 控制图表数据。CRAN

## 其他类型R包
install.packages("showtext")#
install.packages("Sysfonts")#
install.packages("showtextdb")#
remotes::install_github("igraph/rigraph@master")#
install.packages("extrafont")#
install.packages("caTools")
install.packages("purrr")#
install.packages("fpp3")#
install.packages("timetk")#
install.packages("modeltime")#
install.packages("plotly")#
install.packages("leaflet")#
install.packages("ggforce")#
install.packages("treemapify")#
install.packages("ggridges")#
install.packages("ggalluvial")#
install.packages("alluvial")#
install.packages("randomForest")#
install.packages("lubridate")#
install.packages("broom")#
install.packages("pROC")#
install.packages("ROCR")#
install.packages("survival")#
install.packages("statnet")#
install.packages("cartogram")#
install.packages("fmsb")#
install.packages("ggridges")#
install.packages("leaflet")#
install.packages("plotly")#
install.packages("treemap")#
install.packages("vioplot")#
install.packages("broom")#
install.packages("%>%")#
install.packages("ggmap")#
install.packages("linear models")#
install.packages("colorspace")#
install.packages("easyPubMed")#
install.packages("eulerr")#
install.packages("chorddiag")#
install.packages("ggrepel")#
install.packages("ggdendro")#环形热图
install.packages("maps")#地图
install.packages("bioacoustics")#分析声音
install.packages("radtools")#操作医学图像数据
install.packages("crimedata")#犯罪数据
install.packages("nasapower")#能源预测,全球气象。。。
install.packages("wikisourcer")#公共领域作品
install.packages("ggasym")#非对称矩阵绘图
install.packages("predict3d")#二维三维绘图
install.packages("pins")#提高速度远程操作
install.packages("sankywheel")#
install.packages("rayrender")#
install.packages("OCNet")#自然河网
install.packages("covid19us")#
install.packages("COVID19")#
install.packages("covid19.analytics")#
install.packages("regmedint")#sas部分功能
install.packages("covid19dbcand")#
install.packages("oysteR")#
install.packages("SITH")#癌症生长随机模型
install.packages("glow")#
install.packages("DataEditR")#交互编辑器
install.packages("raveio")#脑电图
install.packages("salem")#女巫
install.packages("archeofrag")#考古学
install.packages("gm")#音乐
devtools::install_github("david6marsh/himach")#超音速飞机最佳航线
install.packages("nCov2019")#
install.packages("afdx")#无黄金标准估计诊断性能
install.packages("spiralize")#阿基米德
remotes::install_github("wjakethompson/taylor")#
install.packages("DIGSS")#考古学
install.packages("igraph")#
install.packages("nloptr")#
install.packages("sp")#
install.packages("rgeos")#
## 画图包
install.packages("pez")#系统全面的系统发育R包
install.packages("r3dmol")#在R中对分子结构进行3D可视化
install.packages("ggeconodist")#可以画另类的箱线图
install.packages("lemon")#可以很方便的操作ggplot2的图例和坐标轴参考https://cran.r-project.org/web/packages/lemon/vignettes/legends.htmlcomplex-layout-with-grid_arrange_shared_legend
install.packages("ezcox")#很方便的做Cox回归分析模型和森林图
install.packages("ggstream")#河流图绘制
install.packages("arrow")#
install.packages("feather")#
install.packages("fst")#
install.packages("hexView")#
install.packages("pzfx")#
install.packages("readODS")#
install.packages("rmatio")#
remotes::install_github("ddsjoberg/gtsummary")#
devtools::install_github("GuangchuangYu/rvcheck")#
remotes::install_git("appliedepi/epirhandbook")#该包集合了流行病学中诸多描述性分析的函数。其中epi.tests函数专门用于计算诊断试验的灵敏度、特异度及预测值等指标。详细介绍可以看链接 https://rpubs.com/maomaoworm/690424
devtools::install_github("DillonHammill/DataEditR")
devtools::install_github("DillonHammill/rhandsontable")#类似于excel的功能,对R语言已经读入的数据进行修改
install.packages("job")#如果命令运行时间过长,是不能运行下一步命令的,这个包里可以将时间比较长的命令放到后台
remotes::install_github("igraph/rigraph@master")
install.packages("fBasics")#正态检验
devtools::install_github("kassambara/ggpubr")#直接帮你画出箱线图、密度分布图、直方图、点图、偏差图的同时标上significance levels
install.package('tinytex')
tinytex::install_tinytex()
install.package('rticles')
devtools::install_github("joshkatz/needs", ref = "development")
## 机器学习包
install.packages("caret")#类似于python的sciki-learn包,提供多种算法的api,同时也有交叉验证,数据预处理等函数,相当强大
install.packages("randomForest")#最忠实于原文献的随机森林算法包
install.packages("xgboost")#大名鼎鼎的xgboost,kaggle高位利器
install.packages("arules")#关联算法
install.packages("C50")#C50决策树算法包
install.packages("rpart")#CART决策树算法
install.packages("e1071")#SVM和Naive Bayes
install.packages("nnet")#神经网络算法
install.packages("neuralnet")#神经网络算法
install.packages("mxnet")#深度学习框架
install.packages("tensorflow")#深度学习框架
install.packages("lubridate")#时间处理最好的包,没有之一
install.packages("broom")#将各种统计学模型结果数据框化
install.packages("magrittr")#管道符
install.packages("zoo")#时间序列
install.packages("forcats")#时间序列
install.packages("pROC")#绘制ROC曲线
install.packages("ROCR")#绘制ROC曲线
install.packages("igraph")#网络图以及pagerank算法
install.packages("network3D")#结合D3.js
install.packages("DBI")#和SQL的交互
