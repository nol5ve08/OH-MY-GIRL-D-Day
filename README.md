# Miracle Calendar

오마이걸 멤버 생일과 발매일을 보여주는 정적 캘린더 사이트입니다.

## 파일 구조

- `index.html`: 사이트 화면과 동작
- `events.json`: 생일/발매일 데이터

## 일정 추가 방법

DB를 붙이기 전에는 `events.json`에 항목을 추가하면 됩니다.

```json
{
  "id": "unique-event-id",
  "date": "2024-08-26",
  "type": "release",
  "title": "Dreamy Resonance 발매",
  "short": "Dreamy",
  "source": "1회 수집: 음반 발매일"
}
```

`type`은 현재 `birthday` 또는 `release`를 사용합니다.

## 배포

GitHub Pages나 Railway의 정적 사이트 배포로 올릴 수 있습니다. 배포 루트는 이 폴더입니다.
