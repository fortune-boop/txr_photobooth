# Texas Roadhouse Christmas Photo Booth

## 📁 파일 구조

```
/
├── index.html          ← 포토부스 메인 파일
└── frames/             ← 프레임 PNG 이미지 폴더 (직접 추가 필요)
    ├── appetizer_roll.png      (에피타이저 - 디너롤 프레임)
    ├── appetizer_peanut.png    (에피타이저 - 땅콩 프레임)
    ├── appetizer_steak.png     (에피타이저 - 립아이 스테이크 프레임)
    ├── appetizer_potato.png    (에피타이저 - 베이크드 포테이토 프레임)
    ├── xmas_rope.png           (텍사스 크리스마스 - 로프 프레임)
    ├── xmas_merry.png          (텍사스 크리스마스 - Merry TX 프레임)
    ├── xmas_longhorn.png       (텍사스 크리스마스 - 롱혼 프레임)
    ├── xmas_truck.png          (텍사스 크리스마스 - 트럭 프레임)
    ├── andy_santa.png          (앤디 - 산타 프레임)
    ├── andy_texas.png          (앤디 - 텍사스 프레임)
    └── andy_cozy.png           (앤디 - 코지 프레임)
```

## 🖼️ 프레임 이미지 제작 가이드

- **권장 크기**: 1080 × 1920px (9:16 세로)
- **포맷**: PNG (투명 배경 필수 — 구멍 뚫린 부분이 투명이어야 카메라가 보임)
- **주의**: 사진이 들어갈 영역은 반드시 투명(alpha=0)으로 제작

## 🚀 GitHub Pages 배포 방법

1. GitHub에서 새 레포지토리 생성 (Public)
2. `index.html` 업로드
3. `frames/` 폴더 생성 후 PNG 파일들 업로드
4. Settings → Pages → Branch: main 설정
5. QR 코드 생성 → 매장 배치
