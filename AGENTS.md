> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## About RocX

- RocX is a Proof of Activity-powered DeFi platform that combines onchain capital activity with verified user participation.
- The site contains a bilingual Whitepaper and task-focused User Guide.
- Current User Guide procedures describe the MVP/testnet environment unless an official status says otherwise.

## Terminology

다음 한/영 표기를 일관되게 사용합니다.

| 한국어 | English |
| --- | --- |
| 활동 증명 | Proof of Activity |
| 액티브 에너지 (AE) | Active Energy (AE) |
| 기여자 랭킹 | Contributor Ranking |
| 도움이 됨 | Helpful |
| 도움이 되지 않음 | Not Helpful |
| 평판 (레이어) | Reputation (Layer) |
| 신원 / 정체성 | Identity |

## Style preferences

- **원문 보존 원칙**: 백서 문구는 왜곡·누락 없이 보존한다. 표·도식(Mermaid 등)은 원문을 대체하지 않고 *보강*만 한다.
- 백서 특유의 선언적·시적 톤과 짧은 문장 리듬을 유지한다.
- 강조는 **bold**, 정의/슬로건은 `<Note>`, 경고/면책은 `<Warning>`.
- 흐름(플라이휠/체인)은 `mermaid`, 단계는 `<Steps>`, 비교는 표로 시각화한다.
- 헤딩은 간결하게, 페이지마다 frontmatter(title/description/icon) 작성.
- User Guide는 What / How / Requirement / Result / Error 중심으로 작성하고 Whitepaper 철학 문체와 분리한다.
- 폐기된 참여·보상 용어, 고정 AE-ROCX 전환, 감사 완료 또는 확인되지 않은 Mainnet/Provider/Network를 현재 기능처럼 문서화하지 않는다.

## Content boundaries

{/* Define what should and shouldn't be documented */}
{/* Example: Don't document internal admin features */}
