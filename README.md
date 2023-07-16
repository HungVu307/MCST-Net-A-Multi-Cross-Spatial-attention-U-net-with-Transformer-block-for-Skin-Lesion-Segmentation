# MCST-Net-A-Multi-Cross-Spatial-attention-U-net-with-Transformer-block-for-Skin-Lesion-Segmentation
ISIC 2018 Dataset:
PH2 Dataset:
# Abstract:
Applying deep learning to skin lesion image seg-
mentation has grown in popularity over the past few years.
It is simpler to understand the injuries and administer the
proper care using segmented images. In this research, we
proposed a new model, by building a multi-cross-attention
block, combining it with the transformer block and Unet
model. In particular, our multi-cross-spatial attention block
is highly effective when it comes to extracting features from
multiple layers, helping to increase efficiency in the image
upsample process. The transformer block that is widely used
in natural language processing (NLP) is incorporated into the
model, which helps to improve performance with processing
the highest features. Additionally, our model has the benefit of
having a small number of parameters in addition to providing
great performance on the two well-known datasets, ISIC 2018
and PH2
# Our contributions:
![image](https://github.com/HungVu307/MCST-Net-A-Multi-Cross-Spatial-attention-U-net-with-Transformer-block-for-Skin-Lesion-Segmentation/assets/106971509/84c73788-44e6-4d59-b74c-e1ef90e31b55)


- We present a new multi-cross-spatial attention block
based on the notion of attention in image segmentation,
which collects information from several encoder layers
and processes them in various ways to improve the
feature maps on the decoder side, enhance the information quality and boost the image segmentation model’s
processing effectiveness
* We develop a novel U-shape model for skin lesion
image segmentation based on the effective use of Trans-
former in natural language processing (NLP) and our
multi-cross-spatial attention gate block. In the decoder
layer, the new model is integrated with the mixer layer
to provide a Dice Similarity Coefficient (DSC) more
than 0.9 in ISIC 2018 dataset, even reaching almost 0.95 for PH2. Comparatively speaking, its performance
outperforms other skin lesion segmentation methods
+ Our suggested model has a significantly better amount
of parameters while still performing well. Our model,
which was created by ingeniously combining blocks,
has just 16M parameters, whereas other U-shape mod-
els require about or over 30M parameters to provide
decent performance
# Results
![image](https://github.com/HungVu307/MCST-Net-A-Multi-Cross-Spatial-attention-U-net-with-Transformer-block-for-Skin-Lesion-Segmentation/assets/106971509/59118ef1-3c3b-4e0e-b501-63985362ea98)

![image](https://github.com/HungVu307/MCST-Net-A-Multi-Cross-Spatial-attention-U-net-with-Transformer-block-for-Skin-Lesion-Segmentation/assets/106971509/e4d10b91-30fa-42bc-ba44-d64432f4628a)

![image](https://github.com/HungVu307/MCST-Net-A-Multi-Cross-Spatial-attention-U-net-with-Transformer-block-for-Skin-Lesion-Segmentation/assets/106971509/a9c94f3b-9706-4a6b-99af-072199252082)

![image](https://github.com/HungVu307/MCST-Net-A-Multi-Cross-Spatial-attention-U-net-with-Transformer-block-for-Skin-Lesion-Segmentation/assets/106971509/214f0b3b-903d-45ba-94be-0c28b3389599)

# Citation
