# 수퍼 하이드라이드 한국어 패치

메가드라이브 일본판 《수퍼 하이드라이드》(Super Hydlide)용 비공식 한국어 패치입니다. 현재 배포 버전은 **v1.0.0**입니다.

## 다운로드

**[패치 다운로드](https://github.com/kilk96/super-hydlide-korean-patch/releases/tag/v1.0.0)**에서 **`super-hydlide-ko-v1.0.0.zip`**을 받아 압축을 풀어 주세요. 페이지 아래쪽 **Assets**(첨부 파일)에서 찾을 수 있습니다.

`Source code` 압축 파일은 받지 않으셔도 됩니다. 원본 게임 파일과 패치 적용이 끝난 게임 파일은 제공하지 않습니다. 이 저장소가 비공개인 동안에는 접근 권한이 있는 계정으로 로그인해야 내려받을 수 있습니다.

## 적용 방법

1. 직접 보유하신 일본판 원본을 백업하고, 아래 **지원 원본과 파일 확인**의 크기·SHA-256을 확인해 주세요.
2. xdelta **3.2 이상**을 지원하는 패치 프로그램에서 원본 파일과 `super-hydlide-ko-v1.0.0.xdelta`를 선택해 주세요. xdelta는 원본과 바뀐 부분만 담은 패치 형식입니다.
3. 결과를 원본과 다른 이름의 `.md` 또는 `.bin` 파일로 저장하고 아래 결과 SHA-256과 비교해 주세요. 결과 파일은 1MB로 늘어나는 것이 정상입니다.
4. 결과 파일을 메가드라이브 에뮬레이터에서 실행해 주세요. 자세한 명령은 ZIP 안의 `README.md`에 있습니다.

## 한글판 화면

![오프닝 첫 장면](https://github.com/kilk96/super-hydlide-korean-patch/releases/download/v1.0.0/v1.0.0-01-opening.png)

![오프닝 그림 장면](https://github.com/kilk96/super-hydlide-korean-patch/releases/download/v1.0.0/v1.0.0-02-opening-scene.png)

![한글 이름 입력](https://github.com/kilk96/super-hydlide-korean-patch/releases/download/v1.0.0/v1.0.0-03-name-entry.png)

![마을 사람과의 대화](https://github.com/kilk96/super-hydlide-korean-patch/releases/download/v1.0.0/v1.0.0-04-dialogue.png)

![상태창](https://github.com/kilk96/super-hydlide-korean-patch/releases/download/v1.0.0/v1.0.0-05-status.png)

## 번역·확인 범위

- 대사, 오프닝, 엔딩, 메뉴, 상태창, 아이템·장비·마법 이름, 상점·여관·은행 문구를 한국어로 옮겼습니다.
- 대화창 위의 `会話中` 그림 글자를 `대화 중`으로 다시 그렸습니다.
- 캐릭터 이름은 현대 한글 전체와 영문·숫자를 조합해 최대 8글자까지 입력할 수 있습니다.
- 타이틀 로고, 화면 오른쪽의 영문 표시(`Life`, `Day`, `Time` 등), 사운드 테스트 곡명은 원본 그대로입니다.
- 진행 보조 기능을 사용해 시작부터 엔딩까지 플레이하며 진행 불가·표시 이상이 없는지 확인했습니다. 그 뒤의 작은 수정 중 아이템 이름 3개와 상태 칸 정렬은 자동 화면 대조로, 보물 상자 문구는 실제 플레이 화면으로 확인했습니다.

## 실행과 저장

확인한 환경은 **BizHawk 2.11.1(Genesis Plus GX 코어)**입니다. 이 패치는 게임 파일에 저장 메모리 정보를 추가하므로 여관에서 한 게임 내 저장이 기록됩니다. 일본판으로 만든 저장 파일과의 호환은 보장하지 않으므로 새 게임을 권장합니다. 에뮬레이터 순간 저장(세이브스테이트)은 패치 버전이 바뀌면 호환되지 않을 수 있습니다.

## 알려진 제한

- 아이템 이름 뒤에 받침에 맞는 조사를 고를 수 없어 보물 상자 문구는 `보물 상자 안은, 단검이다`처럼 표현했습니다. 일부 엔딩 문장은 실제 플레이 화면 재확인이 남아 있습니다.
- 새 한글 글자가 처음 나오는 창은 원본보다 아주 잠깐(약 0.1~0.2초) 늦게 그려질 수 있습니다. 상태창·필드 메뉴는 원본 수준으로 맞췄고, 다른 창의 속도는 원본과 비교 측정하지 않았습니다.
- 실제 기기와 다른 에뮬레이터는 확인하지 못했습니다.

## 지원 원본과 파일 확인

| 항목 | 값 |
|---|---|
| 기종·판본 | 메가드라이브, Super Hydlide (Japan) |
| 원본 형식 | 헤더 없는 일반 형식(`.md`/`.bin`) |
| 원본 크기 | 524,288바이트 |
| 원본 SHA-256 | `30749097096807abf67cd1f7b2392f5789f5149ee33661e6d13113396f06a121` |
| 결과 크기 | 1,048,576바이트 |
| 결과 SHA-256 | `7974f056c3e69f87e37b2a4b6b795a0b23a6abb55844fb4f80b4a2cffc63b0c6` |

SHA-256은 파일 내용이 같은지 확인하는 값입니다. 파일명보다 크기와 이 값이 일치하는지 확인해 주세요.

Windows PowerShell에서 다음 명령의 파일명을 바꾸어 원본과 결과를 각각 확인하실 수 있습니다.

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath '확인할파일.md'
```

## 문제 제보

[Issues에 제보해 주세요](https://github.com/kilk96/super-hydlide-korean-patch/issues). 패치 버전, 에뮬레이터 이름·버전, 발생 장소와 직전 조작, 문제 화면을 함께 적어 주시면 도움이 됩니다. 원본·패치 적용 완료 게임 파일은 첨부하지 말아 주세요.

## 권리와 글꼴

원작사와 관계없는 팬 번역이며, 게임의 권리는 각 권리자에게 있습니다. 한글 글꼴은 달무리 글꼴(Apache License 2.0), `대화 중` 그림 글자는 갈무리 글꼴(SIL Open Font License 1.1)을 게임용 비트맵으로 변환해 사용했습니다. 출처와 라이선스 전문은 ZIP 안의 `FONT-NOTICE.txt`, `LICENSE-dalmoori.txt`, `LICENSE-Galmuri.txt`에 있습니다.
