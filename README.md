# Inclusive Fashion AI project v2 (InFashAIv2)
<img align="right" src="https://github.com/hgilles06/infashaiv2/blob/main/Image_18678.jpg?raw=true " width="200" height="300" />

We are happy to release the second dataset of the InFashAI initiative (InFashAIv2). InFashAIv2 contains 60,636 images with their descriptions.The first version (InFashAIv1) was released [here](https://github.com/hgilles06/infashai) and contains 15,716 images.
To access the dataset, please download the CSV table [here](https://drive.google.com/file/d/14CeDWPJA4EhCuvK-VTjznRTLWayaRFms/view?usp=sharing). This dataset contains three columns:

1-**image_name**: the name of the image file

2-**image_link**: the link to download the image. Images are stored in an Oracle Cloud bucket.

3-**description**: the description of the image. It may contain inconsistent descriptions. So we strongly recommend a filtering step before using them.

## Context 
AI technologies are revolutionizing every industry and forcing key industry players to reinvent their businesses. This revolution and its exponential advances do not spare the fashion industry. Well-trained AI models can now describe a dress model, extract its attributes (color, style, sleeve type, Etc.), predict future fashion trends, and even offer personalized clothing styles. Several publicly large datasets of fashion images (e.g., Deepfashion) made it possible.
However, available datasets need to be more diversified as they are generally western-centric. Indeed, AI models trained with under-diversified datasets have limited generalization capabilities. Therefore they may not perform well for African fashion styles, limiting the adoption of AI technologies within the African fashion industry.
To allow African fashion to benefit from the potential of AI, Ai4Innov initiated the Inclusive Fashion AI research project (InFashAI), which aims to create datasets and build models that are much more representative of the fashion world's diversity. Our first goal is to create a large volume of data on African fashion by gathering scattered data accessible online using web scraping methods.

## Use cases
This dataset should only be used for research purposes. We would appreciate your feedback regarding use cases powered by the dataset. 
InFashAIv2 can potentially be used to build AI tools for (i) fashion image captioning and (ii) realistic fashion image generation from text tailored toward African fashion.

## Disclaimer
We do our best to ensure that the dataset does not contain malicious or biased data. However, due to the large volume of data, we could not perform a manual check of the whole dataset. Consequently, inappropriate images and/or descriptions might be present in the dataset. We would be delighted to have your feedback about any data point you think might be inappropriate.

## Citation
@article{hacheme2021neural, title={Neural Fashion Image Captioning: Accounting for Data Diversity}, author={Hacheme, Gilles and Sayouti, Noureini}, journal={arXiv preprint arXiv:2106.12154}, year={2021} }
