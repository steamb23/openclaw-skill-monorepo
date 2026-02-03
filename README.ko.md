# [OpenClaw](https://github.com/openclaw/openclaw) 스킬 모노레포

이 저장소는 개인적인 용도로 사용하기 위한 스킬의 공유 및 개선을 위해 만들어진 OpenClaw 스킬 모노레포입니다.

대부분의 문서와 코드들은 바이브 코딩과 약간의 손코딩으로 조정하여 작성되었습니다.

## 스킬

현재는 한국에서만 사용 가능한 스킬이 많습니다.

- **[kma-weather](kma-weather/SKILL.md)**: 기상청에서 날씨 정보를 가져옵니다.

- **[naver-news](naver-news/SKILL.md)**: 네이버 검색 API를 사용하여 한국 뉴스 기사를 검색합니다.

## 권장 환경

호스트와 샌드박스 환경 모두 스킬을 사용할 수 있습니다.
단, 샌드박스 환경에서 스킬을 사용하도록 설정하려면 [OpenClaw 저장소](https://github.com/openclaw/openclaw)를 클론하고 도커 이미지를 빌드해야합니다.

스크립트 실행 환경과 패키지 관리자가 모두 설치된 [openclaw-sandbox-common](https://github.com/openclaw/openclaw/blob/main/scripts/sandbox-common-setup.sh) 이미지 사용을 권장합니다.

자세한 설명은 [공식 가이드](https://docs.openclaw.ai/gateway/sandboxing#images-+-setup)를 확인해주세요.