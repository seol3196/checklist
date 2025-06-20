# 다 했어요! - 학급 체크리스트 관리 시스템

## 📝 프로젝트 소개
"다 했어요!"는 교사들이 학급 학생들의 과제나 활동 완료 상태를 쉽게 관리할 수 있는 웹 기반 체크리스트 시스템입니다.

## ✨ 주요 기능
- **교사 로그인 시스템**
  - 교사별 데이터 분리 관리
  - 자동 로그인 지원

- **학생 관리**
  - CSV 파일을 통한 학생 정보 일괄 등록
  - 학생별 번호와 이름 관리

- **체크리스트 관리**
  - 과목별 체크리스트 생성
  - 실시간 상태 업데이트
  - 완료 순위 표시

- **상태 관리**
  - 미완료
  - 완료
  - 진행중
  - 재제출
  - 미제출마감

- **통계 기능**
  - 상태별 통계 표시
  - 완료 순위 표시
  - 실시간 진행률 표시

- **다크모드 지원**
  - 라이트/다크 테마 전환
  - 자동 테마 저장

## 🛠️ 기술 스택
- Frontend: HTML, CSS (Tailwind CSS), JavaScript
- Backend: Supabase
- 데이터베이스: PostgreSQL (Supabase)

## 🚀 시작하기

### 1. 저장소 클론
```bash
git clone https://github.com/seol3196/checklist.git
```

### 2. Supabase 설정
1. [Supabase](https://supabase.com) 계정 생성
2. 새 프로젝트 생성
3. 다음 테이블 생성:
   - `teachers`: 교사 정보
   - `students`: 학생 정보
   - `checklists`: 체크리스트 정보

### 3. 환경 설정
1. `index.html` 파일의 Supabase 설정 업데이트:
```javascript
const SUPABASE_CONFIG = {
    URL: 'YOUR_SUPABASE_URL',
    ANON_KEY: 'YOUR_SUPABASE_ANON_KEY'
};
```

## 📋 사용 방법

### 교사 로그인
1. 교사 아이디로 로그인
2. 자동 로그인 지원

### 학생 관리
1. "학생 추가" 버튼 클릭
2. CSV 양식 다운로드
3. 학생 정보 입력 후 업로드

### 체크리스트 생성
1. 과목 선택
2. 체크리스트 생성
3. 학생별 상태 관리

## 🔒 보안
- 교사별 데이터 분리
- Supabase 보안 규칙 설정
- 로컬 스토리지 암호화

## 📱 반응형 디자인
- 모바일/태블릿/데스크톱 지원
- 최적화된 UI/UX

## 🤝 기여하기
1. Fork the Project
2. Create your Feature Branch
3. Commit your Changes
4. Push to the Branch
5. Open a Pull Request

## 📄 라이선스
이 프로젝트는 MIT 라이선스를 따릅니다.

## 👥 개발자
- [seol3196](https://github.com/seol3196)

## 📞 문의
- GitHub Issues를 통해 문의해주세요.
