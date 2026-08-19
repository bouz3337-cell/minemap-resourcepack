# Minemap 리소스팩

마인크래프트 Paper 플러그인 **Minemap** 의 미니맵 HUD 용 리소스팩입니다.
미니맵은 커스텀 폰트로 그리기 때문에 이 팩이 없으면 화면에 네모 상자만 보입니다.

## 다운로드 주소

```
https://raw.githubusercontent.com/bouz3337-cell/minemap-resourcepack/main/Minemap-ResourcePack.zip
```

## 서버 설정

`plugins/Minemap/config.yml`

```yaml
resource-pack:
  url: "https://raw.githubusercontent.com/bouz3337-cell/minemap-resourcepack/main/Minemap-ResourcePack.zip"
  sha1: ""
```

`sha1` 을 비워두면 플러그인이 자기가 만든 팩의 해시를 자동으로 씁니다.

## 내용물

| 파일 | 용도 |
|---|---|
| `assets/minemap/font/pixel.json` | 지도 픽셀 글리프 (행마다 ascent 가 다른 32개) + 가로 이동용 space |
| `assets/minemap/textures/font/px.png` | 픽셀 글리프 텍스처 |
| `assets/minecraft/.../boss_bar/white_*.png` | WHITE 보스바만 투명 처리 (다른 보스바는 그대로) |

이 파일들은 플러그인이 직접 생성합니다. 손으로 고치지 마세요 —
플러그인 안의 글자 배정과 어긋나면 화면이 통째로 깨집니다.
