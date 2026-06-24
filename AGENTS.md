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

- RocX는 **Survival Finance(생존 금융)** — Powered by **Proof of Activity(활동 증명)** 를 표방하는 Web3 금융 프로토콜입니다.
- 본 문서는 RocX 백서를 Mintlify로 옮긴 것입니다. 원본: `국문백서 초안(0622).pdf` (초안 단계).
- 현재 한국어 기본. 추후 영문(`/en`) 추가 예정.

## Terminology

다음 한/영 표기를 일관되게 사용합니다.

| 한국어 | English |
| --- | --- |
| 생존 금융 | Survival Finance |
| 활동 증명 | Proof of Activity |
| 활동 대출 / 액티브 렌딩 | Active Lending |
| 액티브 에너지 (AE) | Active Energy (AE) |
| 평판 (레이어) | Reputation (Layer) |
| 신원 / 정체성 | Identity |
| 영혼 결속 토큰 | SBT (Soulbound Token) |
| 총 예치 자산 / 총 예치금 | TVL |

- 핵심 슬로건: **예치 · 탐험 · 증명 · 생존**

## Style preferences

- **원문 보존 원칙**: 백서 문구는 왜곡·누락 없이 보존한다. 표·도식(Mermaid 등)은 원문을 대체하지 않고 *보강*만 한다.
- 백서 특유의 선언적·시적 톤과 짧은 문장 리듬을 유지한다.
- 강조는 **bold**, 정의/슬로건은 `<Note>`, 경고/면책은 `<Warning>`.
- 흐름(플라이휠/체인)은 `mermaid`, 단계는 `<Steps>`, 비교는 표로 시각화한다.
- 헤딩은 간결하게, 페이지마다 frontmatter(title/description/icon) 작성.

## Content boundaries

{/* Define what should and shouldn't be documented */}
{/* Example: Don't document internal admin features */}
