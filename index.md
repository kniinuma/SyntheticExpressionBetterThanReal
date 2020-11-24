[[Paper]](http://arxiv.org/abs/2010.10979)
[[Video]](https://github.com/kniinuma/SyntheticExpressionBetterThanReal/blob/gh-pages/Koichiro_WACV21_small.mp4?raw=true)

# Synthetic Expressions are Better Than Real for Learning to Detect Facial Actions

Critical obstacles in training classifiers to detect facial
actions are the limited sizes of annotated video databases
and the relatively low frequencies of occurrence of many
actions. To address these problems, we propose an approach
that makes use of facial expression generation. Our
approach reconstructs the 3D shape of the face from each
video frame, aligns the 3D mesh to a canonical view, and
then trains a GAN-based network to synthesize novel images
with facial action units of interest. To evaluate this
approach, a deep neural network was trained on two separate
datasets: One network was trained on video of synthesized
facial expressions generated from FERA17; the
other network was trained on unaltered video from the same
database. Both networks used the same train and validation
partitions and were tested on the test partition of actual
video from FERA17. The network trained on synthesized facial
expressions outperformed the one trained on actual facial
expressions and surpassed current state-of-the-art approaches.

<img align="center" width="960" src="https://user-images.githubusercontent.com/25273927/95668003-a8eccf80-0b3b-11eb-9ae6-dcbf97d535cc.jpg">

## Citation

```markdown
@inproceedings{syntheticexpressionbetterthanreal2021,
  title={Synthetic Expressions are Better Than Real for Learning to Detect Facial Actions},
  author={Niinuma, Koichiro and Jeni, L{\'a}szl{\'o} A and Onal Ertugrul, Itir and Cohn, Jeffrey F},
  booktitle={IEEE Winter Conference on Applications of Computer Vision (WACV)},
  year={2021}
}
```

