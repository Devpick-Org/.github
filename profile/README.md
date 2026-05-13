<div align="center">

# Trace

흩어진 기술 콘텐츠와 채용 정보를 한곳에 모아, 학습부터 취업 준비까지 이어주는 개발자 성장 플랫폼입니다.

### [Trace 서비스 바로가기](https://traceapp-orcin.vercel.app/)

https://traceapp-orcin.vercel.app/

</div>

## Service Preview

![Trace Service Preview](./assets/showcase.png)

Trace는 여러 기술 블로그, 커뮤니티, 영상, 채용 공고를 수집하고 정규화한 뒤 사용자의 관심사에 맞게 보여줍니다. 콘텐츠를 읽는 데서 끝나지 않고 레벨별 AI 요약, 문서 근거 기반 질의응답, 주간 트렌드 분석, 이력서와 모의면접 기능까지 연결해 학습 기록이 실제 취업 준비로 이어지도록 설계했습니다.

## What We Build

- 여러 출처의 기술 콘텐츠 수집 및 공통 스키마 정규화
- 관심 기술 기반 개인화 피드와 콘텐츠 추천
- 레벨별 AI 요약, 퀴즈, 근거 기반 질의응답
- 주간 기술 트렌드 분석과 학습 활동 리포트
- 채용 공고 매칭, 이력서 관리, 면접 Q&A와 모의면접

## Architecture

![Trace Architecture](./assets/architecture.png)

Trace는 Next.js 프론트엔드, Spring Boot 백엔드, FastAPI AI 서버로 구성됩니다. 운영 환경에서는 프론트엔드를 Vercel에서 제공하고, 브라우저의 API 요청은 Nginx를 거쳐 Spring Boot로 전달됩니다. AI 요약과 RAG 답변은 FastAPI가 Amazon Bedrock, DynamoDB, FAISS 인덱스를 활용해 처리합니다.

## Repositories

| Repository | Role |
| --- | --- |
| [devpick-frontend](https://github.com/Devpick-Org/devpick-frontend) | Next.js 기반 사용자 웹 애플리케이션 |
| [devpick-backend](https://github.com/Devpick-Org/devpick-backend) | Spring Boot 기반 API 서버 |
| [devpick-ai](https://github.com/Devpick-Org/devpick-ai) | FastAPI 기반 수집, 요약, RAG, 트렌드 분석 서버 |
| [devpick-infra](https://github.com/Devpick-Org/devpick-infra) | 인프라와 배포 설정 |

## Tech Stack

| Area | Stack |
| --- | --- |
| Frontend | Next.js, React, TypeScript, Tailwind CSS, TanStack Query, Axios |
| Backend | Spring Boot, Java, JPA, PostgreSQL, Redis |
| AI | FastAPI, Python, Amazon Bedrock, Claude, Titan Embeddings, FAISS |
| Data | PostgreSQL, DynamoDB, ElastiCache Redis, S3 |
| Infra | AWS EC2, Docker, Nginx, GitHub Actions, Vercel |

## Team

DevPick is building Trace as a capstone project focused on practical developer learning, technical content discovery, and career preparation.

<table>
  <tr>
    <td align="center" width="180">
      <a href="https://github.com/khg9859">
        <img src="https://github.com/khg9859.png" width="96" height="96" style="border-radius: 50%;" alt="김홍근" />
      </a>
      <br />
      <strong>김홍근</strong>
      <br />
      <sub>PM / Backend Lead</sub>
      <br />
      <a href="https://github.com/khg9859">@khg9859</a>
    </td>
    <td align="center" width="180">
      <a href="https://github.com/nYeonG4001">
        <img src="https://github.com/nYeonG4001.png" width="96" height="96" style="border-radius: 50%;" alt="박하영" />
      </a>
      <br />
      <strong>박하영</strong>
      <br />
      <sub>Backend</sub>
      <br />
      <a href="https://github.com/nYeonG4001">@nYeonG4001</a>
    </td>
    <td align="center" width="180">
      <a href="https://github.com/suheon98">
        <img src="https://github.com/suheon98.png" width="96" height="96" style="border-radius: 50%;" alt="조수헌" />
      </a>
      <br />
      <strong>조수헌</strong>
      <br />
      <sub>AX</sub>
      <br />
      <a href="https://github.com/suheon98">@suheon98</a>
    </td>
    <td align="center" width="180">
      <a href="https://github.com/uiuuoq">
        <img src="https://github.com/uiuuoq.png" width="96" height="96" style="border-radius: 50%;" alt="홍보민" />
      </a>
      <br />
      <strong>홍보민</strong>
      <br />
      <sub>Frontend</sub>
      <br />
      <a href="https://github.com/uiuuoq">@uiuuoq</a>
    </td>
  </tr>
</table>
