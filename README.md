# [KOR] TesTime
> collection of colab files for quick testing

    .
    ├── basic_cv                        # 기본적인 컴퓨터비전 테스트용 colab 파일들  
    +   ├── test_median_bground.ipynb       # cctv와 같은 고정 시야 영상에서 median을 이용해 배경 이미지 추출 
    ├── data                            # 테스트용 샘플 데이터
    +   ├── readme.md                       # 샘플 데이터에 대한 출처, 라이선스 등에 대한 설명 
    +   ├── sample_cctv.mp4                 # AI Hub에서 제공 cctv 관련 샘플 데이터의 크기 축소본 
    ├── diffusers                       # 허깅페이스 diffusers 관련
    +   ├── 01_guideline.ipynb              # 기본 사용법 01: diffuser 기본 파이프라인 그리고 모델과 스케쥴러로 세분화 
    +   ├── 02_guideline.ipynb              # 기본 사용법 02: unet, vae 등으로 더욱 세분화 
    +   ├── test_controlnet_aux.ipynb       # test of 'controlnet_aux' PyPi package for ControlNet Annotators 
    +   ├── test_controlnet.ipynb           # test of 'controlnet' stable diffusion 
    +   ├── training_example.ipynb          # basics of huggingface's diffusers 
    ├── (drop) MoMOTest.ipynb           # Invariance-Driven Unsupervised Video Motion Retargeting
    ├── (drop) splice.ipynb             # Splicing ViT Features for Semantic Appearance Transfer (CVPR 2022 - Oral)
    ├── test_github_stored_image.ipynb  # github에 저장한 이미지에 대한 접근이 실패하는 이유 설명
    ├── test_github_stored_video.ipynb  # github에 저장한 비디오에 대한 접근이 실패하는 이유 설명
    └── README.md                       # this file

- diffusers/test_controlnet_aux.ipynb : https://github.com/patrickvonplaten/controlnet_aux
   - controlnet_aux: PyPi package for ControlNet Annotators
   - hed 예시
   - 설명: https://blog.naver.com/secutron/223121353455
</p>
<p align='center'>   
    <img src='https://github.com/secutron/TesTime/assets/1733748/c245e542-1ac0-4fde-b827-20abd60ffad8' width="200"/>
    <img src='https://github.com/secutron/TesTime/assets/1733748/f8f0b6bd-8f7c-419d-aab6-f0db5c275c5f' width="200"/>
</p>

- diffusers/test_controlnet.ipynb : https://github.com/lllyasviel/ControlNet
   - controlnet: "Adding Conditional Control to Text-to-Image Diffusion Models"
   - 설명: https://blog.naver.com/secutron/223121423760
</p>
<p align='center'>   
    <img src='https://github.com/secutron/TesTime/assets/1733748/9f5f20e3-dd61-41e9-8076-191a6d6f4e37' width="200"/>
    <img src='https://github.com/secutron/TesTime/assets/1733748/ee6d6e58-d41b-44f9-86c3-fa7105224da8' width="400"/>
</p>

- MoMOTest.ipynb : https://github.com/yzhq97/transmomo.pytorch
   - TransMoMo: Invariance-Driven Unsupervised Video Motion Retargeting
<p align='center'>  
  <img src='https://yzhq97.github.io/assets/transmomo/dance.gif' width='480'/>
</p>

- splice.ipynb : https://github.com/omerbt/Splice
   - splice: Splicing ViT Features for Semantic Appearance Transfer (CVPR 2022 - Oral)
   - 이론과 현실
<p align='center'>  
  <img src='https://github.com/omerbt/Splice/blob/master/imgs/teaser.png'  width='640'/>
</p>
<p align='center'>   
    <img src='https://github.com/secutron/TesTime/assets/1733748/5cbd34e9-933f-4101-aac0-4cbade73cd59' width="200"/>
    <img src='https://github.com/secutron/TesTime/assets/1733748/001e371a-a48d-4436-b56f-dc4897f97642)' width="200"/>
    <img src='https://github.com/secutron/TesTime/assets/1733748/a673fd8e-20a2-447b-ac70-49f67eb38a1f)' width="200"/>
</p>




