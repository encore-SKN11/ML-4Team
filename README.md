# ML-4Team


# 💰 채무 불이행 여부 예측


## **팀원** 



|![RaHymcBWPvZxahEQnSzVpHQyBa7W6ZBluEhgpnd0KvrOvM7V27lX_GJFgasqRTmx4K3HsyaqY424aaaZCnhXiQ](https://github.com/user-attachments/assets/6a60c509-9ab4-4e37-bdba-d126e60c3b8f)|![3F3F3F3F3F%3F](https://github.com/user-attachments/assets/048dba28-032b-4002-a6b5-64e5468b2471)|![gFvvZ3KYzuIl2Myys5rKWcc47oKDMNjSXrS-RJy8otGiIpJhX6SNVkVpaQQLiGZDXHPcJGG0tIiKQ2VogPb3OQ](https://github.com/user-attachments/assets/e474d56c-95c5-4d55-bea7-ec5891c39e88)|![vE55XH50ogmnoVrtTRlILwvUIkua-oK0XqndiTjRxUeYKDNZ0vhNihTUTIbYlo7z51vqxUVhvzwSeHo94Hp0-w](https://github.com/user-attachments/assets/ba871227-fa25-4fdf-9a5c-299573298a98)|![images](https://github.com/user-attachments/assets/589a6020-e1bc-4a60-9b9b-4f4461f01c6c)
|------|------|------|------|------|
|김상익|김성지|방성일|이선호|정민호|






## 📌 프로젝트 개요  
### - 데이터 출처: 데이콘 - 채무 불이행 여부 예측 해커톤: 불이행의 징후를 찾아라!
### - EDA, 데이터의 전처리와 시각화, 머신러닝을 통한 인사이트의 도출

---

## 🎯프로젝트 목표  
### - 채무 불이행 여부를 선제 파악하여, 사회적 취약 계층의 위험 방지
### - 고객의 데이터를 통해 채무를 이행할지 여부를 판단 
### - 기존 고객의 채무 불이행 과거를 분류하여 의미 있는 데이터의 생성



---

## 🔧 기술 스택

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">

<img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">

<img src="https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=NumPy&logoColor=white">


---
# 1.데이터 로드
![image](https://github.com/user-attachments/assets/8474cf7f-ec26-44de-b428-74dc05241a9d)


---
# 2. 데이터 관찰: 결측치 / 이상치 관측
![image](https://github.com/user-attachments/assets/459b2df5-200d-414b-a940-75fae53947b1)

![image](https://github.com/user-attachments/assets/98cfc55d-97be-4f1c-b0cc-d1910e451774)

![2](https://github.com/user-attachments/assets/d8293b8b-09cb-417c-85a3-001844256dad)

![image](https://github.com/user-attachments/assets/21e430d6-b638-47fe-bc8b-6f8f5a077eff)

![image](https://github.com/user-attachments/assets/07124187-45b7-4837-9244-5673ec398032)

---
# 3. 데이터 전처리
### - X와 y 분리
![image](https://github.com/user-attachments/assets/79b1ddd1-e5d7-4758-9c9c-59fce1adde61)

### - XLabel Encoding
![image](https://github.com/user-attachments/assets/783a53f6-50fe-497e-ab01-3595b7b62fba)

### - One-Hot Encoding
![image](https://github.com/user-attachments/assets/b929ac41-8b74-4eb9-a31d-9903bab805a1)


### - StandardScaling
![image](https://github.com/user-attachments/assets/18dec52a-3eab-434d-a61f-17c37537fa42)

### - Log Transition
![image](https://github.com/user-attachments/assets/4f72b1a6-fc7f-48a3-9246-72bdeaefc636)

### - train_test_split
![image](https://github.com/user-attachments/assets/44cb02ec-1a99-443c-8458-6b2eb03db530)

---
# 4. 시각화 
![1](https://github.com/user-attachments/assets/d2af6119-6bbc-4cf7-bf89-5a0ca94ce034)


![image](https://github.com/user-attachments/assets/4bc6a42c-73af-49af-9667-cad1ce4308ee)


![image](https://github.com/user-attachments/assets/9cc8ff78-0f3e-40fb-82d0-45d99768165b)


---
# 5. 회귀분석, 분류, 결정 트리, 앙상블 

## 학습 진행 과정

### LogisticRegression (Optuna로 최적화)
<img width="510" alt="스크린샷 2025-03-20 오후 5 05 47" src="https://github.com/user-attachments/assets/09736f0a-14de-4018-a1f4-337084e65c7f" />

### XGBoost (Optuna로 최적화)
<img width="516" alt="스크린샷 2025-03-20 오후 5 09 52" src="https://github.com/user-attachments/assets/31dfe9b9-ff44-4163-b482-a08869181077" />
<img width="564" alt="스크린샷 2025-03-20 오후 5 11 47" src="https://github.com/user-attachments/assets/d3ffa0da-8175-46e3-85fc-53adc86d61f7" />
<img width="773" alt="image" src="https://github.com/user-attachments/assets/0d10f346-4a7a-4540-919e-0d6dd2457c20" />


### Ensemble (LogisticRegression + RandomForest + XGBoost + CatBoost)
<img width="514" alt="스크린샷 2025-03-20 오후 5 16 16" src="https://github.com/user-attachments/assets/273bc223-be0a-4316-9a6c-047460ebadfb" />

### LightGBM

#### score
<img width="382" alt="image" src="https://github.com/user-attachments/assets/8ec01ce1-db4c-4bb8-9136-41faf9edf8a2" />

#### Confusion Matrix
<img width="385" alt="image" src="https://github.com/user-attachments/assets/cf631a76-e0b7-4c4c-a8bb-8fb72aeb5f0d" />

#### ROC curve
<img width="452" alt="image" src="https://github.com/user-attachments/assets/42130023-27cb-4c7e-a2b5-fbbae0690b0c" />

#### Precision-Recall Curve
<img width="453" alt="image" src="https://github.com/user-attachments/assets/9d4fc6ac-9333-4060-a8f1-71fcb06a8ca0" />

#### feature importance
<img width="691" alt="image" src="https://github.com/user-attachments/assets/ecbcd4de-c0b0-4e5c-acd0-ab43152d475d" />

#### Logloss
<img width="520" alt="image" src="https://github.com/user-attachments/assets/441b5038-46a8-404b-9c11-0460256ff1ea" />


-
