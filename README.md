<div align="center">
  <a href="https://github.com/{{github_username}}/{{github_repo_name}}">
    <img src="assets/logo.gif" alt="Repo Logo" height="240">
  </a>
</div>

---

<h1 align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" alt="Rocket" width="25" height="25" />
XYZCylinder: Feedforward Reconstruction for Driving Scenes Based on A Unified Cylinder Lifting Method
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

Recently, more attention has been paid to feedforward reconstruction paradigms, which mainly learn a fixed view transformation implicitly and reconstruct the scene with a single representation. However, their generalization capability and reconstruction accuracy are still limited while reconstructing driving scenes, which results from two aspects: (1) The fixed view transformation fails when the camera configuration changes, limiting the generalization capability across different driving scenes equipped with different camera configurations. (2) The small overlapping regions between sparse views of the 360 degree panorama and the complexity of driving scenes increase the learning difficulty, reducing the reconstruction accuracy. To handle these difficulties, we propose **XYZCylinder**, a feedforward model based on a unified cylinder lifting method which involves camera modeling and feature lifting. Specifically, to improve the generalization capability, we design a Unified Cylinder Camera Modeling (UCCM) strategy, which avoids the learning of viewpoint-dependent spatial correspondence and unifies different camera configurations with adjustable parameters. To improve the reconstruction accuracy, we propose a hybrid representation with several dedicated modules based on newly designed Cylinder Plane Feature Group (CPFG) to lift 2D image features to 3D space. Experimental results show that XYZCylinder achieves state-of-the-art performance under different evaluation settings, and can be generalized to other driving scenes in a zero-shot manner.

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bar%20Chart.png" alt="Bar Chart" width="25" height="25" /> Results
![Image](./assets/radar.png)

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bar%20Chart.png" alt="Bar Chart" width="25" height="25" /> Citation

If you find this repository useful for your research, please use the following BibTeX entry for citation.

