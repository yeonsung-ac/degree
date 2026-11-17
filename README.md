# DEGREE

학생 작품 전시관. GitHub Pages의 main 브랜치 루트에서 제공됩니다.

- 전시관 입장: 0909 (브라우저 화면 입장 장치, 저장소 비공개 기능 아님)
- 클래스/기수/학생: data.json. 새 클래스를 classes에 추가하면 상단 전시실 구획이 자동 생성됩니다.
- order는 학번 순 정렬 번호입니다. 공개 파일에는 학번 원문을 넣지 않습니다.
- 기본 이미지: assets/consumer/*.webp. 메인페이지가 없는 경우 assets/upload-placeholder.svg.
- 학생 수정: 본인 카드의 썸네일 수정 → 개인 수정코드 → 이미지 업로드. 800×500 JPEG로 압축하여 Firebase에 저장합니다. 코드가 확인된 카드만 수정됩니다.
- 교수 관리: dasahee@yeonsung.ac.kr Google 계정. 수정코드 조회 및 최초 등록 지원.
- Firebase 규칙: backend/degree.rules는 기존 규칙 안에 추가한 전시관 전용 부분입니다. 기존 프로젝트 전체 규칙을 이 파일로 대체하지 마세요.
- 코드 파일과 학생별 학번 원본은 공개 저장소에 포함하지 않습니다.
