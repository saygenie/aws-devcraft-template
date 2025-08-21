# AWS DEVCRAFT Agent 참고 자료

## MCP 서버 도구 활용 가이드

AWS DEVCRAFT Agent는 다양한 MCP 서버 도구를 활용하여 전문적인 기술 조언을 제공합니다.

### AWS 관련 참고 자료

AWS와 관련된 모든 기술적 내용은 **AWS MCP 서버 도구**를 우선적으로 활용해야 합니다:

- **awsread_documentation**: AWS 문서 페이지를 마크다운으로 변환
- **awsrecommend**: 관련 AWS 문서 페이지 추천
- **awssearch_documentation**: AWS 공식 문서 검색

### 소프트웨어 라이브러리 참고 자료

Mermaid 문법, Python 코드 등 일반적인 소프트웨어 라이브러리는 **Context7 MCP 서버 도구**를 활용:

- **resolve-library-id**: 패키지명을 Context7 호환 라이브러리 ID로 변환
- **get-library-docs**: 라이브러리 최신 공식 문서 가져오기

### Amazon States Language 참고

Amazon States Language(ASL) 관련 내용은 다음 순서로 참고:

1. **AWS MCP 서버 도구 우선 활용**
2. **AWS MCP 서버에서 충분한 정보를 얻기 어려운 경우**: `@asl.md` 파일 참고

#### @asl.md 파일 사용 시 주의사항

- **용량이 큰 파일**이므로 전체 내용을 한번에 참고하지 말 것
- **필요한 특정 섹션만 선별적으로 참고**
- 주요 섹션:
  - Structure of a State Machine
  - JSONata Concepts
  - State Types (Pass, Task, Choice, Wait, etc.)
  - Error Handling

## 참고 자료 활용 원칙

1. **AWS 기술**: AWS MCP 서버 도구 최우선
2. **일반 소프트웨어**: Context7 MCP 서버 도구 활용
3. **ASL 상세 문법**: @asl.md 파일의 필요 섹션만 선별적 참고
4. **효율적 정보 수집**: 용량이 큰 문서는 부분적으로 활용
