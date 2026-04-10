# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 정주열
- 리뷰어 : 황성연


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - <img width="1548" height="752" alt="image" src="https://github.com/user-attachments/assets/0a500500-ebb9-4209-af8f-ae1c0382cfde" />
        - 루브릭1: 영화와 가장 유사한 단어로 다큐멘터리 , 드라마 등 의미상 바르게 나왔다
        - <img width="1702" height="1094" alt="image" src="https://github.com/user-attachments/assets/c9b65a6e-04d0-4a83-af78-51c892f607d7" />
        - 루브릭2 : 각 장르별 장르를 대표하는 단어셋이 15개씩 고르게 나왔다.
        - <img width="746" height="686" alt="image" src="https://github.com/user-attachments/assets/e9734a18-16cf-4fe6-8f66-477790359e8a" />
        - 루브릭3 : 21개 장르에 대한 히트맵을 그렸고, 성인물이 일반영화에 가깝다는 상식적 결과가 도출됨



    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - <img width="1036" height="1050" alt="image" src="https://github.com/user-attachments/assets/820bee7f-395d-499d-88c4-f0624200de10" />

        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - <img width="1021" height="473" alt="image" src="https://github.com/user-attachments/assets/a9dcc5bb-01ec-493a-b0ab-ac1c8c32773a" />
        - 장르별 단어수가 15개가 채워지지 않아 중복조건을 완화하는 방식으로 문제 해결

        
- [ ]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - <img width="1614" height="410" alt="image" src="https://github.com/user-attachments/assets/55bde090-5108-4baf-acc0-95fe85854a99" />

        
- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - <img width="780" height="182" alt="image" src="https://github.com/user-attachments/assets/23d0e5ed-835a-4153-ab6b-576f1f3e7f9c" />
        - <img width="1334" height="850" alt="image" src="https://github.com/user-attachments/assets/a7e5a536-48e8-4695-a8cb-07d731543231" />




# 회고(참고 링크 및 코드 개선)
```
임베딩 모델을 성공적으로 만들었으며, 각 장르를 대표하는 단어들을 성공적으로 얻어 weat score를 계산해 시각화해서, 상식에 부합하는 편향성 정도를 얻어냈습니다.
```
