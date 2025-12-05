<div align="center">
  <a href="https://github.com/{{github_username}}/{{github_repo_name}}">
    <img src="assets/logo.gif" alt="Repo Logo" height="240">
  </a>
</div>

---

<h1 align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" alt="Rocket" width="25" height="25" />
XYZCylinder: Towards Compatible Feed-Forward 3D Gaussian Splatting for Driving Scenes via Unified Cylinder Lifting Method
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" alt="Rocket" width="25" height="25" />
</h3>

<h3 align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Sparkles.png" alt="Sparkles" width="20" height="20" />
  <a href="https://yuyuyu223.github.io/howsenfisher.github.io/">Haochen Yu</a>,
  <a href="https://scholar.google.com/citations?user=TNDbzzMAAAAJ&hl=zh-CN">Qiankun Liu</a>,
  <a href="https://scholar.google.com/citations?user=Gt3-rnAAAAAJ&hl=zh-CN">Hongyuan Liu</a>,
  <a href="https://jianfeij.github.io/">Jianfei Jiang</a>,
  <a href="https://openreview.net/profile?id=~Juntao_Lyu1">Juntao Lyu</a>,
  <a href="https://scholar.google.com/citations?user=A1gA9XIAAAAJ&hl=zh-CN">Jiansheng Chen</a>,
  <a href="http://www.3dimagelab.com/index.php/huimin-ma/">Huimin Ma</a>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Sparkles.png" alt="Sparkles" width="20" height="20" />
</h3>
<h3 align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Sparkles.png" alt="Sparkles" width="20" height="20" />
  University of Science and Technology Beijing
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Sparkles.png" alt="Sparkles" width="20" height="20" />
</h3>

<p align="center">
<a href="#">
      <img src="https://custom-icon-badges.demolab.com/badge/code-comming%20soon-blue?logo=code" />
    </a>
    <a href="#">
      <img src="https://custom-icon-badges.demolab.com/badge/Paper-Under%20Review-green?logo=paper" />
    </a>
    <a href="https://yuyuyu223.github.io/XYZCYlinder-projectpage/">
      <img src="https://custom-icon-badges.demolab.com/badge/Project%20Page-purple?logo=web" />
    </a>
    <a href="https://huggingface.co/howsenfisher/XYZCylinder">
      <img alt="Tests Coverage" src="https://img.shields.io/badge/%F0%9F%A4%97%20Huggingface-coming%20soon-orange" />
    </a>
    <a href="https://www.modelscope.cn/models/yuyuyu223/XYZCylinder">
      <img alt="Issues" src="https://custom-icon-badges.demolab.com/badge/ModelScope-coming%20soon-624aff.svg?logo=modelscope&logoColor=white" />
    </a>
    <!-- <a href="#">
      <img alt="Issues" src="https://custom-icon-badges.demolab.com/badge/Video-Youtube-FF0033.svg?logo=youtube" />
    </a>
    <a href="#">
      <img alt="Issues" src="https://custom-icon-badges.demolab.com/badge/Video-BiliBili-FB7299.svg?logo=bilibili" />
    </a> -->
    <a href="#">
      <img alt="Issues" src="https://custom-icon-badges.demolab.com/badge/Datasets-comming%20soon-pink.svg?logo=database" />
    </a>
    <!-- <a href="#">
      <img alt="Issues" src="https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge" />
    </a> -->
  </p>


## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Animals%20and%20Nature/Fire.webp" width="20" height="20" /><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Animals%20and%20Nature/Fire.webp" width="20" height="20" /><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Animals%20and%20Nature/Fire.webp" width="20" height="20" /> News!!
* [2025-10-09] We have released the project page of XYZCylinder.



## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Spiral%20Calendar.png" alt="Spiral Calendar" width="25" height="25" /> TODO List

* [ ] Release the checkpoints in huggingface and modelscope.
* [ ] Release the whole code.
* [ ] Release the code of occ-branch training.
* [ ] Release the Carla-Centric dataset.
* [X] Release the project page.

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Blue%20Book.png" alt="Blue Book" width="25" height="25" /> About
![Image](./assets/mainpipe.png)

Feed-forward paradigms for 3D reconstruction have become a focus of recent research, which learn implicit, fixed view transformations to generate a single scene representation. However, their application to complex driving scenes reveals significant limitations. Two core challenges are responsible for this performance gap. First, the reliance on a fixed view transformation hinders compatibility to varying camera configurations. Second, the inherent difficulty of learning complex driving scenes from sparse 360° views with minimal overlap compromises the final reconstruction fidelity. To handle these difficulties, we introduce **XYZCylinder**, a novel method built upon a unified cylinder lifting method that integrates camera modeling and feature lifting. To tackle the compatibility problem, we design a Unified Cylinder Camera Modeling (UCCM) strategy. This strategy explicitly models projection parameters to unify diverse camera setups, thus bypassing the need for learning viewpoint-dependent correspondences. To improve the reconstruction accuracy, we propose a hybrid representation with several dedicated modules based on newly designed Cylinder Plane Feature Group (CPFG) to lift 2D image features to 3D space. Extensive evaluations confirm that XYZCylinder not only achieves state-of-the-art performance under different evaluation settings but also demonstrates remarkable compatibility in entirely new scenes with different camera settings in a zero-shot manner.

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bar%20Chart.png" alt="Bar Chart" width="25" height="25" /> Results
![Image](./assets/radar.png)

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bar%20Chart.png" alt="Bar Chart" width="25" height="25" /> Citation

If you find this repository useful for your research, please use the following BibTeX entry for citation.
```
@misc{yu2025xyzcylindercompatiblefeedforward3d,
      title={XYZCylinder: Towards Compatible Feed-Forward 3D Gaussian Splatting for Driving Scenes via Unified Cylinder Lifting Method}, 
      author={Haochen Yu and Qiankun Liu and Hongyuan Liu and Jianfei Jiang and Juntao Lyu and Jiansheng Chen and Huimin Ma},
      year={2025},
      eprint={2510.07856},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2510.07856}, 
}
```




