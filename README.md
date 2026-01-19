# chopaChung 

<a href="https://chopa-chi.vercel.app/" target="_blank">
  <img
    src="https://img.shields.io/badge/VIEW%20RESUME-Frontend%20Developer-0A84FF?style=for-the-badge&labelColor=111111"
    alt="Resume Button"
  />
</a>



---
# Frontend Experience

**2025.08.18 – 2025.10.31**

### 현대홈쇼핑 UI 개발파트팀

**Tech Stack:** Next.js (Page Router), TypeScript, Vanilla Extract
**Deployment:** Bitbucket 기반 직접 배포 (사내 인프라)

#### hmall 단축 URL 페이지 리팩토링

* 기능 단위로 코드 구조 재분리 및 Compound Component Pattern 적용
* UI / 로직 분리를 통해 재사용성과 유지보수성 개선
* 🔗 [단축 URL 페이지](https://www.hmall.com/md/shortUrl) | [조회 페이지](https://www.hmall.com/md/shortUrl/lookup)

#### planH 보험사 페이지 hmall 내재화 프로젝트 – 지점찾기 페이지 (JSP → Next.js)

* 기존 JSP 기반 페이지를 Next.js(Page Router)로 마이그레이션
* 레거시 구조 분석 후 CSR/SSR 혼합 구조로 재설계
* 🔗 [planH 링크](https://hyundaiplanh.com/support/branch/list.do)

#### hmall 전시매장 / 동적 HTML 영역 조건부 핀치줌 유틸 개발

* Admin flag 기반으로 특정 영역에만 pinch-zoom을 적용하는 유틸리티 개발
* 동적 HTML 환경에서도 안정적으로 동작하도록 이벤트 처리 최적화
* 🔗 [전시매장 링크](https://www.hmall.com/md/dpa/searchSpexSectItem?sectId=1628243)

---

**2025.11.03 – 현재**

## STCLab NetFUNNEL팀 Frontend Engineer

**Tech Stack:** React, Vite, TypeScript
**Deployment:** GitHub Actions 기반 빌드 → Argo CD 배포 (SaaS / On-Prem 환경)

* 넷퍼넬 가상 대기실 SaaS – 대기 완료 사운드 기능 개발 [FE]

* SaaS 환경을 고려한 기능 단위 설계 및 확장성 중심 구현

* CI 단계에서 GitHub Actions로 빌드 자동화 후 Argo CD를 통한 배포 파이프라인 운영

* **On-Premise 환경 빗썸 구축**

  * Okta SSO 로그인 연동 및 On-Prem 환경에 맞춘 인증 플로우 설계·구현

---

## Personal Project – TradeHub

**Tech Stack:** Next.js (App Router), Tailwind CSS, Supabase
**Deployment:** Vercel

* 실시간 트레이딩 커뮤니티를 위한 PC 기반 서비스 개발
* App Router 기반 구조 설계 및 빠른 반복 개발
* Supabase 기반 인증·데이터 관리 및 Vercel 자동 배포 환경 구성
