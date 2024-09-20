**전자공학종합설계/송병철 교수님 2조(이건중, 우진형) Project Proposal**
1.	주제 선정 배경 (2분)
	•	주제 선정 이유: 반도체 제조 공정에서의 결함 검출은 제품 품질에 직결되는 중요한 문제임. 그러나 인간의 육안 검사에는 한계가 있어, 자동화된 결함 검출 시스템 도입이 필요함.
	•	문제점: 기존의 결함 검출은 사람의 경험에 의존하며, 시간과 비용이 많이 소요됨. 따라서 머신러닝 기반의 자동화된 검사 시스템이 필요함.
2.	주제 설명 (2~3분)
	•	프로젝트 목표: CNN을 활용하여 반도체 웨이퍼 또는 칩 이미지에서 결함을 탐지하는 머신러닝 모델 개발. 결함 탐지를 자동화하여 검사 효율성과 정확성을 높이는 것을 목표로 함.
	•	결함의 종류: 스크래치, 오염, 정렬 불량 등의 다양한 결함을 탐지할 수 있도록 할 계획.
	•	분류 방식: 결함 유무만 판단할지, 결함 종류까지 분류할지에 대한 결정 필요.
3.	예상 문제와 해결 방안 (2~3분)
	•	데이터셋 구축 문제: 실제 산업용 데이터셋에 접근할 수 없을 경우, 공개된 데이터셋 활용 (예: SEMI.org, Kaggle). 데이터가 부족할 경우, 이미지 증강 및 합성 데이터 생성 기술 사용.
	•	기존 프레임워크 문제점: 기존의 결함 탐지 시스템은 데이터 증강 및 전처리 과정이 부족해 일반화 성능이 떨어짐. 이를 해결하기 위해 다양한 증강 기법과 CNN 구조 최적화 방안을 도입할 예정.
4.	최종 예상 산출물 (2분)
	•	데모: 반도체 웨이퍼 결함 탐지 시스템의 데모. 결함이 있는 이미지와 없는 이미지를 정확히 분류하는 모델 시연.
	•	결과 시각화: 결함 탐지 결과를 시각화하여, 검출된 결함 위치를 하이라이트하는 기능도 포함.
5.	예상 기대 효과 (2분)
	•	효율성 증가: 기존의 사람에 의한 수동 검사 방식에 비해, 결함 검출 시간 단축 및 정확성 증가.
	•	제조 비용 절감: 자동화된 시스템으로 결함을 조기에 발견함으로써 제조 과정에서의 결함 비율 감소.
	•	생산성 향상: 결함 검사 인력의 부담 경감 및 검사 과정 자동화로 인한 전반적인 생산성 향상.
6.	진행 계획 (주차별) (2~3분)
	•	1주차: 문제 정의 및 데이터 수집
	•	2주차: 데이터 전처리 및 증강
	•	3주차: CNN 모델 설계 및 초기 학습
	•	4주차: 모델 성능 평가 및 하이퍼파라미터 튜닝
	•	5주차: 모델 최종 학습 및 결과 도출
	•	6주차: 데모 시스템 구현 및 발표 준비
7.	구성원 별 역할 분담 (1분)
	•	팀원 A: 데이터 수집 및 전처리 담당
	•	팀원 B: CNN 모델 설계 및 학습 담당
	•	팀원 C: 결과 분석 및 데모 시스템 구현 담당
	•	팀원 D: 프로젝트 전반적인 관리 및 발표 준비 담당

Here’s a detailed outline for your PPT slides based on your project:

### Slide 1: **Title Slide**
- **Title**: "Defect Detection on Semiconductor Wafers Using Convolutional Neural Networks"
- **Subtitle**: Capstone Design Project
- **Presenters**: Team members' names
- **Visuals**: Background image of a semiconductor wafer or a related visual

---

### Slide 2: **Introduction and Background**
- **Title**: Background and Motivation
- **Content**:
  - Importance of defect detection in semiconductor manufacturing
  - Problems with current manual inspection methods (time-consuming, prone to human error)
  - Need for automation and machine learning solutions
- **Visuals**: Flowchart or diagram of the semiconductor manufacturing process

---

### Slide 3: **Project Overview**
- **Title**: Project Objective
- **Content**:
  - Develop a CNN-based system to detect defects in semiconductor wafers
  - Target defects: scratches, contamination, misalignments, etc.
  - Classification: "Defective" vs. "Non-defective" or multi-class defect classification
- **Visuals**: Diagram showing the CNN workflow or sample defect images

---

### Slide 4: **Dataset and Data Collection**
- **Title**: Data Collection and Preprocessing
- **Content**:
  - Source datasets: SEMI.org, Kaggle wafer defect datasets
  - Techniques to handle limited data: Data augmentation (rotation, zoom, flipping)
  - Preprocessing steps: Resizing, normalizing, grayscale conversion
- **Visuals**: Example images of defects, image augmentation diagram

---

### Slide 5: **Model Selection and Development**
- **Title**: Model Development (CNN)
- **Content**:
  - CNN architecture for image classification
  - Layers involved: Convolutional layers, pooling layers, fully connected layers
  - Use of Python with TensorFlow/PyTorch for implementation
- **Visuals**: CNN architecture diagram

---

### Slide 6: **Expected Challenges and Solutions**
- **Title**: Challenges and Solutions
- **Content**:
  - Challenge 1: Limited access to real-world data → Solution: Use public datasets and data augmentation
  - Challenge 2: Potential overfitting → Solution: Regularization and model tuning
  - Challenge 3: Accuracy improvement → Solution: Hyperparameter tuning and model refinement
- **Visuals**: Graphs or flowcharts showing challenges and solutions

---

### Slide 7: **Expected Output**
- **Title**: Expected Deliverables
- **Content**:
  - CNN model capable of detecting defects with high accuracy
  - Visual demo of defect detection on wafer images
  - System that highlights defective areas on the wafer
- **Visuals**: Example of defect detection and highlighting (mock-up or demo screenshot)

---

### Slide 8: **Expected Benefits**
- **Title**: Expected Benefits
- **Content**:
  - Reduced manual inspection time and human error
  - Increased manufacturing efficiency
  - Cost reduction due to early defect detection
- **Visuals**: Graphs showing productivity improvements, comparison of manual vs automated processes

---

### Slide 9: **Project Timeline**
- **Title**: Project Timeline (Week-by-Week)
- **Content**:
  - Week 1: Data collection and preprocessing
  - Week 2: CNN model design and setup
  - Week 3: Initial training and testing
  - Week 4: Model refinement and evaluation
  - Week 5: Final model training and demo development
  - Week 6: Final report and presentation preparation
- **Visuals**: Gantt chart or timeline visualization

---

### Slide 10: **Team Roles**
- **Title**: Team Roles and Responsibilities
- **Content**:
  - Team Member A: Data preprocessing and augmentation
  - Team Member B: CNN model development
  - Team Member C: Testing and evaluation
  - Team Member D: Demo creation and final report
- **Visuals**: Team structure diagram with roles

---

### Slide 11: **Conclusion**
- **Title**: Conclusion and Next Steps
- **Content**:
  - Summary of the project’s objectives and benefits
  - Future steps after the initial development
  - Invitation for questions and discussion
- **Visuals**: Thank you message with a background related to semiconductors

---

This outline will help structure your presentation logically while keeping it within the 10-15 minute range.
