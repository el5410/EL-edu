# 🌟 EL 영어학원 (Eternal Life) 웹앱

> 김해 EL 영어학원의 학생 관리 + 학부모 안내 + 선생님 대시보드 통합 웹앱

📱 **연락처**: 010-3006-5410  
📍 **위치**: 김해시  
🕐 **운영**: 평일 14:00 ~ 20:00

---

## 📁 페이지 구성

### 🎓 [학생 페이지](./el_student_dashboard_v7.html)
- 학원 PC에서 사용 (가로 3컬럼)
- 진도 입력, 학습 단계 체크, 단어 시험
- 🎫 숙제 적립 통장 (면제권 시스템)
- 📌 어제 진도 확인

### 👨‍🏫 [선생님 메인 대시보드](./el_teacher_dashboard_v2.html)
- 시간대별 학생 관리 (14:00~20:00)
- **카드 보기 / 줄 보기 토글** (한 타임 10명도 OK)
- 빠른 출석/과제 점검
- 학생 이름 클릭 → 상세 패널

### 📊 [학생 상세 페이지](./el_student_detail_v1.html)
- 선생님이 학생별로 관리하는 페이지
- ORT/다독/단어/문법 단계 관리
- 시간표 + 보강 일정
- 면제권 +/- 조절
- 학원 정보 수정 (학부모 페이지 연동)

### 👨‍👩‍👧 [학부모 페이지](./el_parent_view_v1.html)
- 자녀의 학습 현황 조회
- 성장 그래프 (주/월/3개월)
- 영역별 점수 (W/P/Q)
- 숙제 캘린더 + 상세 모달
- 선생님께 메시지 보내기

---

## 🎨 디자인 시스템

| 컬러 | 코드 | 용도 |
|------|------|------|
| 🩵 청록 (메인) | `#14b8a6` | 학원 메인 컬러 |
| 💜 보라 | `#8b5cf6` | 퍼즐 점수, 강조 |
| 🧡 주황 | `#fb923c` | 다독, 포인트 |
| 💙 파랑 | `#3b82f6` | 단어 점수 |
| 💚 초록 | `#22c55e` | 퀴즈 점수, 완료 |
| 💗 핑크 | `#ec4899` | 면제권 |

**폰트**: Plus Jakarta Sans + Noto Sans KR  
**디자인 톤**: Duolingo + Notion + ClassDojo

---

## 🎫 면제권 시스템

```
숙제 ○ 20개 적립 → 면제권 1장 자동 발급
                ↓
          카운트 0부터 다시 시작
                ↓
        🎁 면제권 사용 시
                ↓
    당일 숙제 없음 + 다음 시간 "면제" 자동 처리
```

---

## 📚 ORT 레벨별 학습 단계

| 레벨 | 단계 |
|------|------|
| **ORT1~2** | W·T·C·P·📓·D·S·Q·📔·C (퀴즈까지) |
| **ORT3** | + L 라이팅 ✏️ |
| **ORT4~9** | + L 라이팅 + R ORT 리뷰 🔁 |

---

## 🚀 사용 방법

### 학원 PC에서
1. 학생 페이지: `el_student_dashboard_v7.html`
2. 선생님 대시보드: `el_teacher_dashboard_v2.html`

### 모바일/태블릿에서
1. 학부모 페이지: `el_parent_view_v1.html`

### GitHub Pages로 배포 시
```
https://[본인아이디].github.io/EL-edu/el_student_dashboard_v7.html
https://[본인아이디].github.io/EL-edu/el_teacher_dashboard_v2.html
https://[본인아이디].github.io/EL-edu/el_parent_view_v1.html
```

---

## 🛠️ 기술 스택

- **프론트엔드**: HTML + CSS + Vanilla JavaScript
- **백엔드**: Google Sheets + Google Apps Script (예정)
- **호스팅**: GitHub Pages (예정)
- **외부 연동**:
  - [리드앤톡](https://www.readandtalk.co.kr/elp_login.php)
  - [클래스카드](https://www.classcard.net/Login)

---

## 📝 라이선스

학원 내부 사용 전용

---

## 📞 문의

- 📱 010-3006-5410
- 💬 카카오톡 @EL영어학원

---

✨ Made with 💛 for EL 영어학원
