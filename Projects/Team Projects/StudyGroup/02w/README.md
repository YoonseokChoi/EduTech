# **2주차 (250114~250120)**
> [회의록](https://www.notion.so/2-2025-01-14-2025-01-20-a05c9856b702480ba0602bd4aef910aa?pvs=4)

## **주제**
> [천재교육의 천재AIDT에 대해 알아보기](https://ai.chunjae.co.kr/)

## **정리**
- **AI (Auto Intelligence)**
    - 사람의 뇌는 뉴런이라는 신경 세포를 통해 다양한 정보를 수용.
    뉴런이 얽혀있는 복잡한 신경 구조는 지각, 학습, 추론, 행동과 같은 능력(지능)을 갖게 함.사람이 자연적으로 가지는 지능이라는 점에서, 이를 '자연 지능'이라고 함.
    - 똑같은 원리를 컴퓨터에 구현한 기술이 바로 '인공 지능'.
    - 컴퓨터의 뇌는 뉴런을 수학 모델로 변형한 뉴럴 네트워크를 갖고 있음.컴퓨터는 뉴럴 네트워크를 통해 사람이 하는 것과 유사한 능력(지능)을 발휘. 사람의 지능을 컴퓨터 상에 인공적으로 실현했다는 점에서, 이를 '인공 지능'이라고 함.
- **Big Data / Machine Learning**
    - 과거 경험이나 통계 데이터를 모아놓고, 인공지능이 직접 지식을 습득.
    - 지도 학습, 비지도 학습, 강화 학습.
    - **밀크T서비스**를 통해  연간 학습자 행동 데이터 26억 건, 풀이 이력 4억 건의 데이터를 수집
    - 해당 데이터를 활용해 개인의 학습 수준과 약점을 진단, 성취도를 측정, 적합 학습 콘텐츠를 추천
- **딥러닝 (Deep Learning)**
    - 머신 러닝의 한 분야, 복잡한 데이터 작업을 자동으로 학습하고 수행하는 기술.
    - 가장 큰 특징은 데이터 특징 추출 능력입니다. 인간의 개입 없이 데이터의 패턴을 추출하고 정확성을 판단.
    - 이미지 인식, 음성 인식, 자연어 처리.
    - 이미지 인식을 예로 들면, 인식하고자 하는 대상의 특징을 패턴으로 추출해 이미지를 구분함, 구분하는 기준을 정교하게 지정할수록 정확한 결과를 기대.
- **AI 맞춤 학습 프로세스**
    - 학생이 학습을 마무리한 후, 학습 분석을 통해 학생의 학습 성취도를 파악, 맞춤형 학습 추천
    - 진단, 분석, 추천의 과정을 반복하며 이루어짐
    - 학생이 학습하며 쌓인 데이터는 학생의 학습 강점, 약점, 습관 및 태도 등을 분석하는 데 활용.
    - 학습 동기 증진 및 취약점 보완 등에 도움
- **지식 추적 KT (Knowledge Tracing)**
    - 학생의 지식 상태를 시간의 흐름에 따라 추적하는 기술
    - 과거 풀이 이력을 기반으로, 미래의 학습 수행 능력을 예측
    - 지난 교육 기록을 통해 미래의 유사한 문제에 대한 정/오답 확률을 예측할 수 있음
- **심층 지식 추적 DKT (Deep Knowledge Tracing)**
    - KT기술에 딥 러닝을 적용.
    - 시간의 흐름에 따른 ‘각 시점’을 기반으로 반복하여 지식 상태를 추적
    - 모든 문항 풀이 이력을 순차적이고 반복적으로 학습한다면, 다음 문제에 대한 정/오답 확률을 훨씬 적은 오차로 예측할 수 있게 됩니다.
    - **밀크T 초등 AI수학 서비스**에서는 DKT 기술을 활용해 학생의 지식별 숙련도를 측정, 개별 학습 계획과 개선 방안을 제시.
- **추천 알고리즘 FM (Factorization Machines)**
    - 사용자와 기존 아이템 사이의 상호작용을 계산, 새로운 아이템에 대한 반응 예측
    - ex) 
    사용자는 학생, 기존 아이템은 학생이 푼 문제.
    사용자와 아이템의 상호작용은 학생이 푼 문제의 정답 여부.
    어떤 문제를 맞히고 틀렸는지 연관성을 측정, 
    해당 데이터를 토대로 새로운 아이템인 다음 문제를 맞힐 수 있는지 예측.
    - 예측이 가능하다 ≒ 학생의 수준을 진단하여 필요한 연습을 제공해 줄 수 있다
- **심층 추천 알고리즘 DFM (Deep Factorization Machines)**
    - FM에 딥러닝을 추가한 모델
    - FM보다 정교하게 판단하여 향상된 문제 추천과 학생 진단이 가능
    - 정답 여부 뿐만 아니라 학생의 다양한 학습 요인까지 고려하여 보다 정확한 평가 가능
    - 학생과 학습 요인(문제 응답 여부, 문항 내용, 강의 시청 이력 등) 간의 관계 중 정∙오답과 가장 관련되는 요인을 찾음.
    가장 연관도가 강한 특성에 많은 중요도를 두어 새로운 문제에 대한 정답 여부를 판단
- **문항 반응 이론 IRT (Item Response Theory)**
    - 평가 문항에 대한 피험자들의 응답에 근거하여, 피험자의 능력과 문항의 특성을 측정하는 검사 이론
    - 각 문항의 통계적인 정보를 바탕으로 문항 난이도와 변별도를 계산, 
    모든 문항은 고유한 난이도와 변별도를 갖음
    - 각 능력 수준의 학생이 문항을 맞힐 확률을 나타내는 그래프인 문항 특성 곡선을 활용문항 특성 곡선을 통해 학생들이 각 문항에 반응하는 정도와 문항모수(문항 난이도, 문항 변별도, 문항 추측도)를 확인.
    - **밀크T Genia**는 IRT 이론에 근거하여 문항의 난이도와 변별도를 산정
- **컴퓨터 적응 평가 CAT (Computerized Adaptive Testing)**
    - 학생이 문제를 풀면 학생 수준에 맞는 다음 문제를 제공하는 시험 방식입니다.
    - 적은 수의 문항으로도 수준 측정이 가능, 학생의 이해도를 보다 세밀하게 측정 가능
    - **밀크T**의 ‘**내전석(내 아이의 전국 석차)**’은 최소 3개에서 최대 20개의 문제만 풀면 학생 수준에 맞는 다음 문제가 제시됨.
    - 제시되는 문제를 풀면 석차 확인 뿐만 아니라 중학교 학습 가이드와 추천 과정까지 제공하는 등 정교한 1:1 수준별 맞춤 학습이 가능.
- **음성인식 STT (Speech To Text)**
    - 사람의 음성을 컴퓨터가 인식해 텍스트화 할 수 있는 인공지능
    - 다양한 환경 잡음을 포함한 소리에서 음성만을 명확히 구분하여 음성이 어떤 단어, 어떤 문장을 말하고 있는지 정확하게 텍스트로 변환.
    - **밀크T AI구구단**에서 활용, 마이크를 통해 학생의 음성을 인식하고 이를 텍스트로 변환해 AI와 대화하듯이 구구단 문제를 주고 받음.
- **음성평가**
    - 원어민 발음을 바탕으로 음성의 높낮이나 발음을 평가하는 모델.
    - 문장을 읽게 되면 인공지능은 학생의 음성을 녹음하여 발음이 얼마나 정확한지,  원어민과 비슷한지 판단하고 녹음 된 음성을 다시 들려주며 실시간으로 분석 그래프와 발음 점수도 제공.
    - 타 음성 평가 기술의 경우 대부분이 문장 단위로 평가를 하는 반면, 
    천재의 음성 평가 기술은 단어로도 평가가 가능.
    - **밀크T AI 스피킹**에서 객관적인 분석을 위해 발음 평가를 사용하고 있음
- **손글씨 인식 CNN (Convolutional Neural Network)**
    - 데이터로부터 주요 특징을 찾아내고, 직접 학습하여 데이터 분류를 가능.
    - 이미지에서 특징을 추출.
    - 손글씨 인식에 적용하면 각 문자가 어떤 패턴을 가지는지 고유한 특징을 추출하고 학습.새로운 이미지를 인식시켰을 때 패턴을 발견하고 어떤 문자에 해당하는지 찾아내 분류.
    - 손글씨를 정확하게 인식하고 분류하여, 주관식 문제도 자동 채점 가능.
    - **밀크T**에 탑재된 손글씨 인식 엔진은 딥 러닝 기술을 적용한 모델입니다.
    CNN을 통해 유아 필기 데이터를 정제하고 학습하여 평균 90% 이상의 인식률 달성. 
    (한글 90%, 영어 95%)
- **광학 문자 인식 OCR (Optical Character Recognition)**
    - 이미지나 문서에서 문자를 감지하고 이것을 컴퓨터가 이해할 수 있는 텍스트로 변환.
    - 학습지를 촬영하면, 학습지 안에 있는 문제를 글씨나 수식으로 인식해 유사한 문제를 찾아냄.
    - **닥터매쓰** 유사 문제 검색 서비스에서는 문제집에서 원하는 문제를 촬영하면 문자 부분을 인식하고 디지털에서 사용 가능한 텍스트로 변환하여, 추출한 텍스트를 활용해 천재교육의 수학문제 DB에서 유사한 문제를 찾아 제공.
- **안면인식 FRT (Facial Recognition Theory)**
    - 컴퓨터가 이미지를 인식하고 이미지의 특징을 추출.
    - 개인 얼굴의 코의 폭, 눈의 길이 등 각 점 사이의 거리를 측정하여 입력된 개인의 특징으로 유사한 이미지 생성.
    - 천재교육의 학습 컨텐츠에 적용되어, **나와 닮은 역사 속 인물**을 찾아주는 흥미로운 학습 컨텐츠를 만들어냄.
- **천재 GPT**
    - ChatGPT는 유용성과 위험성 모두 가짐.적어도 학생들의 학습 관련 부분에서 잘못된 답변을 제공하는 위험성을 낮출 수 있다면, 선생님들의 걱정은 줄고 학생들의 ChatGPT의 사용은 더 안전해질 것.
    - 세상에 존재하는 많은 정보를 바탕으로 답을 주는 ChatGPT도 좋지만, 학생들의 학습 질문에 대한 답의 기반이 교과서, 지도서, 참고서, 강의 동영상 등이라면 답변의 신뢰도는 매우 높을 것이고, 학생들이 정말 알고 싶어하는 바로 그 답을 제공해 줄 수 있을 것.
- **유사도 기반 학습 챗봇**
    - `학생`: 도형 넓이 구하기는? 삼각형 아니 직각 삼각형..
    `챗봇`: "도형? 넓이? 삼각형? 직각 삼각형?" 직각 삼각형의 넓이를 구하는 공식은 넓이=(밑변X높이)÷2 입니다.
    - 유사도 기반 학습 챗봇은 질문이 입력되면 미리 학습된 질문과의 유사도를 계산하고, 그 중 가장 유사한 것에 대한 답변 3개를 학생들에게 제시.
    - 질문 유사도를 계산하면서 답변이 부합하지 못한다고 판단되면 다시 분석하여 정말 학생이 의도한 질문에 적합한 답변인지 계산하고 질문자의 의도에 알맞은 답변을 제시.
    - 즉각적이고 적합한 답변으로 학생 학습의 답답함을 해소해주는 학습 도우미
    - **밀크T**는 수학과 영어, 국어, 코딩 등 전 과목에서 학생들이 궁금증이 생기면 바로 질문하고 답변 받을 수 있도록 **AI 학습 챗봇 서비스**를 제공.
- **유사 문항 검색**
    - AI기술을 활용하여 문항 텍스트 혹은 문항의 도형 ∙ 이미지 간의 유사도를 파악하고, 이를 분석하여 높은 유사도의 문항을 찾을 수 있음.
    - OCR기술을 통해 문항 이미지에서 문자를 감지하고 기계가 이해할 수 있는 텍스트로 변환한 후 문항 텍스트 간의 유사도 분석.
    - 취약한 유형이나 자주 틀리는 개념의 문항을 검색하고, 유사한 문제를 풀어보며 취약점을 보완.
- **확장 현실 XR (eXtended Reality)**
    - 증강현실(AR), 가상현실(VR), 혼합현실(MR)의 기술을 포괄하는 개념.
    - 실제로 경험하기 어려운 환경 체험이 가능, 꼭 전용 기기가 있지 않아도 체험 가능.
    - 역사와 연관된 다양한 시대 뿐만 아니라 가보기 힘든 장소도 경험.
- **센서**
    - 인간의 감각 기관을 대체하여 학습 행동 정보를 수집하고 분석하는 장치.
    - 더욱 생생한 학습으로 학습 흥미와 효과를 높일 수 있음.
    - ex )
    태블릿 장치 마이크에 바람을 불면 민들레 홀씨가 날아가게 할 수 있음.
    세게 불면 많이 날아가고, 살살 불면 조금만 날아가도록 조절할 수 있음.
    과학 수업의 경우, 장치를 흔들어 지진을 일으키거나 체에 서로 다른 알갱이를 거르는 경험도 가능.
    - 행위의 결과가 학생에게 즉각적인 체험이 되어 입체적인 학습이 가능.
    - **밀크T초등**에서는 가속도 센서, 소리 센서, 터치 센서 등을 활용한 디지털 센서 체험을 통해 과학과 관련된 개념을 더욱 쉽고 재미있게 학습 가능.

## **핵심 키워드**
- **AI (Auto Intelligence)**
- **Big Data / Machine Learning**
- **딥러닝 (Deep Learning)**
- **AI 맞춤 학습 프로세스**
- **지식 추적 KT (Knowledge Tracing)**
- **심층 지식 추적 DKT (Deep Knowledge Tracing)**
- **추천 알고리즘 FM (Factorization Machines)**
- **심층 추천 알고리즘 DFM (Deep Factorization Machines**
- **문항 반응 이론 IRT (Item Response Theory)**
- **컴퓨터 적응 평가 CAT (Computerized Adaptive Testing**
- **음성인식 STT (Speech To Text)**
- **음성평가**
- **손글씨 인식 CNN (Convolutional Neural Network)**
- **광학 문자 인식 OCR (Optical Character Recognition**
- **안면인식 FRT (Facial Recognition Theory)**
- **천재 GPT**
- **유사도 기반 학습 챗봇**
- **유사 문항 검색**
- **확장 현실 XR (eXtended Reality)**
- **센서**

## **느낀점**
 천재AI 기술을 공부하면서 에듀테크가 얼마나 혁신적이고 강력한 도구가 될 수 있는지 다시 한 번 느낄 수 있었다. 학생의 학습 데이터를 기반으로 맞춤형 학습을 제공하는 기술들이 학습자의 약점을 보완하고 목표를 효율적으로 달성하도록 돕는다는 점이 인상적이었다. 그러나 첨단 기술에 학습자와 교육자의 현실적인 필요를 얼마나 잘 반영하느냐가 중요하다고 생각한다. 뛰어난 기술의 서비스를 제공하더라도 사용자 경험을 중심에 두지 않으면 기대한 만큼의 성과를 내지 못할 수 있기 때문이다. 에듀테크 PM으로서 단순히 기술을 이해하는 것을 넘어, 이를 서비스에 어떻게 통합하고 사용자에게 가치를 제공할 수 있을지 더 깊이 고민해야겠다.
 
 ## **회고**
 ### **좋았던 점**
- 천재 교육의 다양한 천재AI 기술에 대해 알아볼 수 있었음
### **아쉬웠던 점**
- 
---
