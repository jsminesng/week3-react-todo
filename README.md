# Week 3 과제: React Todo 앱

## 프로젝트 개요
이 프로젝트는 Vanilla JavaScript로 만든 Todo 앱을 React로 업그레이드한 버전입니다.  
React의 useState, useEffect, 그리고 컴포넌트 구조를 직접 사용하여  
명령형(Imperative) → 선언형(Declarative) 개발 방식의 차이를 체험하는 것을 목표로 합니다.

---

## 주요 기능
| 기능 | 설명 |
|------|------|
| 할일 추가 | 입력 후 '추가' 버튼 또는 Enter 키로 할일 추가 |
| 완료 토글 | 체크박스를 눌러 완료 상태 변경 |
| 삭제 | 각 할일 오른쪽의 '삭제' 버튼으로 제거 |
| 자동 저장 | LocalStorage와 연동되어 새로고침해도 데이터 유지 |
| 통계 표시 | 전체 / 완료 / 남은 할일 개수 실시간 표시 |
| 반응형 디자인 | Tailwind CSS를 이용한 반응형 UI (모바일, 데스크탑 모두 지원) |
| 한글 입력 안정화 | e.isComposing / keyCode 229 처리로 IME(한글 조합) 버그 방지 |

---

## 사용 기술
- React 18 (CDN 방식)
- Tailwind CSS
- LocalStorage
- HTML5 + Babel (JSX 변환용)

---

## 실행 방법

### 1. 다운로드 또는 복제
```bash
git clone https://github.com/jsminesng/week3-react-todo.git
cd week3-react-todo
