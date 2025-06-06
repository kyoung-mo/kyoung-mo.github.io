# 📦 YOLOv8 학습 성능 분석 문서 모음

이 폴더는 YOLOv8 기반 객체 탐지 모델의 성능을 분석하고 발표자료로 활용하기 위한 `.md` 문서 3종을 포함하고 있습니다.

각 문서는 아래와 같은 목적을 가지고 작성되었습니다.

---

## 📄 1. model_metrics_summary.md

- **목적**: YOLOv8 객체 탐지 모델의 성능 평가에 사용되는 주요 지표(mAP, Precision, Recall, FPS, Latency 등)를 개념적으로 정리
- **포함 내용**:
  - mAP@0.5, mAP@0.5:0.95의 의미와 활용법
  - FPS, latency, 모델 크기, memory usage 등의 속도·효율성 지표
  - 발표 시 활용 가능한 간단한 정의 및 멘트 예시

📌 **활용 예시**: 발표자료 이론 파트, 성능 비교 기준 설명 시 삽입

---

## 📄 2. yolov8_training_graphs_analysis.md

- **목적**: YOLO 학습 시 생성되는 `results.png` 그래프에 대한 해석 제공
- **포함 내용**:
  - train/val loss 감소 추이 해석
  - precision, recall, mAP 곡선의 의미 분석
  - 발표 시 사용 가능한 요약 멘트 제공

📌 **활용 예시**: 모델 학습이 잘 이루어졌다는 시각적 근거 설명용

---

## 📄 3. yolov8_png_files_analysis.md

- **목적**: `F1_curve.png`, `PR_curve.png`, `P_curve.png`, `R_curve.png`, `results.png` 등 YOLO에서 생성되는 시각화 `.png` 파일 각각의 의미 설명
- **포함 내용**:
  - 각 곡선이 어떤 성능을 설명하는지 정리
  - 발표 슬라이드에 어떤 파일을 어떤 맥락으로 넣어야 하는지 가이드 제공
  - 발표 시 활용할 수 있는 요약표와 멘트 예시

📌 **활용 예시**: 발표 중 그래프별 설명 슬라이드 작성 시 참고

---

## 🔖 전체 활용 팁

- 세 문서는 발표자료, 프로젝트 보고서, 캡스톤 포스터 등에 활용될 수 있습니다.
- 성능 분석 비교표, 그래프 해석, 정량 지표 설명 등 다양한 파트에서 인용 가능합니다.
- 필요 시 `.md` 파일 내용을 PPT 슬라이드로 구성해보세요!

