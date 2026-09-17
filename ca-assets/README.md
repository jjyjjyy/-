# CA asset 관리 방법

`index.html`을 고치지 말고 이 폴더의 파일만 수정하면 됩니다.
파일 이름의 `ca1`~`ca5`는 사이트에 나오는 CA 순서입니다.

## 기본 규칙

한국어와 영어를 같은 파일에 씁니다.

```txt
한국어 내용
English content
```

예를 들어 `ca2_name.txt`는 이렇게 씁니다.

```txt
강지형
Jihyeong Kang
```

## CA별로 수정하는 파일

아래 파일들은 모두 1줄 한국어, 2줄 영어 형식입니다.

| 내용 | 파일 예시 |
| --- | --- |
| CA 이름 | `ca1_name.txt` |
| 대표 유형 이름 | `ca1_title.txt` |
| 결과 한 줄 설명 | `ca1_one_line.txt` |
| 결과 설명문 | `ca1_description.txt` |
| 전공 | `ca1_major.txt` |
| 관심사 | `ca1_interest.txt` |
| MBTI | `ca1_mbti.txt` |

다른 CA는 숫자만 바꾸면 됩니다. 예: 두 번째 CA는 `ca2_name.txt`, `ca2_major.txt`를 수정합니다.

## 한 언어만 준비된 경우

영어가 아직 없으면 2번째 줄에 임시 문구를 적어 주세요.

```txt
전산학부
To be added
```

## 한 줄만 쓰는 파일

아래 파일들은 한국어/영어를 나누지 않고 한 줄만 씁니다.

| 내용 | 파일 |
| --- | --- |
| 결과 아이콘 | `ca1_icon.txt` |
| 개인 상담 링크 | `ca1_link.txt` |
| CA 단체방 링크 | `ca_chat_link.txt` |
| 피자파티 수요조사 링크 | `pizza_party_link.txt` |

링크 파일에는 URL 한 줄만 넣어 주세요. 예: `https://open.kakao.com/o/example`
아이콘 파일에는 이모지 하나만 넣는 것을 권장합니다. 예: `🎨`

## 사진

사진은 JPG와 PNG 모두 가능합니다. 파일 이름은 아래 중 하나로 맞춰 주세요.

- `ca1_photo.jpg`
- `ca1_photo.png`
- `ca1_photo.jpeg`
- `ca1_photo.webp`

다른 CA는 숫자만 바꾸면 됩니다. 예: `ca2_photo.png`.
여러 확장자가 동시에 있으면 사이트는 `jpg → png → jpeg → webp` 순서로 먼저 찾은 사진을 씁니다.

## 주의
- 파일명을 바꾸면 사이트가 읽지 못합니다. 내용만 바꿔 주세요.
- 각 내용은 가능하면 한 줄로 써 주세요.
- MBTI를 공개하지 않을 경우 `비공개` / `Private`처럼 적으면 됩니다.