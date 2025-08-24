# VIDEO Asset Pack Template

이 템플릿은 히어로 배경을 **영상**으로 쓰기 위한 폴더 구조/스니펫을 제공합니다.
파일만 이 구조에 맞춰 넣어서 ZIP으로 업로드하면, 제가 index에 즉시 반영해 드립니다.

## 폴더 구조
assets/
  videos/
    hero/            ← hero-1080.webm, hero-1080.mp4 등 영상 파일
  images/
    hero/            ← 포스터(정지 이미지) scene-1600.jpg
    projects/        ← 포트폴리오 썸네일
    logos/           ← 협력사 로고

snippets/
  hero-video.html    ← index에 넣을 영상 히어로 코드 조각

config/
  videos.csv         ← 영상/포스터 파일명 설정(선택)

## 권장 파일 이름
- WebM: hero-1080.webm (VP9), 선택으로 hero-1440.webm/hero-720.webm 추가 가능
- MP4 : hero-1080.mp4  (H.264)
- 포스터: scene-1600.jpg (또는 .webp)

## 권장 규격
- 해상도: 1920×1080 (16:9) 또는 1920×820 (21:9)
- 길이: 6–12초 루프
- 용량: 데스크톱 6–12MB, 모바일 2–5MB
- 옵션: autoplay, muted, loop, playsinline, preload="metadata"

업로드가 끝나면 ZIP만 전달해 주세요. index에 반영해 드립니다.