# Leewonjin-25.github.io
# 🐍 파이썬 기초 퀴즈

앞서 학습한 5개의 샘플 코드를 기반으로 한 퀴즈입니다. 각 문제를 풀어보고 정답을 확인하세요!

---

## 퀴즈 1: 변수와 데이터 타입

**다음 코드의 출력 결과는?**

```python
name = '파이썬'
version = 3.12
print(type(name), type(version))
```

**선택지:**
1. `<class 'str'> <class 'int'>`
2. `<class 'str'> <class 'float'>`
3. `<class 'string'> <class 'float'>`
4. `<class 'text'> <class 'number'>`

<details>
<summary>정답 보기</summary>

**정답: 2번**

`name`은 문자열(str), `version`은 실수(float)입니다. 3.12는 소수점이 있어 float 타입입니다.

</details>

---

## 퀴즈 2: 리스트 인덱싱

**다음 코드의 출력 결과는?**

```python
fruits = ['사과', '바나나', '오렌지', '포도']
print(fruits[-2])
```

**선택지:**
1. 바나나
2. 오렌지
3. 포도
4. 에러 발생

<details>
<summary>정답 보기</summary>

**정답: 2번 (오렌지)**

음수 인덱스는 뒤에서부터 세며, `-1`이 마지막, `-2`가 뒤에서 두 번째입니다.

</details>

---

## 퀴즈 3: 조건문

**다음 코드의 출력 결과는?**

```python
score = 85
if score >= 90:
    print('A')
elif score >= 80:
    print('B')
else:
    print('C')
```

**선택지:**
1. A
2. B
3. C
4. 아무것도 출력 안됨

<details>
<summary>정답 보기</summary>

**정답: 2번 (B)**

`score`는 85이므로 두 번째 조건(`>= 80`)을 만족하여 'B'가 출력됩니다.

</details>

---

## 퀴즈 4: for 반복문

**다음 코드의 출력 결과는?**

```python
total = 0
for i in range(1, 5):
    total += i
print(total)
```

**선택지:**
1. 10
2. 15
3. 5
4. 0

<details>
<summary>정답 보기</summary>

**정답: 1번 (10)**

`range(1, 5)`는 1, 2, 3, 4를 생성하고, 합은 1+2+3+4 = 10입니다.

</details>

---

## 퀴즈 5: 함수 반환값

**다음 코드의 출력 결과는?**

```python
def multiply(a, b):
    return a * b

result = multiply(3, 4)
print(result)
```

**선택지:**
1. 7
2. 12
3. 34
4. None

<details>
<summary>정답 보기</summary>

**정답: 2번 (12)**

`multiply` 함수는 두 수를 곱한 값을 반환합니다. 3 × 4 = 12입니다.

</details>

---

## 퀴즈 6: 리스트 메서드

**다음 코드 실행 후 `numbers`의 값은?**

```python
numbers = [1, 2, 3]
numbers.append(4)
numbers.insert(0, 0)
print(numbers)
```

**선택지:**
1. `[1, 2, 3, 4, 0]`
2. `[0, 1, 2, 3, 4]`
3. `[1, 2, 3, 4]`
4. `[0, 1, 2, 3]`

<details>
<summary>정답 보기</summary>

**정답: 2번 (`[0, 1, 2, 3, 4]`)**

`append(4)`로 끝에 4를 추가하고, `insert(0, 0)`으로 맨 앞(인덱스 0)에 0을 삽입합니다.

</details>

---

## 퀴즈 7: 딕셔너리

**다음 코드의 출력 결과는?**

```python
student = {'이름': '김철수', '나이': 20}
print(student['이름'])
```

**선택지:**
1. 김철수
2. '김철수'
3. 이름
4. 에러 발생

<details>
<summary>정답 보기</summary>

**정답: 1번 (김철수)**

딕셔너리에서 키로 값을 조회하면 해당 값이 출력됩니다. `student['이름']`은 키 '이름'에 해당하는 값 '김철수'를 반환합니다.

</details>

---

## 퀴즈 8: while 반복문과 break

**다음 코드의 출력 결과는?**

```python
count = 0
while True:
    count += 1
    if count == 3:
        break
print(count)
```

**선택지:**
1. 1
2. 2
3. 3
4. 무한 루프

<details>
<summary>정답 보기</summary>

**정답: 3번 (3)**

`count`가 3이 되는 순간 `break`가 실행되어 반복문을 종료하고 3이 출력됩니다.

</details>

---

## 퀴즈 9: 리스트 슬라이싱

**다음 코드의 출력 결과는?**

```python
numbers = [10, 20, 30, 40, 50]
print(numbers[1:4])
```

**선택지:**
1. `[10, 20, 30]`
2. `[20, 30, 40]`
3. `[20, 30, 40, 50]`
4. `[10, 20, 30, 40]`

<details>
<summary>정답 보기</summary>

**정답: 2번 (`[20, 30, 40]`)**

슬라이싱 `[1:4]`는 인덱스 1부터 3까지(4는 미포함)를 의미합니다. 인덱스 1, 2, 3의 항목을 포함합니다.

</details>

---

## 퀴즈 10: 함수 기본 매개변수

**다음 코드의 출력 결과는?**

```python
def greet(name, msg='안녕하세요'):
    return f'{msg}, {name}님!'

print(greet('홍길동'))
```

**선택지:**
1. 안녕하세요, 홍길동님!
2. 홍길동님!
3. 안녕하세요
4. 에러 발생

<details>
<summary>정답 보기</summary>

**정답: 1번 (안녕하세요, 홍길동님!)**

`msg` 매개변수에 값을 전달하지 않으면 기본값 '안녕하세요'가 사용됩니다.

</details>

---

## 📊 점수 계산

정답 개수를 세어보세요!

- **10개**: 🏆 완벽합니다! 파이썬 기초를 완전히 마스터했습니다!
- **8-9개**: 🌟 훌륭합니다! 파이썬 기초를 잘 이해하고 있습니다!
- **6-7개**: 👍 좋습니다! 조금만 더 복습하면 완벽해질 거예요!
- **4-5개**: 📚 괜찮습니다! 샘플 코드를 다시 한 번 복습해보세요!
- **0-3개**: 💪 화이팅! 샘플 코드를 천천히 다시 학습해보세요!

## 📚 복습 자료

틀린 문제가 있다면 해당 샘플 코드를 다시 확인해보세요:

- [01_variables_and_data_types.py](file:///c:/Users/USER/Desktop/01_variables_and_data_types.py) - 변수와 데이터 타입
- [02_conditional_statements.py](file:///c:/Users/USER/Desktop/02_conditional_statements.py) - 조건문
- [03_loops.py](file:///c:/Users/USER/Desktop/03_loops.py) - 반복문
- [04_functions.py](file:///c:/Users/USER/Desktop/04_functions.py) - 함수
- [05_list_operations.py](file:///c:/Users/USER/Desktop/05_list_operations.py) - 리스트 조작

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🛣️ 도로의 분류 퀴즈</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            max-width: 800px;
            width: 100%;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            overflow: hidden;
        }

        .header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 40px;
            text-align: center;
        }

        .header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        .header p {
            font-size: 1.1em;
            opacity: 0.9;
        }

        .quiz-content {
            padding: 40px;
        }

        .question-card {
            background: #f8f9fa;
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .question-card:hover {
            transform: translateY(-5px);
        }

        .question-number {
            display: inline-block;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 8px 16px;
            border-radius: 20px;
            font-weight: bold;
            margin-bottom: 15px;
            font-size: 0.9em;
        }

        .question-text {
            font-size: 1.3em;
            font-weight: 600;
            color: #2c3e50;
            margin-bottom: 20px;
            line-height: 1.5;
        }

        .options {
            display: flex;
            flex-direction: column;
            gap: 12px;
        }

        .option {
            background: white;
            border: 2px solid #e0e0e0;
            border-radius: 10px;
            padding: 15px 20px;
            cursor: pointer;
            transition: all 0.3s ease;
            font-size: 1.1em;
            display: flex;
            align-items: center;
        }

        .option:hover {
            border-color: #667eea;
            background: #f0f4ff;
            transform: translateX(5px);
        }

        .option.selected {
            border-color: #667eea;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            font-weight: 600;
        }

        .option.correct {
            border-color: #27ae60;
            background: #d4edda;
            color: #155724;
        }

        .option.incorrect {
            border-color: #e74c3c;
            background: #f8d7da;
            color: #721c24;
        }

        .option.disabled {
            cursor: not-allowed;
            opacity: 0.6;
        }

        .explanation {
            margin-top: 20px;
            padding: 20px;
            background: #e8f4f8;
            border-left: 4px solid #667eea;
            border-radius: 8px;
            display: none;
        }

        .explanation.show {
            display: block;
            animation: fadeIn 0.5s ease;
        }

        .explanation h4 {
            color: #667eea;
            margin-bottom: 10px;
            font-size: 1.1em;
        }

        .explanation p {
            color: #2c3e50;
            line-height: 1.6;
        }

        .explanation ul {
            margin-top: 10px;
            padding-left: 20px;
        }

        .explanation li {
            margin: 5px 0;
            color: #34495e;
        }

        .score-container {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 30px;
            text-align: center;
            border-radius: 15px;
            margin-top: 30px;
            display: none;
        }

        .score-container.show {
            display: block;
            animation: fadeIn 0.5s ease;
        }

        .score-container h2 {
            font-size: 2em;
            margin-bottom: 15px;
        }

        .score-number {
            font-size: 4em;
            font-weight: bold;
            margin: 20px 0;
        }

        .score-message {
            font-size: 1.3em;
            margin-top: 15px;
        }

        .submit-btn {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            padding: 15px 40px;
            font-size: 1.2em;
            border-radius: 10px;
            cursor: pointer;
            margin-top: 20px;
            transition: all 0.3s ease;
            font-weight: 600;
        }

        .submit-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(102, 126, 234, 0.4);
        }

        .submit-btn:disabled {
            opacity: 0.5;
            cursor: not-allowed;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(10px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .reset-btn {
            background: white;
            color: #667eea;
            border: 2px solid white;
            padding: 12px 30px;
            font-size: 1.1em;
            border-radius: 10px;
            cursor: pointer;
            margin-top: 20px;
            transition: all 0.3s ease;
            font-weight: 600;
        }

        .reset-btn:hover {
            background: #f0f4ff;
            transform: translateY(-2px);
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🛣️ 도로의 분류 퀴즈</h1>
            <p>도로의 종류와 분류 기준에 대한 퀴즈입니다</p>
        </div>

        <div class="quiz-content">
            <!-- 퀴즈 1 -->
            <div class="question-card">
                <span class="question-number">퀴즈 1</span>
                <div class="question-text">도로법에 따른 도로의 분류가 아닌 것은?</div>
                <div class="options">
                    <div class="option" data-question="1" data-answer="1">1. 고속국도</div>
                    <div class="option" data-question="1" data-answer="2">2. 일반국도</div>
                    <div class="option" data-question="1" data-answer="3">3. 특별시도·광역시도</div>
                    <div class="option" data-question="1" data-answer="4">4. 농어촌도로</div>
                </div>
                <div class="explanation" data-question="1">
                    <h4>✅ 정답: 4번 (농어촌도로)</h4>
                    <p>도로법상 도로는 다음과 같이 분류됩니다:</p>
                    <ul>
                        <li><strong>고속국도</strong>: 자동차 전용 고속도로</li>
                        <li><strong>일반국도</strong>: 주요 도시를 연결하는 도로</li>
                        <li><strong>특별시도·광역시도</strong>: 특별시 또는 광역시 관할 도로</li>
                        <li><strong>지방도</strong>: 지방 지역을 연결하는 도로</li>
                        <li><strong>시도, 군도, 구도</strong>: 각 지방자치단체 관할 도로</li>
                    </ul>
                    <p>농어촌도로는 별도의 법률(농어촌도로 정비법)에 따른 분류입니다.</p>
                </div>
            </div>

            <!-- 퀴즈 2 -->
            <div class="question-card">
                <span class="question-number">퀴즈 2</span>
                <div class="question-text">도로를 기능에 따라 분류할 때, 주로 장거리 통과 교통을 처리하며 접근 제한이 있는 도로는?</div>
                <div class="options">
                    <div class="option" data-question="2" data-answer="1">1. 집산도로</div>
                    <div class="option" data-question="2" data-answer="2">2. 국지도로</div>
                    <div class="option" data-question="2" data-answer="3">3. 주간선도로</div>
                    <div class="option" data-question="2" data-answer="4">4. 보조간선도로</div>
                </div>
                <div class="explanation" data-question="2">
                    <h4>✅ 정답: 3번 (주간선도로)</h4>
                    <p>도로의 기능별 분류:</p>
                    <ul>
                        <li><strong>주간선도로</strong>: 도시 내 주요 지역 간 연결, 장거리 통과 교통 처리, 접근 제한</li>
                        <li><strong>보조간선도로</strong>: 주간선도로를 보조하며 중거리 교통 처리</li>
                        <li><strong>집산도로</strong>: 근린 주거 지역의 교통을 간선도로로 연결</li>
                        <li><strong>국지도로</strong>: 주거 지역 내부의 교통을 처리, 접근 기능 중심</li>
                    </ul>
                </div>
            </div>

            <!-- 퀴즈 3 -->
            <div class="question-card">
                <span class="question-number">퀴즈 3</span>
                <div class="question-text">고속국도(고속도로)에 대한 설명으로 옳지 않은 것은?</div>
                <div class="options">
                    <div class="option" data-question="3" data-answer="1">1. 자동차 전용 도로이다</div>
                    <div class="option" data-question="3" data-answer="2">2. 신호등이 설치되어 있지 않다</div>
                    <div class="option" data-question="3" data-answer="3">3. 보행자와 자전거의 통행이 금지된다</div>
                    <div class="option" data-question="3" data-answer="4">4. 최저 속도 제한이 없다</div>
                </div>
                <div class="explanation" data-question="3">
                    <h4>✅ 정답: 4번 (최저 속도 제한이 없다)</h4>
                    <p>고속국도의 특징:</p>
                    <ul>
                        <li>✅ 자동차 전용 도로 (이륜차, 보행자, 자전거 통행 금지)</li>
                        <li>✅ 신호등 없음 (입체 교차로만 사용)</li>
                        <li>✅ 접근 제한 (인터체인지를 통해서만 진입 가능)</li>
                        <li>✅ <strong>최저 속도 제한 있음</strong> (일반적으로 50km/h)</li>
                        <li>✅ 최고 속도 제한 (일반적으로 100-120km/h)</li>
                    </ul>
                </div>
            </div>

            <!-- 퀴즈 4 -->
            <div class="question-card">
                <span class="question-number">퀴즈 4</span>
                <div class="question-text">다음 중 도로를 구조에 따라 분류한 것으로 올바른 것은?</div>
                <div class="options">
                    <div class="option" data-question="4" data-answer="1">1. 평면도로, 입체도로</div>
                    <div class="option" data-question="4" data-answer="2">2. 국도, 지방도</div>
                    <div class="option" data-question="4" data-answer="3">3. 간선도로, 집산도로</div>
                    <div class="option" data-question="4" data-answer="4">4. 포장도로, 비포장도로</div>
                </div>
                <div class="explanation" data-question="4">
                    <h4>✅ 정답: 1번 (평면도로, 입체도로)</h4>
                    <p>도로의 구조별 분류:</p>
                    <ul>
                        <li><strong>평면도로</strong>: 교차로가 평면 교차하는 일반적인 도로</li>
                        <li><strong>입체도로</strong>: 교차로가 입체 교차하는 도로 (고가도로, 지하도로, 고속도로 등)</li>
                    </ul>
                    <p>참고:</p>
                    <ul>
                        <li>2번은 관리 주체에 따른 분류</li>
                        <li>3번은 기능에 따른 분류</li>
                        <li>4번은 포장 상태에 따른 분류</li>
                    </ul>
                </div>
            </div>

            <!-- 퀴즈 5 -->
            <div class="question-card">
                <span class="question-number">퀴즈 5</span>
                <div class="question-text">도로교통법상 '좁은 도로'로 분류되는 기준은?</div>
                <div class="options">
                    <div class="option" data-question="5" data-answer="1">1. 폭 4m 미만</div>
                    <div class="option" data-question="5" data-answer="2">2. 폭 6m 미만</div>
                    <div class="option" data-question="5" data-answer="3">3. 폭 8m 미만</div>
                    <div class="option" data-question="5" data-answer="4">4. 폭 10m 미만</div>
                </div>
                <div class="explanation" data-question="5">
                    <h4>✅ 정답: 2번 (폭 6m 미만)</h4>
                    <p>도로 폭에 따른 분류:</p>
                    <ul>
                        <li><strong>광로(廣路)</strong>: 폭 25m 이상</li>
                        <li><strong>대로(大路)</strong>: 폭 12m 이상 25m 미만</li>
                        <li><strong>중로(中路)</strong>: 폭 8m 이상 12m 미만</li>
                        <li><strong>소로(小路)</strong>: 폭 8m 미만</li>
                        <li><strong>좁은 도로</strong>: 폭 6m 미만 (도로교통법상 특별 규정 적용)</li>
                    </ul>
                </div>
            </div>

            <div style="text-align: center;">
                <button class="submit-btn" id="submitBtn">결과 확인하기</button>
            </div>

            <div class="score-container" id="scoreContainer">
                <h2>🎉 퀴즈 완료!</h2>
                <div class="score-number" id="scoreNumber">0/5</div>
                <div class="score-message" id="scoreMessage"></div>
                <button class="reset-btn" onclick="location.reload()">다시 풀기</button>
            </div>
        </div>
    </div>

    <script>
        const correctAnswers = {
            1: 4,
            2: 3,
            3: 4,
            4: 1,
            5: 2
        };

        let userAnswers = {};

        // 옵션 클릭 이벤트
        document.querySelectorAll('.option').forEach(option => {
            option.addEventListener('click', function() {
                const questionNum = this.dataset.question;
                const answerNum = parseInt(this.dataset.answer);
                
                // 같은 질문의 다른 옵션들 선택 해제
                document.querySelectorAll(`.option[data-question="${questionNum}"]`).forEach(opt => {
                    opt.classList.remove('selected');
                });
                
                // 현재 옵션 선택
                this.classList.add('selected');
                userAnswers[questionNum] = answerNum;
                
                // 모든 문제를 풀었는지 확인
                if (Object.keys(userAnswers).length === 5) {
                    document.getElementById('submitBtn').disabled = false;
                }
            });
        });

        // 결과 확인 버튼
        document.getElementById('submitBtn').addEventListener('click', function() {
            let score = 0;
            
            // 각 문제 채점
            for (let q = 1; q <= 5; q++) {
                const userAnswer = userAnswers[q];
                const correctAnswer = correctAnswers[q];
                
                // 모든 옵션 비활성화
                document.querySelectorAll(`.option[data-question="${q}"]`).forEach(opt => {
                    opt.classList.add('disabled');
                    const answerNum = parseInt(opt.dataset.answer);
                    
                    if (answerNum === correctAnswer) {
                        opt.classList.add('correct');
                    } else if (answerNum === userAnswer && userAnswer !== correctAnswer) {
                        opt.classList.add('incorrect');
                    }
                });
                
                // 정답 확인
                if (userAnswer === correctAnswer) {
                    score++;
                }
                
                // 해설 표시
                document.querySelector(`.explanation[data-question="${q}"]`).classList.add('show');
            }
            
            // 점수 표시
            document.getElementById('scoreNumber').textContent = `${score}/5`;
            
            // 메시지 설정
            let message = '';
            if (score === 5) {
                message = '🏆 완벽합니다! 도로 분류에 대해 잘 알고 계십니다!';
            } else if (score === 4) {
                message = '🌟 훌륭합니다! 도로 체계를 잘 이해하고 있습니다!';
            } else if (score === 3) {
                message = '👍 좋습니다! 조금만 더 공부하면 완벽해질 거예요!';
            } else if (score === 2) {
                message = '📚 괜찮습니다! 도로 관련 법규를 복습해보세요!';
            } else {
                message = '💪 화이팅! 도로법과 도로교통법을 학습해보세요!';
            }
            
            document.getElementById('scoreMessage').textContent = message;
            document.getElementById('scoreContainer').classList.add('show');
            
            // 버튼 숨기기
            this.style.display = 'none';
            
            // 점수 컨테이너로 스크롤
            document.getElementById('scoreContainer').scrollIntoView({ behavior: 'smooth', block: 'center' });
        });

        // 초기 상태에서 제출 버튼 비활성화
        document.getElementById('submitBtn').disabled = true;
    </script>
</body>
</html>
