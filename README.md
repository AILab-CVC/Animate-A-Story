<div align="center">

<h2>Animate-A-Story: Storytelling with Retrieval-Augmented Video Generation</h2> 

 <a href='https://arxiv.org/abs/2307.06940'><img src='https://img.shields.io/badge/ArXiv-2305.18247-red'></a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href='https://VideoCrafter.github.io/Animate-A-Story'><img src='https://img.shields.io/badge/Project-Page-Green'></a> 
  

_**[Yingqing He*](https://github.com/YingqingHe), [Menghan Xia*](https://menghanxia.github.io/), Haoxin Chen*, [Xiaodong Cun](http://vinthony.github.io/), [Yuan Gong](https://github.com/yuanygong), [Jinbo Xing](https://doubiiu.github.io/),<br> 
[Yong Zhang<sup>#](https://yzhang2016.github.io), [Xintao Wang](https://xinntao.github.io/), Chao Weng, [Ying Shan](https://scholar.google.com/citations?hl=zh-CN&user=4oXBp9UAAAAJ) and [Qifeng Chen<sup>#](https://cqf.io/)**_

(* first author, # corresponding author)

</div>

## 🥳 Demo
<p align="center"> <img src="assets/demo1.gif" width="700px"> </p>


## 🔆 Abstract
<b>TL; DR: 🤗🤗🤗 **Animate-A-Story** is a video storytelling approach which can synthesize high-quality, structure-controlled, and character-controlled videos.</b>

> Generating videos for visual storytelling can be a tedious and complex process that typically requires either live-action filming or graphics animation rendering.
To bypass these challenges, our key idea is to utilize the abundance of existing video clips and synthesize a coherent storytelling video by customizing their appearances. 
We achieve this by developing a framework comprised of two functional modules: (i) Motion Structure Retrieval, which provides video candidates with desired scene or motion context described by query texts, and (ii) Structure-Guided Text-to-Video Synthesis, which generates plot-aligned videos under the guidance of motion structure and text prompts.
For the first module, we leverage an off-the-shelf video retrieval system and extract video depths as motion structure. 
For the second module, we propose a controllable video generation model that offers flexible controls over structure and characters. The videos are synthesized by following the structural guidance and appearance instruction. To ensure visual consistency across clips, we propose an effective concept personalization approach, which allows the specification of the desired character identities through text prompts.
Our experiments showcase the significant advantages of our proposed methods over various existing baselines. Moreover, user studies on our synthesized storytelling videos demonstrate the effectiveness of our framework and indicate the promising potential for practical applications.


## 😉 Citation
```bib
@misc{he2023animate-a-story,
      title={Animate-A-Story: Storytelling with Retrieval-Augmented Video Generation}, 
      author={Yingqing He and Manghan Xia and Haoxin Chen and Xiaodong Cun and Yuan Gong and Jinbo Xing and Yong Zhang and Xintao Wang and Chao Weng and Ying Shan and Qifeng Chen},
      year={2023},
      eprint={todo},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
## 📭 Contact
If your have any comments or questions, feel free to contact [Yingqing He](yhebm@connect.ust.hk), [Menghan Xia](menghanxyz@gmail.com) or [Haoxin Chen](jszxchx@126.com).
