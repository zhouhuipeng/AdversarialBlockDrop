# Adversarial Block Drop Attack（ABD）
# Transferable Adversarial Examples against Vision Transformers via Adversarial Block Drop
Full paper：https://github.com/zhouhuipeng/AdversarialBlockDrop/blob/main/Transferable%20Adversarial%20Examples%20against%20Vision%20Transformers%20via%20Adversarial%20Block%20Drop.pdf
### Our Code is coming soon.^-^

![fig1](https://github.com/zhouhuipeng/AdversarialBlockDrop/assets/27478201/f430d604-1847-46ca-b731-8ba40e336e1e)

![@W$D6YAFU{${3PW @ RF3P9](https://github.com/zhouhuipeng/AdversarialBlockDrop/assets/27478201/a5e99c38-be29-46ba-a724-ef3e02a2d519)

## Abstract
Vision Transformers (ViTs) have shown impressive performance in various vision tasks, which has aroused scholarly interest in studying adversarial example generation and transferability on ViTs. ViT has architecture with self-attention at its core, which is entirely different from traditional convolutional neural networks (CNNs). However, existing adversarial attacks have limited effect on ViTs due to neglecting these architectural features. To address this issue, we propose a self-attention oriented Adversarial Block Drop (ABD) method to generate transferable adversarial examples by skipping attention mechanism from partial blocks. The ViT encoder consists of multiple blocks that are consistent architectures consisting of a self-attentive layer and a feed-forward layer. Specifically, we tailor our approach to this architecture, enhancing self-attention uncertainty by dropping some of the blocks during inference and thus fooling the model decisions. This exploits a unique but widely used architectural feature in the transformer model that can be used as a general attack pattern. Extensive experiments using multiple popular transformers on ImageNet datasets show that the proposed ABD significantly outperforms other baseline methods. Our approach can greatly improve the transferability between ViTs and from ViTs to both CNNs and MLPs, demonstrating the true generalization potential of ViTs in the adversarial space.

## Experiments

We conducted extensive experiments using the unused Vision Transformer model as an alternative model to generate adversarial samples to attack other unknown black -box models.

### Transferring to ViTs
![T6PDQ7KW3 7ECPFEO@O9`5P](https://github.com/zhouhuipeng/AdversarialBlockDrop/assets/27478201/1e8c1665-0b5b-4144-9db7-e1a348113105)

### Transferring to non-ViTs
![ADF%NB~Q9H`WP)PYH6NGR)D](https://github.com/zhouhuipeng/AdversarialBlockDrop/assets/27478201/ccbd8c04-b2eb-40f3-bbde-ee252bfe0898)

### Evading defenses
![defense](https://github.com/zhouhuipeng/AdversarialBlockDrop/assets/27478201/8499ca5c-ad88-41ba-b94b-e24b26f6a49b)

### Comparison with attacks that target ViTs
![sota-comparison](https://github.com/zhouhuipeng/AdversarialBlockDrop/assets/27478201/2cb10a57-28a5-42b7-aad2-fe51403eb2a9)

### Discussion of the effect of P
![p-fr-acc-diversity](https://github.com/zhouhuipeng/AdversarialBlockDrop/assets/27478201/5a19b545-3344-4422-829b-51ebdd6dbe6b)

### Visualisation of samples
![gradcam (1)](https://github.com/zhouhuipeng/AdversarialBlockDrop/assets/27478201/84e067cc-12b4-4898-82d9-f592d3d362c9)

