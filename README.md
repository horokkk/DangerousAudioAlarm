# UrbanSound8K Audio Classification Preprocessing

## 파일 설명
- `preprocess.py`: UrbanSound8K 데이터에서 MFCC(40, 174)를 추출하고
  `x.npy`, `y.npy`로 저장하는 코드.

## 실행 방법 (Colab / 로컬)
1. UrbanSound8K 데이터셋 준비
2. 필요 라이브러리 설치:
   ```bash
   pip install librosa numpy pandas tqdm kagglehub resampy
