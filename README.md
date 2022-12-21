* 本项目分为**波形偏差修正**和**故障诊断**两大部分

  ***

  ​		高速铁路的动态响应数据可以反应线路质量劣化的真实状态，其往往作为线路质量分析和线路故障诊断的数据基础。中国铁路总公司铁路基础设施检测中心使用动车组综合检测车进行轨道动态检测（采样频率4Hz），根据计划每月两次左右，积累了大量的动态响应数据。

  1、每次的检测数据都会因为车轮打滑或空转的影响产生里程偏差，时域上表现为波形错位，对于这种随机误差影响后续的故障诊断工作，因此自动化里程校正算法的设计变得尤为重要。

  2、经第一步预处理和里程校正后的数据可以直接用于后续的时频分析，设计轨道线路故障诊断算法，建立自动化评估系统。

* 本项目用到的主要工具HDFS,Python(numpy, pandas, pyspark, pywt, matplotlib, bokeh, pyecharts, pyqt5), MySQL

![ChessUrl](https://p78.f0.n0.cdn.getcloudapp.com/items/kpu8DDb9/46b5573c-9f4a-4808-841d-842a628052ae.gif?source=viewer&v=37018064ff3bcb7172e5457a4853ecc3)

论文：

1、 [胀板区段的高低不平顺时频特征及其评估方法](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CJFD&dbname=CJFDLAST2020&filename=ZDCJ202013018&uniplatform=NZKPT&v=xXmWh5X0pLGxZCF98v-gzRD6RQ_NiqsVyj_ysvlP-nO0Jy4J0EOQDnAsOZedMmex)

2、[基于轨道平顺性的线路质量分析及其评估方法](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CMFD&dbname=CMFD202101&filename=1021535038.nh&uniplatform=NZKPT&v=Hc041iUTCbhu5uqvunrcaLOu8HQ0YATwm4rRrq4mfYxyN0VuiW2BiFzGZIN5CGl2)
