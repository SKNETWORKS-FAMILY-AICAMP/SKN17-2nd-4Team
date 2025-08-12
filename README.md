# 🟦 SK네트웍스 Family AI 캠프 17기 2차 프로젝트_ 4Team 🟦


#  1. 팀 소개
### ▶️ 팀명 :  **공공삼**

#### '공공삼'은 00년생 3명과 03년생 1명이 하나가 되어 팀을 이루었다는 뜻과 세 가지 '공'인 공유, 공감, 공조를 핵심가치로 조화로운 팀을 이루겠다는 의미를 담았습니다. 

<br>

### ▶️ 팀원 소개 
|[김주영](https://github.com/samkim7788)|[전상아](https://github.com/sang-a-le)|[조해리](https://github.com/Haer111)|[최우진](https://github.com/CHUH00)|
|:---|:---|:---|:---|
|<img width="100" height="100" src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN17-2nd-4Team/blob/main/image/%EB%B8%8C%EB%A0%88%EB%93%9C.png" />|<img width="100" height="100" src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN17-2nd-4Team/blob/main/image/%EB%B0%80%ED%81%AC.png" />|<img width="100" height="100" src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN17-2nd-4Team/blob/main/image/%EC%B4%88%EC%BD%94.png" />|<img width="100" height="100" src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN17-2nd-4Team/blob/main/image/%EA%B0%90%EC%9E%90%EC%B9%A9.png" />|

<br>

-----

# 2. 프로젝트 개요

### ▶️ 프로젝트 명 

### **🏃‍♀️‍➡️떠날까? 말까?🏃‍♀️**
#### SNS 사용자 데이터를 기반으로 '페이스북' 이탈 가능성 예측 모델 및 예측 서비스 제공

<br>

-----

### ▶️ 프로젝트 소개 
해당 프로젝트는 SNS 사용자 데이터를 기반으로 개인 특성을 분석하여 향후 플랫폼 이탈 가능성 예측한다. 
특히, 페이스북을 1순위로 선택한 사용자를 기반으로 페이스북 사용자 이탈 모델을 학습해 향후 사용자 특성 데이터를 기반으로 잠재적 이탈자 판별 서비스 제공을 목표로 한다. 

<br>

-----

### ▶️ 프로젝트 배경
<br>

<img width="551" height="210" alt="image" src="https://github.com/user-attachments/assets/3954c807-02cf-4edb-ab48-04ec4bec4a9d" />

> https://www.chosun.com/economy/tech_it/2023/03/10/NEL65GJO2ZGUXJHVGNCAC4Y354/


> 국내 페이스북 월 이용자가 처음으로 1000만명 이하로 떨어졌다. 사진이나 짧은 동영상 위주의 소셜미디어를 선호하는 10·20대 이용자의 이탈이 가속화하고 있기 때문으로 풀이된다.

> 조선일보, 변희원, 2023.03.10


위의 기사 내용과 같이 2023년 국내 페이스북 월 이용자가 처음으로 1000만명 이하로 떨어지는 등 페이스북 사용자가 지속적으로 감소하는 양상을 보이고 있습니다. 

<br>
<br>

<img width="500" height="300" src='https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN17-2nd-4Team/blob/main/image/%ED%8E%98%EC%9D%B4%EC%8A%A4%EB%B6%81%20%EC%9D%B4%EC%9A%A9%20%EA%B7%B8%EB%9E%98%ED%94%84%201.jpg'>

> https://www.i-boss.co.kr/ab-6141-59928

> 출처 : 오픈서베이 소셜미디어·검색포털 트렌드 리포트 2023

위의 그래프는 2023년 발표된 오픈서베이의 소셜미디어·검색포털 트렌드 리포트에서 발표된 그래프이다. 
최근 일주일 내 사용한 소셜네트워크 시스템 순위 중 페이스북이 22.6%로 7위를 기록하는 등 동일한 리포트에서 2019년 3위를 기록했던 것에 비해 많이 떨어진 순위를 보이고 있습니다.

<br>
<br>

<img width="600" height="450" alt="image" src="https://github.com/user-attachments/assets/13150251-0be3-43a7-96bd-6e85accadd69" />

> https://www.wiseapp.co.kr/insight/detail/517

> 출처 : 2024. 와이즈앱·리테일 '희비 엇갈린 SNS 앱 인스타그램 vs 페이스북 비교'

<br>
<br>

|<img width="600" height="300" alt="image" src="https://github.com/user-attachments/assets/639bc8a7-162e-41fd-b1b6-89720eb2fd2c" />|<img width="600" height="300" alt="image" src="https://github.com/user-attachments/assets/86dc6a9c-85ed-4db8-a7c7-95c873108c5d" />|
|:---|:---|
| 페이스북 앱 사용자 및 사용시간 추이 | 인스타그램, 페이스북 앱 월간 사용자 추이 |

<br>

위의 그래프둘에서 확인된 바와 같이 페이스북의 사용 추이가 지속적으로 감소되고 있습니다. 

#### 현재 2030 세대의 경우, 학창시절 페이스북을 가장 주된 SNS로 사용했던 세대이기도 하지만 페이스북 이탈률이 가장 많은 세대라는 것을 확인할 수 있습니다. 

#### 과거 많은 파급력을 주었던 페이스북의 사용자 감소에 대한 의문이 해당 프로젝트 주제 선정에 영향을 주었고, 이에 따라 저희는 SNS 사용자의 개인 특성 데이터를 기반으로 페이스북 이탈률 예측을 하고자 합니다. 

<br>
<br>

-----

### ▶️ 프로젝트 목표 
#### 1. 사용자 특성 데이터를 이용한 페이스북 사용자 이탈률 파악
#### 2. 실제 데이터 주입 시 이탈률 예측
#### 3. 페이스북 외의 다른 SNS의 이탈률 파악으로 인사이트 확장


<br>
<br>

-----

### ▶️ 수집데이터 설명
[미디어통계포털 미디어패널조사]
- 출처 : 미디어 통계 포털(https://stat.kisdi.re.kr/)
- 수집 방법 : 미디어 통계 포털에서 제공하는 연도별 한국 미디어 패널 조사 데이터셋 csv 파일 다운로드.
- 데이터 출처 및 범위
    - 수집 데이터 기간: 2019년 1월 ~ 2024년 12월
    - 데이터 범위 : 개인 정보 및 미디어 이용 중 SNS 사용 관련 질문 
    - 주요 변수 : SNS 사용 빈도, 개인정보(나이, 성별, 학력, 결혼 여부, 종교, 수입 등), 사용하는 SNS 종류
- 설명 
    : 미디어 통계 포털에서 이루어진 한국 미디어 패널 조사 데이터셋을 분석하여 고객의 다양한 특성(나이, 성별, 학력, 결혼 여부, 종교, 수입 등)과 SNS 사용 빈도 관련 설문 데이터에 따른 페이스북 이탈 가능성을 예측

<br>
<br>

-----

# 3. 기술 스택
|개발도구|협업도구|프로그래밍 언어|데이터 전처리|데이터 시각화|머신러닝|
|---|---|---|---|---|---|
|vscode|Github|Python|Pandas / numpy|Matplotlib|scikit learn|
| <img src='https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white'>|<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">|<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">|<img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white"> <img src='https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white'>|<img src='https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black'>| <img src="https://img.shields.io/badge/Scikit-learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>|

<br>
<br>

-----

# 4. WBS
![WBS이미지](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN17-2nd-4Team/blob/main/image/WBS.png)

<br>
<br>

-----

# 5. 데이터 전처리 결과서 (EDA)

## 👉 최종 데이터 (19년도 /24년도, 2개년 비교)
### 🔹 1. 데이터 로드 
```python
df = pd.read_csv('./data/p19v31_KMP_csv.csv', encoding='CP949')

feature = ['pid', 'p19age', 'p19gender', 'p19school', 'p19mar', 'p19job1', 'p19job2', 'p19job4', 'p19income', 'p19relig2', 'p19d27001', 'p19d27002', 'p19d27003', 'p19d27004', 'p19d11002', 'p19d11004', 'p19d11006']

df_19 = df[feature].copy()

df_19.rename(
    columns={
        'p19age': 'age', 
        'p19gender': 'gender', 
        'p19school': 'school', 
        'p19mar': 'mar', 
        'p19job1': 'job', 
        'p19job2': 'job_o',
        'p19job4': 'job_x',
        'p19income': 'income', 
        'p19relig2': 'relig',
        'p19d27001': 'd01', 
        'p19d27002': 'd02', 
        'p19d27003': 'd03', 
        'p19d27004': 'd04',
        'p19d11002': 'label_1',
        'p19d11004': 'label_2', 
        'p19d11006': 'label_3'
    }, inplace=True
)

df_19['year'] = 2019

df_19.head()
```
<img width="1303" height="193" alt="image" src="https://github.com/user-attachments/assets/990f4250-728e-48b5-bf49-b33ab7db3424" />

<br>
<br>

### 🔹 2. 변수 변환
#### * 유/무직자 컬럼 병합 및 정제
```python
# 유직자 번호 변경
df_all['job_o'] = df_all['job_o'].replace({'1': '5', '2': '6', '3': '7', '4': '2', '9999': '8'})
print(df_all['job_o'].value_counts())
```

<br>

#### * 데이터 맵핑
  - 데이터 사용 빈도에 대해 맵핑
  
  |<img width="238" height="176" alt="image" src="https://github.com/user-attachments/assets/8cecaa34-7fbf-4067-a515-5eb51792f206" /> | <img width="238" height="176" alt="image" src="https://github.com/user-attachments/assets/e1f9bf73-ceb4-403b-9005-fef9ad932e19" />|
  |---|---|
  |기존값|맵핑 후|

<br>

#### * 라벨데이터 재생성
```python
# 라벨 기초 데이터 변환 (3순위 포함)
df_24['label'] = (df_24[['label_1', 'label_2', 'label_3']].isin(['2']).any(axis=1).astype(int))
print(sum(df_24['label'] == 1), sum(df_24['label'] == 0))

# label의 다음 연도 값
df_all['next_year_label'] = df_all.groupby('pid')['label'].shift(-1)
df_all

# 라벨 데이터 생성 = 이탈(churn) 여부 정의 
churn_conditions = [
    (df_all['label'] == 1) & (df_all['next_year_label'].notna()) & (df_all['next_year_label'] != 1),
    (df_all['label'] == 1) & (df_all['next_year_label'].notna()) & (df_all['next_year_label'] == 1)
]
churn_choices = [1, 0] # 1: 이탈 (Churn), 0: 비이탈 (Not Churn)

df_all['churn'] = np.select(churn_conditions, churn_choices, default=np.nan)
```

<br>

#### * 결측치 제거
```python
df_all = df_all[df_all['label'].str.strip() != ''].reset_index(drop=True)
```

<br>

#### * 이탈(churn) 변수 정의
```python
df_all['next_year_label'] = df_all.groupby('pid')['label'].shift(-1) # 각 pid 그룹에 대한 다음 연도의 label 값 반환

churn_conditions = [
    (df_all['label'] == '2') & (df_all['next_year_label'].notna()) & (df_all['next_year_label'] != '2'),
    (df_all['label'] == '2') & (df_all['next_year_label'].notna()) & (df_all['next_year_label'] == '2')
]
churn_choices = [1, 0] # 1: 이탈 (Churn), 0: 비이탈 (Not Churn)

df_all['churn'] = np.select(churn_conditions, churn_choices, default=np.nan)
```

<br>

#### * 필터링
```python
df_model_base = df_all[df_all['churn'].notna()].copy() # 'churn'값이 NaN이 아닌 경우 필터링
```

<br>
  
#### * 2개년 기초 데이터 
<img width="500" height="198" alt="image" src="https://github.com/user-attachments/assets/d8c182a7-6868-40a7-adc0-f6da4f0a2ce4" />

<br>
<br>

#### * 24년도 변수 변경 내용 컬럼 추가
<img width="1540" height="198" alt="image" src="https://github.com/user-attachments/assets/5b23701e-db7c-4bb6-a163-677e97b8e6be" />

→ 총 31개 피처, 1712개 로우 수 생성

<br>
<br>

### 🔹3. EDA

#### * 파생 변수 추가
```python
# 2. 변화량(차이) 파생변수 생성
df_final['d01_change'] = df_final['d01_y'] - df_final['d01_x']
df_final['d02_change'] = df_final['d02_y'] - df_final['d02_x']
df_final['d03_change'] = df_final['d03_y'] - df_final['d03_x']
df_final['d04_change'] = df_final['d04_y'] - df_final['d04_x']
df_final['income_change'] = df_final['income_y'] - df_final['income_x']
df_final['job_change'] = (df_final['job_y'] != df_final['job_x']).astype(int)  # 직업 변동 여부
```
<br>

#### * 변수별 상관계수 
<img width="600" height="550" alt="image" src="https://github.com/user-attachments/assets/723d36c7-57d0-4725-97d8-5fb8a5d00063" />

<br>

### → 모델 성능 추출 간 변화 내용 없음. 파생변수 미사용.

<br>
<br>

#### * 중요도 추출
<img width="500" height="600" alt="image" src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN17-2nd-4Team/blob/main/image/%EC%A4%91%EC%9A%94%EB%8F%84.png" />

 
<br>
<br>

-----

# 6. 인공지능 학습 결과서 
### 🔹1. 최초 학습 - XGBclassifier
```python
# X, y 준비
df = df_final.copy()
df.drop(columns=["pid", "label_x", "label_y", "year_x", "year_y", "gender_y"], inplace=True)

X = df.drop(columns=["churn"])
y = df["churn"]

# 범주형 라벨 인코딩
X_encoded = X.copy()
for col in X_encoded.select_dtypes(include="object").columns:
    le = LabelEncoder()
    X_encoded[col] = le.fit_transform(X_encoded[col].astype(str))

X_train, X_test, y_train, y_test = train_test_split(
    X_encoded, y, test_size=0.2, random_state=42, stratify=y
)

model = XGBClassifier(
    n_estimators=50,
    max_depth=2,
    learning_rate=0.1,
    random_state=42,
    eval_metric='logloss'
)
# 모델 학습
model.fit(X_train, y_train)

# 예측 및 평가
y_train_pred = model.predict(X_train)
y_train_prob = model.predict_proba(X_train)[:, 1]
y_test_pred = model.predict(X_test)
y_test_prob = model.predict_proba(X_test)[:, 1]
```
<img width="320" height="320" alt="image" src="https://github.com/user-attachments/assets/ca5404b3-9353-4c15-9c61-c39e694fa421" />

<br>
<br>

### 🔹2. RandomForest
```python
# 파라미터 후보
param_grid = {
    'n_estimators': [100, 200, 300],
    'max_depth': [4, 6, 8, None],
    'min_samples_split': [2, 5, 8, 10],
    'min_samples_leaf': [1, 2, 3, 4],
    'max_features': ['sqrt', 0.5, None],
    'class_weight': [None, 'balanced']
}

# 모델 생성
rf = RandomForestClassifier(random_state=42)

# GridSearchCV 설정
grid_search = GridSearchCV(
    estimator=rf,
    param_grid=param_grid,
    scoring='f1',
    cv=5,
    n_jobs=-1,
    verbose=2
)

# 학습
grid_search.fit(X_train, y_train)

# 최적 파라미터 & 교차검증 성능
print("Best Parameters:", grid_search.best_params_)
print("Best CV F1 Score:", grid_search.best_score_)

# 최적 모델
best_rf = grid_search.best_estimator_

# 과적합 확인
train_acc = best_rf.score(X_train, y_train)
test_acc = best_rf.score(X_test, y_test)
print(f"Train Accuracy: {train_acc:.4f}")
print(f"Test Accuracy : {test_acc:.4f}")
print(f"Overfitting Gap: {train_acc - test_acc:.4f}")

# 분류 리포트
y_pred = best_rf.predict(X_test)
print(classification_report(y_test, y_pred))
```
<img width="1423" height="339" alt="image" src="https://github.com/user-attachments/assets/d13bbada-8a07-4335-9207-22402418dc9e" />

<br>
<br>

### 🔹3. HistGradientBoost
```python
smote = SMOTE(random_state=42)
X_resample, y_resample = smote.fit_resample(X, y)

X_encoded = X_resample.copy()
for col in X_encoded.select_dtypes(include='object').columns:
    le = LabelEncoder()
    X_encoded[col] = le.fit_transform(X_encoded[col].astype(str))

X_train, X_test, y_train, y_test = train_test_split(X_encoded, y_resample, random_state=42)

param_grid = {
    'max_iter': [100],
    'max_depth': [5],
    'learning_rate': [0.3],
    'l2_regularization': [10],
    'max_bins': [225]
}

model = HistGradientBoostingClassifier(random_state=42)

grid_search = GridSearchCV(model, param_grid, cv=5, scoring='roc_auc')

grid_search.fit(X_train, y_train)
grid_search.best_params_

best_hist_gb_clf = grid_search.best_estimator_

y_pred_train = best_hist_gb_clf.predict(X_train)
y_prob_train = best_hist_gb_clf.predict_proba(X_train)[:, 1]

y_pred_test = best_hist_gb_clf.predict(X_test)
y_prob_test = best_hist_gb_clf.predict_proba(X_test)[:, 1]
```
<img width="320" height="320" alt="image" src="https://github.com/user-attachments/assets/cbfee80e-f39a-4e1e-aa23-6da47be5010c" />

<br>
<br>

### 🔹4. GradientBoost
```python
# 파라미터 최적화
param_grid = {
    'n_estimators': [100, 300, 500],      # 트리 개수
    'learning_rate': [0.1, 0.05, 0.01],   # 작을수록 성능 ↑, 대신 트리 수 필요
    'max_depth': [3, 5, 7],               # 개별 트리 최대 깊이
    'min_samples_split': [2, 5, 10],      # 노드 분할 최소 샘플 수
    'min_samples_leaf': [1, 3, 5],        # 리프 노드 최소 샘플 수
    'subsample': [0.8, 1.0],              # 샘플링 비율
    'max_features': ['sqrt', 'log2', None]# 특성 샘플링
}

model = GradientBoostingClassifier(random_state=42)

grid_search = GridSearchCV(model, param_grid, cv=5, scoring='roc_auc')

grid_search.fit(X_train, y_train)
grid_search.best_params_

best_hist_gb_clf = grid_search.best_estimator_

y_pred_train = best_hist_gb_clf.predict(X_train)
y_prob_train = best_hist_gb_clf.predict_proba(X_train)[:, 1]

y_pred_test = best_hist_gb_clf.predict(X_test)
y_prob_test = best_hist_gb_clf.predict_proba(X_test)[:, 1]

print("\n===== XGBoost - Train Set Evaluation =====")
print(classification_report(y_train, y_pred_train))
print(f'{roc_auc_score(y_train, y_prob_train):.4f}')

print("\n===== XGBoost - Test Set Evaluation =====")
print(classification_report(y_test, y_pred_test))
print(f'{roc_auc_score(y_test, y_prob_test):.4f}')
```
<img width="320" height="320" alt="image" src="https://github.com/user-attachments/assets/fe912a84-7533-4966-b2b0-4d163918bfb8" />


<br>
<br>

### 🔹5. 최종 : XGBooat - 규제 
```python
X = df_final.drop(['churn'], axis=1)
y = df_final['churn']

smote = SMOTE(random_state=42)
X_resample, y_resample = smote.fit_resample(X, y)

X_encoded = X_resample.copy()
for col in X_encoded.select_dtypes(include='object').columns:
    le = LabelEncoder()
    X_encoded[col] = le.fit_transform(X_encoded[col].astype(str))

X_train, X_test, y_train, y_test = train_test_split(X_encoded, y_resample, random_state=42)

param_grid = {
    'n_estimators': [100, 200, 300],
    'learning_rate': [0.01, 0.07, 0.1],
    'max_depth': [3, 5, 10],
    'min_child_weight': [0.01, 0.05, 0.1],
    'subsample': [0.1, 0.5, 0.8],
    'colsample_bytree': [1.0],
    'reg_lambda': [10],
    'reg_alpha': [0],
    'gamma': [0, 1]
}

model = XGBClassifier(random_state=42)

grid_search = GridSearchCV(model, param_grid, cv=5, scoring='roc_auc')

grid_search.fit(X_train, y_train)
grid_search.best_params_
```
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/d9b46fda-b1ba-4d91-aa1d-66ac98c79f3f" />

<br>

```python
best_xgb_clf = grid_search.best_estimator_

y_pred_train = best_xgb_clf.predict(X_train)
y_prob_train = best_xgb_clf.predict_proba(X_train)[:, 1]

y_pred_test = best_xgb_clf.predict(X_test)
y_prob_test = best_xgb_clf.predict_proba(X_test)[:, 1]
```
<img width="320" height="320" alt="image" src="https://github.com/user-attachments/assets/dd6c2090-319f-4c99-a61d-3b7e04d63950" />


<br>
<br>

-----

# 7. 수행결과


<br>
<br>

-----

# 8. 한 줄 회고
|이름|내용|
|:---:|:---|
|김주영| |
|전상아| |
|조해리|설문조사 데이터여서 데이터를 파악하는 것부터가 정말 힘들었고, 전처리 과정에서도 시행착오가 많았다. 특히 모델 성능이 어떻게 돌려도 63%에서 오르지 않아 어려움을 겪었지만, 전처리 과정에서의 실수를 발견하고 수정했을 때 성능이 확실히 개선되는 경험을 했다. 이를 통해 데이터 분석에서 전처리의 중요성을 크게 느낄 수 있었다.|
|최우진| |
