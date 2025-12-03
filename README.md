# 황박사의 지혜로운 건강교실 - 치료 사례 랜딩페이지

## 프로젝트 개요
황박사의 지혜로운 건강교실 유튜브 광고용 랜딩페이지입니다. 아토피 치료 전후 비교 사진을 통해 치료 효과를 시각적으로 보여주는 웹페이지입니다.

## 주요 기능

### ✅ 완료된 기능
1. **성인 치료 사례**
   - 얼굴 치료 전후 비교
   - 상체(가슴/목) 치료 전후 비교
   - 하체(다리) 치료 전후 비교
   - 무릎 치료 전후 비교

2. **어린이 치료 사례**
   - 팔 치료 전후 비교
   - 무릎 뒤 치료 전후 비교
   - 팔꿈치 치료 전후 비교
   - 완치 감사 문자 표시

3. **치료 후 근황**
   - 북경에서 치료받은 분의 건강한 근황
   - 감사 이메일 4건 표시

4. **디자인 특징**
   - 현대적이고 깔끔한 그라데이션 디자인
   - 치료 전/후 명확한 시각적 구분
   - 화살표로 변화 과정 직관적 표시
   - 반응형 디자인 (모바일 최적화)
   - 친근하고 따뜻한 색상 사용

5. **상담 정보**
   - 상담 시간: 10:00 - 18:00
   - 상담 전화: 031-439-6557
   - 헤더와 푸터에 연락처 정보 표시

## 기술 스택
- HTML5
- CSS3 (그라데이션, Flexbox, Grid)
- Google Fonts (Noto Sans KR)
- 반응형 웹 디자인

## 페이지 구조

```
index.html              # 메인 페이지
css/
  └── style.css         # 스타일시트
images/                 # 이미지 폴더 (19개 치료 사례 이미지)
  ├── adult-face-before.jpg
  ├── adult-face-after.jpg
  ├── adult-chest-before.jpg
  ├── adult-chest-after.jpg
  ├── adult-leg-before.jpg
  ├── adult-leg-after.jpg
  ├── adult-knee-before.jpg
  ├── adult-knee-after.jpg
  ├── child-arm-before.jpg
  ├── child-arm-after.jpg
  ├── child-knee-before.jpg
  ├── child-knee-after.jpg
  ├── child-elbow-before.jpg
  ├── child-elbow-after.jpg
  ├── testimonial-message.jpg
  ├── followup-email1.jpg
  ├── followup-email2.jpg
  ├── followup-email3.jpg
  └── followup-email4.jpg
README.md               # 프로젝트 문서
```

## 접근 경로
- **메인 페이지**: `/index.html` 또는 `/`

## 디자인 특징

### 색상 팔레트
- **헤더/푸터**: 보라색 그라데이션 (#667eea → #764ba2)
- **치료 전 라벨**: 분홍-레드 그라데이션 (#f093fb → #f5576c)
- **치료 후 라벨**: 블루-시안 그라데이션 (#4facfe → #00f2fe)
- **감사 문자 박스**: 오렌지-피치 그라데이션 (#ffecd2 → #fcb69f)
- **후속 섹션**: 라이트 블루 그라데이션 (#e0f7fa → #b2ebf2)

### 레이아웃
- 최대 너비: 1200px
- 반응형 브레이크포인트: 768px, 480px
- 그리드/Flexbox 기반 레이아웃

## 반응형 지원
- 데스크톱 (1200px+)
- 태블릿 (768px ~ 1199px)
- 모바일 (~ 767px)

## 향후 개선 사항
- [ ] 치료 과정 상세 설명 추가
- [ ] 온라인 상담 문의 폼 추가
- [ ] 치료 후기 더 많은 사례 추가
- [ ] 애니메이션 효과 추가 (스크롤 애니메이션)
- [ ] FAQ 섹션 추가
- [ ] 치료 절차 안내 섹션

## 배포 방법

### GitHub + Netlify 배포
1. **프로젝트 다운로드**: 이 프로젝트를 다운로드하여 압축을 풉니다
2. **GitHub 업로드**: 
   - GitHub 저장소를 생성합니다
   - 모든 파일(index.html, css/, images/)을 업로드합니다
3. **Netlify 배포**:
   - Netlify에 로그인합니다
   - "New site from Git" 선택
   - GitHub 저장소를 연결합니다
   - 배포 완료!

### 로컬 테스트
1. 웹브라우저에서 `index.html` 파일을 엽니다.
2. 페이지를 스크롤하여 치료 사례를 확인합니다.
3. 상담이 필요한 경우 푸터의 전화번호로 연락합니다.

### ⚠️ 중요 사항
- **모든 이미지 파일이 포함되어 있습니다**: images/ 폴더의 모든 파일을 함께 업로드해야 합니다
- **상대 경로 사용**: 이미지는 `images/` 폴더에서 불러옵니다
- Netlify 배포 시 이미지가 정상적으로 표시됩니다

## 브라우저 호환성
- Chrome (최신 버전)
- Firefox (최신 버전)
- Safari (최신 버전)
- Edge (최신 버전)
- 모바일 브라우저 (iOS Safari, Chrome)

## 라이선스
황박사의 지혜로운 건강교실 전용

---

**제작일**: 2025년 12월
**목적**: 유튜브 광고용 랜딩페이지
**연락처**: 031-439-6557