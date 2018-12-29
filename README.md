# faceid

## Face Detection and Identification for Smart Toy: Geomex Soft.

#### Jeong-Gun Lee
> School of Software, Hallym University
> Email : jeonggun.lee@gmail.com

*  *  *

인지형 스마트 토이를 만들기 위한 가장 기본적인 기능으로, 현재 토이 앞에 위치한 사람을 인식하는 것이 필요하다.
카메라를 통한 사람의 인식은 크게 두개의 스텝으로 이루어 진다.

   1. Face Recognition: 영상으로 부터 사람의 얼굴 부분을 검출
   2. Face Identification: 검출된 얼굴을 기존 학습된 데이터를 통해 ```누구```인지 파악

이러한 작업을 진행함에 있어 동영상 강의 및 코드를 오픈한 것이 있어 이를 기반으로 작업을 진행하고자 한다.

본 문서는 ```https://github.com/codingforentrepreneurs/OpenCV-Python-Series```에 기술된 코드에 대한 분석 및 응용에 대한 문서이다 [1].

*  *  *
 OpenCV를 처음 사용하는 사람으로 기존 프로그래밍 지식에 근거하여 분석을 진행한다.
 일차적으로 OpenCV를 설치하기 위하여 다음 명령어를 사용하였다 [2].
 
```
run pip install opencv-python-headless if you need only main modules
run pip install opencv-contrib-python-headless if you need both main and contrib modules 
```

이후, 해당 코드를 Github로 부터 cloning 한다.

```
git clone https://github.com/codingforentrepreneurs/OpenCV-Python-Series

Cloning into 'OpenCV-Python-Series'...
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 216 (delta 0), reused 0 (delta 0), pack-reused 215
Receiving objects: 100% (216/216), 17.13 MiB | 2.90 MiB/s, done.
Resolving deltas: 100% (91/91), done.
```

*  *  *
# References

1. [OpenCV Python TUTORIAL #4 for Face Recognition and Identification](https://www.youtube.com/watch?v=PmZ29Vta7Vc)
   - [Github](https://github.com/jeonggunlee/OpenCV-Python-Series)
2. https://pypi.org/project/opencv-python/
