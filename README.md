# image_to_image_stable_diffusers

diffueers을 활용하여 image를 학습하여 image를 출력하는 모델입니다.

## Diffusion

이미지에 노이즈를 주고 이를 다시 역산하여 신경망에 노이즈 이미지에서 일반 이미지를 복원시키도록 학습시킨 후, 이 신경망에 노이즈만 들어있는 이미지와 적절한 힌트를 주면 해당 힌트에 맞는 이미지를 출력한다.

## 시작하기

이 지침을 따르면 로컬 컴퓨터에서 프로젝트를 실행할 수 있습니다.

### Prerequisites (전제 조건)

프로젝트를 실행하기 위해 다음 소프트웨어 및 라이브러리가 필요합니다.

- Python 3
- 필요한 Python 패키지 (requirements.txt 참조)

### 설치

프로젝트를 실행하려면 다음 단계를 따르십시오.

1. 리포지토리를 복제합니다.

```
git clone https://github.com/kiyuyeon/image_to_image_stable_diffusers.git
```

2. 프로젝트 디렉토리로 이동합니다.

```
cd image_to_image_stable_diffusers
```

3. 필요한 패키지를 설치합니다.

```
pip install -r requirements.txt
```

4. Jupyter Notebook 또는 스크립트를 실행합니다.

```
image to image.ipynb
```
![Science Subject for Middle School Comets and Meteors by Slidesgo의 사본_10](https://github.com/kiyuyeon/image_to_image_stable_diffusers/assets/66301840/bbc0b37b-e1c8-4003-b046-a4fccd821913)


