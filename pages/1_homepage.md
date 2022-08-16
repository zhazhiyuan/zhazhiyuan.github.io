---
layout: page
title: Zhiyuan Zha
comments: true
permalink: /homepage/
---

<style>
.biblist { }

/* The item */
.biblist li { }

/* You can define custom styles for plstyle field here. */


/*************************************
   The box that contain BibTeX code
 *************************************/
div.noshow { display: none; }
div.BibTeX {
  margin-right: 1%;
  margin-left: 3%;
  margin-top: 1.2em;
  margin-bottom: 1.3em;
  border: 1px solid silver;
  padding: 0.3em 0.5em;
  background: #eeeeee;
}
div.BibTeX pre { font-size: 100%; overflow: auto;  width: 100%; }
</style>

<script>
function toggleBibtex(articleid) {
  var bib = document.getElementById('bib_'+articleid);
  if (bib) {
    if(bib.className.indexOf('BibTeX') != -1) {
    bib.className.indexOf('noshow') == -1?bib.className = 'BibTeX noshow':bib.className = 'BibTeX';
    }
  } else {
    return;
  }
}
</script>



	
### Biography
 
| <br>**Zhiyuan Zha (查志远）** is a postdoctoral research fellow at the School of Electrical and Electronic Engineering, Nanyang Technological University, Singapore, working with [Prof. Bihan Wen](https://personal.ntu.edu.sg/bihan.wen/). Prior to that, I was a postdoctoral research fellow at the School of Information and Communication Engineering, University of Electronic Science and Technology of China, Chengdu, China, working with [Prof. Ce Zhu](http://www.avc2-lab.net/~eczhu/). I received a Ph.D. degree from the School of Electronic Science and Engineering, Nanjing University, Nanjing, China, in 2018. My research interests include inverse problems in image and volume data (e.g., video, Hyperspectral image and medical image) processing, sparse signal representation, and machine learning. <br> <br> **Email：** <zhazhiyuan.mmd@gmail.com>, <zhiyuan.zha@ntu.edu.sg>. <br><br>|  ![image](https://zhazhiyuan.github.io/images/IMG_2698.JPG)|



### Publications ([**Google Scholar**](https://scholar.google.com/citations?user=JgiasCAAAAAJ&hl=en))

#### Journal Papers

* **Zhiyuan Zha**, Bihan Wen, Xin Yuan, Jiantao Zhou, Ce Zhu and Alex Chichung Kot, "Low-Rankness Guided Group Sparse Representation for Image Restoration, **_IEEE Transactions on Neural Networks and Learning Systems (TNNLS)_**, 2022. (IF: 14.255) [[PDF](https://ieeexplore.ieee.org/abstract/document/9705602)] [[Code](https://github.com/zhazhiyuan/LGSR_IR_Demo)]

* **Zhiyuan Zha**, Bihan Wen, Xin Yuan, Joey Tianyi Zhou, Jiantao Zhou and Ce Zhu, "Triply Complementary Priors for Image Restoration," **_IEEE Transactions on Image Processing_**, vol. 30, pp. 5819-5834, 2021. (IF: 11.041) [[PDF](https://ieeexplore.ieee.org/abstract/document/9457041)]
	    
		    
		     
* **Tianjing Zhang**, LiangJian Deng, Ting-Zhu Huang, Gemine Vivone and Jocelyn Chanussot. “Pansharpening via Triple-Double convolutional neural network.”  **_IEEE Transactions on Neural Networks and Learning Systems (TNNLS)_**.[[Project Page](https://liangjiandeng.github.io/index.html)][[PDF](https://liangjiandeng.github.io/papers/2022/zhang-tnnls2022.pdf)]<a href="javascript:toggleBibtex('zhangtnnls2022')" class="textlink">[BibTeX]</a>
<div id="bib_zhangtnnls2022" class="BibTeX noshow">
<pre>
@ARTICLE{zhangtnnls2022,
	author={T.-J. Zhang, L.-J. Deng, T.-Z. Huang, J. Chanussot, and G. Vivone},
	journal={IEEE Transactions on Neural Networks and Learning Systems}, 
	title={A Triple-Double Convolutional Neural Network for Panchromatic Sharpening}, 
	year={2022},
	volume={},
	number={},
	pages={},
	doi={10.1109/TNNLS.2022.3155655}
   }
</pre>
</div>

* **Tianjing Zhang**, LiangJian Deng, ZhongCheng Wu and ChaoChao Zheng “An iterative approach for image fusion with dynamic gradient sparsity and anisotropic spectral-spatial total variation.”  **_Signal, Image and Video Processing_**.


* ZiRong Jin#,  **TianJing Zhang#**, LiangJian Deng, and TaiXiang Jiang. “LAGConv: Local-Context Adaptive Convolution Kernels with Global Harmonic Bias for Pansharpening.”  **_AAAI Conference on Artificial Intelligence (AAAI 2022)_**. (#: equal contribution)[[Project Page](https://github.com/liangjiandeng/TDNet)][[PDF](https://liangjiandeng.github.io/papers/2022/jin-aaai2022.pdf)]<a href="javascript:toggleBibtex('jinif2021')" class="textlink">[BibTeX]</a>
<div id="bib_jinif2021" class="BibTeX noshow">
<pre>
@ARTICLE{jinif2021,
	author={Jin, Zi-Rong and Zhang, Tian-Jing and Jiang, Tai-Xiang and Vivone, Gemine and Deng, Liang-Jian},
	journal={AAAI Conference on Artificial Intelligence (AAAI)}, 
	title={LAGConv: Local-context Adaptive Convolution Kernels with Global Harmonic Bias for Pansharpening}, 
	year={2022},
	volume={},
	number={},
	pages={},
	doi={}
   }
</pre>
</div>

* ZiRong Jin, YuWei Zhuo, **TianJing Zhang**, XiaoXu Jin and LiangJian Deng.“Parallel Full Depth Feature Fusion Network for Pansharpening.” **_IEEE Transactions on Geoscience and Remote Sensing_**.

* ZiRong Jin, **TianJing Zhang**, Cheng Jin and LiangJian Deng. “Weighted shallow-deep feature fusion network for pansharpening.” **_2021 IEEE International Geoscience and Remote Sensing Symposium (IGARSS 2021)_**

* ShiShi Xiao, Cheng Jin, **TianJing Zhang**, Ran Ran and LiangJian Deng. “Progressice band- convolutional neural network for pansharpening.” **_2021 IEEE International Geoscience and Remote Sensing Symposium (IGARSS 2021)_**

* YuDong Wang, LiangJian Deng, and **TianJing Zhang**.“SSconv: Explicit Spectral-to-Spatial Convolution for Pansharpening.” **_2021 ACM International Conference on Multimedia (ACM MM 2021)_**. doi: 10.1145/3474085.3475600. [[Project Page](https://github.com/liangjiandeng/MUCNN)][[PDF](https://liangjiandeng.github.io/papers/2021/mucnn_mm2021/mucnn_mm2021.pdf)]<a href="javascript:toggleBibtex('mucnn')" class="textlink">[BibTeX]</a>
<div id="bib_mucnn" class="BibTeX noshow">
<pre>
@ARTICLE{mucnn,
author={Yudong Wang, Liang-Jian Deng, Tian-Jing Zhang, Xiao Wu},
booktitle={Proceedings of the 29th ACM International Conference on Multimedia (ACM MM)},
title={SSconv: Explicit Spectral-to-Spatial Convolution for Pansharpening},
year={2021},
pages={DOI: 10.1145/3474085.3475600.},
}
</pre>
</div>
* ZiRong Jin, LiangJian Deng, **TianJing Zhang** and XiaoXu Jin.“BAM: Bilateral Activation Mechanism for Image Fusion.”**_2021 ACM International Conference on Multimedia (ACM MM 2021)_**. doi: 10.1145/3474085.3475571. [[Project Page](https://liangjiandeng.github.io/Projects_Res/bam_mm2021.html)][[PDF](https://liangjiandeng.github.io/papers/2021/bam_mm2021.pdf)]<a href="javascript:toggleBibtex('BAM')" class="textlink">[BibTeX]</a>
<div id="bib_BAM" class="BibTeX noshow">
<pre>
@ARTICLE{BAM,
author={Zi-Rong Jin , Liang-Jian Deng, Tian-Jing Zhang, Xiaoxu Jin},
journal={Proceedings of the 29th ACM International Conference on Multimedia (ACM MM)},
title={BAM: Bilateral Activation Mechanism for Image Fusion},
year={2021},
volume={},
number={},
pages={DOI: 10.1145/3474085.3475571},
}
</pre>
</div>
* Wu Xiao, TingZhu Huang, LiangJian Deng and **TianJing Zhang**. “Dynamic Cross Feature Fusion for Remote Sensing Pansharpening”**_IEEE International Conference on Computer Vision (ICCV 2021)_**. doi: 10.1145/3474085.3475571. [[Project Page will be available](https://github.com/liangjiandeng/MUCNN)][[PDF](https://liangjiandeng.github.io/papers/2021/dfcnet2021.pdf)]<a href="javascript:toggleBibtex('wu_iccv2021')" class="textlink">[BibTeX]</a>
<div id="bib_wu_iccv2021" class="BibTeX noshow">
<pre>
@ARTICLE{wu_iccv2021,
	author={Wu, Xiao and Huang, Ting-Zhu and Deng, Liang-Jian and Zhang, Tian-Jing},
	journal={IEEE International Conference on Computer Vision (ICCV)}, 
	title={Dynamic Cross Feature Fusion for Remote Sensing Pansharpening}, 
	year={2021},
	doi={}
   }
</pre>
</div>


---

### Experiences 

* 09/2018-06/2022: University of Electronic Science and Technology of China (UESTC); Bachelor student in Mathematics and Physics Basic Science.

---

### Awards

* National Scholarship, 2020 and 2021

* Outstanding Students’ Scholarship of UESTC, 2019, 2020 and 2021

* First Prize, _Huawei Scholarship_, 2021

* First Prize, _Yunhui Award Special College Student Innovation and Entrepreneurship Program in UESTC_, 2021

* Excellent class member of UESTC, 2019 and 2020

* Honorable Mention, _Mathematical Contest In Modeling_, 2020

* First Prize in Sichuan Province, _China Undergraduate Mathematical Contest in Modeling_, 2020

* Third prize, _Southwest Hackathon Coding Contest_, 2020

* Third prize, _Innovation Creavitivity Entrepreneurship” Competition_, 2021





---

### Academic Activities

Peer-Reviewer: IEEE Transactions on Geoscience and Remote Sensing (IEEE TGRS)

Peer-Reviewer:  IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing (IEEE JSTARS)

Video Presentation: Record video report on AAAI 2022

Video Presentation: Record video report on ACM Multimedia 2021


---

<script type="text/javascript" src="//rf.revolvermaps.com/0/0/6.js?i=573geowbknl&amp;m=7&amp;c=ffc000&amp;cr1=ffffff&amp;f=arial&amp;l=1&amp;s=170&amp;bv=70" async="async"></script>



