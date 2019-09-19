# Style-Transfer



### 프로젝트 진행 과정 

**대부분의 프로젝트는 Google Drive와 Google Colab에서 진행함 (코드 실행시 GPU )**

19.07.30~ 19.08.01: Style Transfer 관련 배경지식, 논문 공부
1. [A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576)
2. [Perceptual Losses for Real-Time Style Transfer and Super-Resolution](https://cs.stanford.edu/people/jcjohns/eccv16/)
3. [kaggle_kernel by greg115](https://www.kaggle.com/greg115/style-transfer)

19.08.02~ 19.08.20: 각자 다양한 방법으로 모델/코드 뜯어보기 & 변형/시도<br>
- 규원: Comparison of VGG16 and VGG19 model with output images from 5 content images and 5 style images
- 도은: VGG16, VGG19 모델 Layers Visualisation. Trying different performance comparison tests(eg. cropped image transfer)
- 세영 : content layer 17개 해체 및 다시 combining
- 제훈: convolution feature map visualization & noise image visualization
- 지선: hyperparameter 조정, multi-style-image


### Style-Transfer Github_project
path = "StyleTransfer/data/[vgg19_weights.h5](https://drive.google.com/file/d/1hEuIGJWk-hQ8vxub3Ks0GpEHT6AtRTD0/view?usp=sharing)"

<br><br>


> [OpenCV를 사용한 Neural Style Transfer](https://tykimos.github.io/2018/10/10/Neural_Style_Transfer_with_OpenCV/) trial output

![input](https://user-images.githubusercontent.com/38810970/62348502-ce457d00-b537-11e9-83f8-c48f6db84f6d.jpg)

![st2](https://user-images.githubusercontent.com/38810970/62348495-cab1f600-b537-11e9-9f42-07dd8211b0c0.jpg)
![st3](https://user-images.githubusercontent.com/38810970/62348496-cab1f600-b537-11e9-9335-c30a9df4ed7e.jpg)
![st4](https://user-images.githubusercontent.com/38810970/62348497-cb4a8c80-b537-11e9-8b80-09117100a9a4.jpg)
![st1](https://user-images.githubusercontent.com/38810970/62348499-cd145000-b537-11e9-8bef-e18d8b59cdba.jpg)

