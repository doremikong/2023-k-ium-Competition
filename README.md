## 🏆 2023 k-ium 의료 인공지능 경진대회 (최우수상)

## **📑 Summary**

**"AI로 질병 진단"**

뇌동맥류는 조기에 발견하면 치료할 수 있지만, 기존 진단 방식으로 미세한 혈관의 변화를 찾아내는 일은 쉽지 않습니다. 이에 뇌혈관조영술(DSA) **영상 데이터**를 활용하여 **뇌동맥류 여부를 자동으로 판별**하고, **위험 가능성이 높은 위치까지 예측**할 수 있는 **AI 모델**을 설계하여, 더 빠르고 정확한 진단이 가능하도록 했습니다.

---

## **💪 Contribution**

✅ **뇌혈관조영술 영상을 분석하여 뇌동맥류의 존재 여부와 위치를 예측하는 AI 모델을 개발.**

✅ **최적의 모델을 선정하기 위해 Hugging Face의 모든 CNN 모델을 for-loop로 빠르게 테스트함.**

**✅ 적은 데이터를 보완하기 위해 데이터 증강(Augmentation) 및 위치 기반 데이터 변환 기법을 적용.**

✅ **뇌동맥류 위치 예측을 위해 주요 혈관(L_ICA, R_ICA)만 선택하고 집중하는 전략 도입. → 성능 향상**

✅ **뇌동맥류 여부 예측 모델은 AUROC 0.889을 달성, 위치 예측 모델은 Accuracy 0.96을 기록 → 최우수상**

---

### **👩‍🔧 Team**

- **팀원:** AI 엔지니어 5인
- **역할:** 딥러닝 모델 설계 및 최적화 (Data augmentation, CNN 기반 모델 성능 테스트 등)
