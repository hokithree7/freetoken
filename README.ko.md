# FreeToken.link — 무료 이용 조건이 있는 LLM API 찾기 및 확인

[English](README.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [한국어](README.ko.md)

**FreeToken.link는 개발자가 날짜가 명시된 무료 이용 조건을 비교하고, 공식 API 키 발급 절차를 확인하며, 지원되는 경로를 브라우저에서 직접 테스트할 수 있도록 돕습니다. 실제 키를 포함하지 않는 설정 템플릿과 주요 변경 사항을 확인하는 Watchlist도 제공합니다.**

한국어 사이트: **[freetoken.link/ko](https://freetoken.link/ko)**

> 이 공개 저장소는 제품 안내, 배포 자료 및 피드백을 위한 공간입니다. 운영 애플리케이션 소스, 제공업체 인증 정보, 공유 API 키, 사용자 Vault 데이터 또는 운영 비밀 정보는 공개하지 않습니다.

## AI 도우미에서 사용하기

읽기 전용 **FreeToken MCP Server**가 공식 MCP Registry에 [`link.freetoken/catalog`](https://registry.modelcontextprotocol.io/v0.1/servers/link.freetoken%2Fcatalog/versions/1.0.0) **v1.0.0**으로 등록되었습니다.

Streamable HTTP를 지원하는 클라이언트에 **`https://freetoken.link/mcp`**를 추가하세요. FreeToken 계정이나 API 키는 필요하지 않습니다. 공개 모델 검색, 공식 발급 안내, 날짜가 명시된 가격 참고 정보, 비용 추정, 기존 점검 결과 조회 및 키 없는 설정 생성 기능을 제공합니다.

모델 추론, 사용자 키 테스트, 실시간 가동 여부 점검 또는 비공개 Vault 접근은 수행하지 않습니다. 도구 결과의 설명문은 현재 영어이며, locale은 사이트 링크의 언어를 지정합니다.

[한국어 연결 안내](https://freetoken.link/ko/mcp-guide) · [도구 및 제한 사항(영어)](docs/MCP.md)

## 주요 기능

- [요구 사항으로 API 찾기(영어)](https://freetoken.link/find)
- [모델 및 제공업체 검색](https://freetoken.link/ko/models)
- [공식 API 키 발급 절차 확인](https://freetoken.link/ko/get-key)
- [브라우저에서 기존 키 연결 진단](https://freetoken.link/ko/doctor)
- [프롬프트 직접 테스트](https://freetoken.link/ko/playground)
- [실제 키를 포함하지 않는 설정 생성](https://freetoken.link/ko/playground#tool-config)
- [가격 참고 정보 비교](https://freetoken.link/ko/pricing)
- [기존 가동 점검 결과 확인](https://freetoken.link/ko/status)
- [주요 변경 사항 Watchlist](https://freetoken.link/ko/watchlist)
- [정보 출처 및 검증 방식 확인](https://freetoken.link/ko/sources)

## 신뢰 및 개인정보 보호

공식 문서의 설명과 FreeToken이 운영하는 Canary의 관측 결과를 구분합니다. 무료 티어, 무료 크레딧 및 체험은 같은 의미가 아니며 계정, 지역, 할당량 조건이 적용될 수 있습니다. 목록에 있다는 사실만으로 모든 사용자에게 현재 사용 가능함을 보장하지 않습니다.

지원되는 브라우저 직접 테스트에서는 API 키와 프롬프트가 브라우저에서 선택한 제공업체로 전송됩니다. 공유 URL에는 키를 넣지 않으며, 선택적 Vault 동기화는 클라이언트에서 암호화된 데이터만 저장합니다. 키를 수집하거나 공유·재판매하지 않습니다.

잘못된 모델 ID, 오래된 조건 또는 끊어진 공식 링크를 발견하면 공식 출처 URL과 확인 날짜를 포함해 Source correction Issue를 작성해 주세요. API 키, 토큰 또는 개인정보는 게시하지 마세요.

제품과 SEO의 기준 주소는 `https://freetoken.link/`입니다. 별도 GitHub Pages 사이트는 운영하지 않습니다. FreeToken.link는 독립 제품이며 목록에 있는 제공업체의 공식 보증을 의미하지 않습니다.
