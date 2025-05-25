
<h1 align="center"> R1-searcher:  Incentivizing the Search Capability in LLMs via Reinforcement Learning</a></h1>


<div align="center">
<a href="./LICENSE"><img src="https://img.shields.io/badge/Code_License-MIT-blue" alt="license"></a>
<a href="./LICENSE"><img src="https://img.shields.io/badge/Model_License-MIT-blue" alt="license"></a>
<a href="https://github.com/RUCAIBox/R1-Searcher-plus"><img alt="Hugging Face" src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?color=8A2BE2"></a>
<a href="https://arxiv.org/abs/2505.17005" target="_blank"><img src=https://img.shields.io/badge/arXiv-b5212f.svg?logo=arxiv></a>

</div>



<h5 align="center"> If you like our project, please give us a star ⭐ on GitHub for the latest update.</h5>


# ✨ News
+ [22 May 2025] ⚡️⚡️ [**R1-Searcher++**](https://github.com/RUCAIBox/R1-Searcher-plus):We propose **R1-Searcher++**,  a framework for training LLMs to adaptively use internal and external knowledge. It uses a two-stage strategy: an initial SFT Cold-start phase for basic format learning, and an RL phase for Dynamic
Knowledge Acquisition. In the RL phase, we introduce a reward mechanism for the utilization of internal knowledge and integrate a memorization mechanism to continuously assimilate the retrieved information, thereby enriching the model's internal knowledge.
The paper can be found here: [**arxiv.org/abs/2505.17005**](https://arxiv.org/abs/2505.17005)
+ [22 May 2025] ⚡️⚡️ [**SimpleDeepSearcher-paper**](https://github.com/RUCAIBox/SimpleDeepSearcher):We release the paper of the SimpleDeepSearcher, which also explores the impact of using a distilled model as the backbone for continued reinforcement learning training, as well as the effects of incorporating long cot math reasoning data during the training process. Additionally, the paper includes comprehensive experiments. The paper can be found here: [**arxiv.org/abs/2505.16834**](https://arxiv.org/abs/2505.16834)
+ [16 Apr 2025] ⚡️⚡️ [**SimpleDeepSearcher**](https://github.com/RUCAIBox/SimpleDeepSearcher):We propose **SimpleDeepSearcher**, a framework designed to stimulate autonomous retrieval during complex reasoning via knowledge distillation and self-distillation. The goal is to achieve efficient and effective training using only a small amount of data.
+ [8 Mar 2025] ⚡️⚡️ [**R1-Searcher**](https://arxiv.org/abs/2503.05592)We propose **R1-searcher**, utilizing a *two-stage outcome-supervision reinforcement learning* approach to enable the model to learn to invoke web search during the reasoning process: first allowing the model to learn how to invoke web search, and then teaching it how to effectively use that search engine. This method does not require any instruction fine-tuning for cold start, and at the same time, it is compatible with existing Base LLMs or Chat LLMs.
# 💡 Overview


- Arxiv: [arxiv.org/abs/2505.17005](arxiv.org/abs/2505.17005)
- Model: coming soon...
- Train-data: coming soon...


# ✨ Method


# 📄 Evaluation


# 💫 Case Study

# 🙌 Compare to R1-Searcher



# 🏃 Quick Start
Coming soon... (Almost the same as R1-Searcher's.)

# 📄 Citation
Please kindly cite our report if they are helpful for your research.

```
@article{song2025r1,
  title={R1-Searcher++: Incentivizing the Dynamic Knowledge Acquisition of LLMs via Reinforcement Learning},
  author={Song, Huatong and Jiang, Jinhao and Tian, Wenqing and Chen, Zhipeng and Wu, Yuhuan and Zhao, Jiahao and Min, Yingqian and Zhao, Wayne Xin and Fang, Lei and Wen, Ji-Rong},
  journal={arXiv preprint arXiv:2505.17005},
  year={2025}
}
```

# 📄 License

This project is released under the [MIT License](LICENSE).

# 📞 Contact

For any questions or feedback, please reach out to us at [songhuatong123@ruc.edu.cn](songhuatong123@ruc.edu.cn).
