# 🖼️ 이미지 설정 가이드

## ⚠️ 중요: Netlify 배포 전 이미지 추가 필수

현재 웹사이트의 이미지들이 표시되지 않는 이유는 이미지 파일이 프로젝트에 포함되지 않았기 때문입니다.

## 📋 해결 방법

### 1단계: images 폴더 생성
프로젝트 폴더에 `images` 폴더를 만듭니다.

```
프로젝트 폴더/
├── index.html
├── css/
│   └── style.css
└── images/          ← 이 폴더를 만드세요
```

### 2단계: 이미지 파일 추가
원본 이미지 파일들을 아래 이름으로 `images/` 폴더에 저장하세요:

#### 성인 치료 사례 (8개)
- `adult-face-before.jpg` - 얼굴 치료 전
- `adult-face-after.jpg` - 얼굴 치료 후
- `adult-chest-before.jpg` - 상체 치료 전
- `adult-chest-after.jpg` - 상체 치료 후
- `adult-leg-before.jpg` - 하체 치료 전
- `adult-leg-after.jpg` - 하체 치료 후
- `adult-knee-before.jpg` - 무릎 치료 전
- `adult-knee-after.jpg` - 무릎 치료 후

#### 어린이 치료 사례 (6개)
- `child-arm-before.jpg` - 팔 치료 전
- `child-arm-after.jpg` - 팔 치료 후
- `child-knee-before.jpg` - 무릎 치료 전
- `child-knee-after.jpg` - 무릎 치료 후
- `child-elbow-before.jpg` - 팔꿈치 치료 전
- `child-elbow-after.jpg` - 팔꿈치 치료 후

#### 감사 메시지 (5개)
- `testimonial-message.jpg` - 완치 감사 문자
- `followup-email1.jpg` - 감사 이메일 1
- `followup-email2.jpg` - 감사 이메일 2
- `followup-email3.jpg` - 감사 이메일 3
- `followup-email4.jpg` - 감사 이메일 4

### 3단계: 파일 구조 확인
모든 파일을 추가한 후 폴더 구조가 다음과 같아야 합니다:

```
프로젝트 폴더/
├── index.html
├── css/
│   └── style.css
├── images/
│   ├── adult-face-before.jpg
│   ├── adult-face-after.jpg
│   ├── adult-chest-before.jpg
│   ├── adult-chest-after.jpg
│   ├── adult-leg-before.jpg
│   ├── adult-leg-after.jpg
│   ├── adult-knee-before.jpg
│   ├── adult-knee-after.jpg
│   ├── child-arm-before.jpg
│   ├── child-arm-after.jpg
│   ├── child-knee-before.jpg
│   ├── child-knee-after.jpg
│   ├── child-elbow-before.jpg
│   ├── child-elbow-after.jpg
│   ├── testimonial-message.jpg
│   ├── followup-email1.jpg
│   ├── followup-email2.jpg
│   ├── followup-email3.jpg
│   └── followup-email4.jpg
└── README.md
```

### 4단계: GitHub 업로드
1. GitHub 저장소에 **모든 파일을 함께** 업로드합니다
2. 특히 `images/` 폴더의 모든 이미지가 포함되어야 합니다

### 5단계: Netlify 배포
1. Netlify에서 GitHub 저장소를 연결합니다
2. 자동으로 배포됩니다
3. 이미지가 정상적으로 표시됩니다! ✅

## 💡 팁

### 로컬에서 먼저 테스트하기
1. 이미지를 모두 추가한 후
2. `index.html` 파일을 더블클릭하여 브라우저에서 엽니다
3. 이미지가 모두 보이는지 확인합니다
4. 문제없으면 GitHub/Netlify에 업로드합니다

### 이미지 파일명 주의사항
- 정확한 파일명을 사용하세요 (대소문자 구분)
- JPG 형식이어야 합니다
- 파일명에 공백이나 특수문자를 사용하지 마세요

## ❓ 문제 해결

### 이미지가 여전히 안 보인다면:
1. `images/` 폴더가 올바른 위치에 있는지 확인
2. 파일명이 정확한지 확인 (철자, 대소문자)
3. 모든 이미지 파일이 업로드되었는지 확인
4. 브라우저 캐시를 지우고 새로고침

### GitHub에 업로드 시:
- `images/` 폴더를 반드시 포함하세요
- Git에서 이미지 파일이 무시되지 않았는지 확인하세요
- `.gitignore` 파일이 있다면 이미지를 제외하지 않는지 확인하세요

## ✅ 완료!
모든 단계를 완료하면 Netlify에서 이미지가 정상적으로 표시됩니다!