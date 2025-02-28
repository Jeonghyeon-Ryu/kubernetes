# kubernetes
### 1장. 도커 및 컨테이너 기초
  - 기술 요구 사항
  - 컨테이너화의 필요성 이해
  - 쿠버네티스에서 도커를 지원 중단하는 이유
  - 도커 소개
  - 도커 이해하기
  - 컨테이너는 일시적이다
  - 도커 이미지
  - 이미지 레이어
  - 영구 데이터
  - 컨테이너에서 실행 중인 서비스에 액세스
  - 도커 설치
  - 도커 설치 준비
  - Ubuntu에 도커 설치
  - 도커 권한 부여
  - 도커 CLI 사용
  - docker help
  - docker run
  - docker ps
  - docker start and stop
  - docker attach
  - docker exec
  - docker logs
  - docker rm

### 2장. KinD를 이용한 쿠버네티스 배포
  - 기술 요구 사항
  - 쿠버네티스 컴포넌트 및 오브젝트 소개
  - 클러스터와 상호 작용
  - 개발 클러스터 사용
  - 기본 KinD 쿠버네티스 클러스터로 작업하기
  - 노드 이미지 이해
  - KinD 및 도커 네트워킹
  - 중첩 인형 추적
  - KinD 설치
  - KinD 설치 - 사전 조건
  - kubectl 설치
  - KinD 바이너리 설치
  - KinD 클러스터 만들기
  - 단순 클러스터 생성
  - 클러스터 삭제
  - 클러스터 설정 파일 생성
  - 다중 노드 클러스터 설정
  - 컨트롤 플레인 및 Kubelet 옵션 커스터마이징
  - 사용자 지정 KinD 클러스터 만들기
  - Calico 설치
  - 인그레스 컨트롤러 설치
  - KinD 클러스터 검토
  - KinD 스토리지 오브젝트
  - 스토리지 드라이버
  - KinD 스토리지 클래스
  - KinD의 스토리지 프로비저너 사용
  - 인그레스용 커스텀 로드밸런서 추가
  - 설치 사전 요구 사항
  - KinD 클러스터 설정 생성하기
  - 사용자 지정 HAProxy 컨테이너 배포
  - HAProxy 트래픽 흐름 이해
  - kubelet 장애 시뮬레이션

### 3장. 쿠버네티스 부트캠프
  - 기술 요구 사항
  - 쿠버네티스 컴포넌트 개요
  - 컨트롤 플레인 살펴보기
  - 쿠버네티스 API 서버
  - Etcd 데이터베이스
  - kube-scheduler
  - kube-controller-manager
  - cloud-controller-manager
  - 작업자 노드 컴포넌트 이해
  - kubelet
  - kube-proxy
  - 컨테이너 런타임
  - API 서버와 상호 작용
  - 쿠버네티스 kubectl 유틸리티 사용
  - Verbose 옵션 이해
  - 일반 kubectl 명령어
  - 쿠버네티스 리소스 소개
  - 쿠버네티스 매니페스트
  - 쿠버네티스의 리소스는 무엇인가?
  - 쿠버네티스 리소스 검토
  - 컨피그맵
  - 엔드포인트
  - 이벤트
  - 네임스페이스
  - 노드
  - 퍼시스턴트 볼륨 클레임
  - 퍼시스턴트 볼륨
  - 파드
  - 레플리케이션 컨트롤러
  - 리소스쿼터
  - 시크릿
  - 서비스어카운트
  - 서비스
  - 커스텀리소스데피니션
  - 데몬셋
  - 디플로이먼트
  - 레플리카셋
  - 스테이트풀셋
  - HorizontalPodAutoscalers
  - 크론잡
  - 잡
  - 인그레스
  - 네트워크폴리시
  - 파드 시큐리티 폴리시
  - 클러스터롤바인딩
  - 클러스터롤
  - 롤바인딩
  - 롤
  - CSI 드라이버
  - CSI 노드
  - 스토리지 클래스

### 4장. 서비스, 로드밸런서, ExternalDNS 그리고 글로벌 밸런싱
  - 기술 요구 사항
  - 요청에 대한 워크로드 노출
  - 서비스 작동 방식 이해
  - 서비스 생성
  - DNS를 사용해 서비스 해결
  - 다양한 서비스 유형 이해
  - ClusterIP 서비스
  - NodePort 서비스
  - 로드밸런서 서비스
  - ExternalName 서비스
  - 로드밸런서 소개
  - OSI 모델에 대해서
  - 레이어 7 로드밸런서
  - 이름 해석 및 레이어 7 로드밸런서
  - 이름 해석에 nip.io 사용
  - 인그레스 규칙 생성
  - 레이어 4 로드밸런서
  - 레이어 4 로드밸런서 옵션
  - 레이어 4 로드밸런서로 MetalLB 사용
  - MetalLB 설치
  - MetalLB 설정 파일 이해
  - MetalLB 컴포넌트
  - 스피커
  - 컨트롤러
  - 로드밸런서 서비스 생성
  - MetalLB에 여러 IP 풀 추가
  - 다중 프로토콜 사용
  - 여러 가지 프로토콜 문제
  - MetalLB와 함께 여러 프로토콜 사용
  - 공유 IP 사용
  - 엔터프라이즈를 위한 로드밸런서 강화
  - 서비스 이름을 외부에서 사용할 수 있도록 설정
  - external-dns 설정
  - external-dns와 CoreDNS 연동
  - CoreDNS에 ETCD 존 추가
  - ExternalDNS 연동으로 로드밸런서 서비스 생성
  - CoreDNS와 엔터프라이즈 DNS의 연동
  - 프라이머리 DNS 서버 설정
  - CoreDNS로의 DNS 전달 테스트
  - 멀티 클러스터 간의 로드밸런싱
  - 쿠버네티스 글로벌 밸런서 소개
  - K8GB의 요건
  - 클러스터에 K8GB 배포
  - K8GB 로드밸런싱 옵션 이해
  - 헬름 차트 값 사용자 정의
  - 헬름을 사용한 K8GB 설치
  - K8GB를 사용한 고가용성 애플리케이션 배포
  - 커스텀 리소스르 사용해 K8GB에 애플리케이션 추가
  - 인그레스 어노테이션을 사용해 K8GB에 애플리케이션 추가
  - K8GB의 글로벌 로드밸런싱 기능 이해
  - K8GB CoreDNS 서버의 동기화 유지

### 5장. 클러스터 인증 연동
  - 기술 요구 사항
  - 쿠버네티스가 당신을 어떻게 아는지 이해하기
  - 외부 사용자
  - 쿠버네티스의 그룹
  - 서비스어카운트
  - OpenID Connect 이해
  - OpenID Connect 프로토콜
  - OIDC와 API의 상호 작용을 추적
  - id_token
  - 기타 인증 옵션
  - 인증서
  - 서비스어카운트
  - TokenRequest API
  - 커스텀 인증 웹훅
  - 키스톤
  - OpenID Connect에 대한 KinD 설정
  - 요구 사항에 대한 대응
  - 쿠버네티스에서의 LDAP 및 액티브 디렉터리 사용
  - 액티브 디렉터리 그룹을 RBAC 롤바인딩에 매핑
  - 쿠버네티스 대시보드 액세스
  - 쿠버네티스 CLI 액세스
  - 엔터프라이즈 규정 준수 요구 사항
  - 모든 것을 한데 모으기
  - OpenUnison 배포
  - OIDC를 사용하기 위한 쿠버네티스 API 설정
  - OIDC 연동 확인
  - kubectl과 함께 토큰 사용
  - 클라우드 관리형 클러스터와 인증을 연동하기 위한 가장 도입
  - 가장이란?
  - 보안에 관한 고려 사항
  - 가장을 위한 클러스터 구성
  - 가장 테스트
  - OpenUnison을 사용하지 않는 가장 설정
  - 가장 RBAC 정책
  - 기본 그룹
  - 클러스터에 대한 파이프라인에서 인증
  - 토큰 사용
  - 인증서 사용
  - 안티 패턴 회피

### 6장. 롤 기반 액세스 제어 정책 및 감사
  - 기술 요구 사항
  - RBAC 소개
  - 롤이란
  - 롤 식별
  - 롤 대 클러스터롤
  - 네거티브 롤
  - 집계된 클러스터롤
  - 롤바인딩 및 클러스터 롤바인딩
  - 클러스터롤 및 롤바인딩 결합
  - 리소스에 대한 액세스 권한을 부여하기 위해 엔터프라이즈 ID를 쿠버네티스에 매핑
  - 네임스페이스 멀티테넌시 구현
  - 쿠버네티스 감사
  - 감사 정책 만들기
  - 클러스터에서 감사 활성화
  - audit2rbac를 사용한 정책 디버깅

### 7장. 안전한 쿠버네티스 대시보드 배포
  - 기술 요구 사항
  - 대시보드에서의 사용자
  - 대시보드 아키텍처
  - 인증 방법
  - 대시보드 보안 위험 이해
  - 안전하지 않은 대시보드 배포
  - 토큰을 사용해 로그인
  - 리버스 프록시로 대시보드 배포
  - 로컬 대시보드
  - 기타 클러스터 레벨 애플리케이션
  - 오픈유니슨과 대시보드 통합

### 8장. 개방형 정책 에이전트를 사용한 보안 확장
  - 기술 요구 사항
  - 동적 승인 컨트롤러 소개
  - OPA의 정의 및 동작
  - OPA 아키텍처
  - OPA 정책 언어, Rego
  - 게이트키퍼
  - 게이트키퍼 배포
  - 자동화된 테스트 프레임워크
  - Rego를 사용한 정책 작성
  - OPA 정책 개발
  - OPA 정책 테스트
  - 게이트키퍼에 정책 배포
  - 동적 정책 구축
  - Rego 디버깅하기
  - 기존 정책 사용
  - 메모리 제약 적용
  - 게이트키퍼 캐시 활성화
  - 테스트 데이터 모킹
  - 정책 구축 및 배포
  - 오브젝트 및 기본값 변형

### 9장. 게이트키퍼로 노드 보안 구현
  - 기술 요구 사항
  - 노드 보안
  - 컨테이너와 VM 간의 차이점 이해
  - 컨테이너 브레이크아웃
  - 적절한 컨테이너 설계
  - 게이트키퍼로 노드 보안 적용
  - 파드 보안 정책
  - PSP와 게이트키퍼의 차이점
  - 노드 보안 정책 승인
  - 노드 보안 정책 배포 및 디버깅
  - 보안 컨텍스트 기본값 생성
  - 클러스터 정책 적용
  - 제약 조건 위반 디버깅
  - 멀티테넌트 클러스터의 스케일링 정책 배포

### 10장. 팔코, 데브옵스 AI, ECK를 통한 감사
  - 기술 요구 사항
  - 감사 살펴보기
  - 팔코 소개
  - 팔코 설정 파일 살펴보기
  - 헬름 밸류 파일
  - 헬름 밸류 커스터마이징
  - 팔코 규칙 설정 파일
  - 규칙 이해
  - 조건(필드 및 값) 이해
  - 매크로 사용
  - 목록 이해하기
  - 사용자 지정 규칙 생성 및 추가
  - 기존 규칙 수정
  - 신규 규칙 만들기
  - 팔코 배포
  - 팔코사이드킥 소개
  - 팔코사이드킥 설치
  - 쿠브리스의 이해
  - 쿠브리스의 설치
  - 쿠브리스를 사용한 함수 배포
  - 데브옵스 AI
  - 이벤트에 대한 자동 응답 이해
  - NGINX 서버 배포 및 연결 테스트
  - 파드에 대한 공격 시뮬레이션
  - 팔코 이벤트 관측
  - FalcoSideKick-UI 사용
  - 로깅 시스템 배포
  - 신규 네임스페이스 생성
  - ECK 오퍼레이터 배포
  - 일래스틱서치, 파일비트, 키바나 배포
  - 로그를 보기 위한 ECK 구성 요소 사용
  - 키바나 인덱스 생성
  - 이벤트 탐색
  - 시각화
  - 대시보드 생성
  - 팔코 이벤트 유형에 대한 시각화 생성

### 11장. 워크로드 백업
  - 기술 요구 사항
  - 쿠버네티스 백업에 대한 이해
  - etcd 백업 수행
  - 필요한 인증서 백업
  - etcd 데이터베이스 백업
  - VMware 벨레로 소개 및 설정
  - 벨레로 요구 사항
  - 벨레로 CLI 설치
  - 벨레로 설치
  - 백업 스토리지 위치
  - MinIO 배포
  - MinIO 및 콘솔 노출
  - S3 대상 설정 생성
  - 벨레로를 사용한 워크로드 백업
  - 일회성 클러스터 백업 실행
  - 클러스터 백업 스케줄링
  - 사용자 지정 백업 생성
  - CLI를 사용한 벨레로 관리
  - 일반적인 벨레로 명령 사용
  - 벨레로 오브젝트 목록
  - 벨레로 오브젝트 세부 정보 검색
  - 오브젝트 생성 및 삭제
  - 백업에서 복원
  - 복원 작업
  - 백업에서 배포 복원
  - 네임스페이스 백업
  - 장애 시뮬레이션
  - 네임스페이스 복원
  - 백업을 사용한 신규 클러스터 워크로드 생성
  - 클러스터 백업
  - 신규 클러스터 구축
  - 신규 클러스터에 백업 복원
  - 신규 클러스터에 벨레로 설치
  - 신규 클러스터에서 백업 복원
  - 신규 클러스터 삭제

### 12장. 이스티오 소개
  - 기술 요구 사항
  - 서비스 메시에 신경을 써야 하는 이유는 무엇일까?
  - 워크로드 관측성
  - 트래픽 관리
  - 블루/그린 배포
  - 카나리 배포
  - 문제가 발생하기 전에 문제 찾기
  - 보안
  - 이스티오 개념 소개
  - 이스티오 구성 요소 이해
  - istiod를 사용해 컨트롤 플레인을 단순하게 만들기
  - istiod 파드 브레이킹
  - Pilot - 사이드카 관리
  - Galley - 구성 검증
  - Citadel - 인증서 관리
  - Mixer - 보안 키퍼
  - 이스티오-인그레스 게이트웨이에 대한 이해
  - 이스티오-이그레스 게이트웨이에 대한 이해
  - 이스티오 설치
  - 이스티오 다운로드
  - 프로필을 사용한 이스티오 설치
  - 이스티오 리소스 소개
  - 권한 부여 정책
  - 예 1: 모든 액세스 거부 및 허용
  - 예 2: 워크로드에 GET 메서드만 허용
  - 예 3: 특정 소스의 요청 허용
  - 게이트웨이
  - 가상 서비스
  - 대상 규칙
  - 피어 인증
  - 인증 요청
  - 서비스 항목
  - 사이드카
  - Envoy 필터
  - 관측성을 제공하는 애드온 구성 요소 배포
  - 프로메테우스 설치
  - Jaeger 설치
  - Kiali 설치
  - 서비스 메시에 애플리케이션 배포
  - 첫 번째 애플리케이션을 메시에 배포하기
  - Kiali를 사용한 메시 워크로드 관찰
  - Kiali 개요 화면
  - 그래프 뷰 사용
  - 애플리케이션 뷰 사용
  - 워크로드 뷰 사용
  - 서비스 뷰 사용
  - 이스티오 구성 뷰

### 13장. 이스티오에서 애플리케이션 빌드 및 배포
  - 기술 요구 사항
  - 마이크로서비스와 모놀리스의 비교
  - 마이크로서비스와 모놀리식 아키텍처에 대한 나의 이야기
  - 애플리케이션 아키텍처 비교
  - 모놀리식 애플리케이션 설계
  - 마이크로서비스 설계
  - 모놀리스와 마이크로서비스 중에서 선택
  - 이스티오를 사용한 마이크로서비스 관리 지원
  - 모놀리스 배포하기
  - 모놀리스를 클러스터 외부에 노출
  - 고정 세션 구성
  - Kiali와 오픈유니슨의 통합
  - 마이크로서비스 구축
  - Hello World 배포하기
  - 우리 서비스에 인증 통합
  - 우리 서비스에 액세스 권한 부여
  - 서비스를 누가 사용하고 있는지 알고 싶다면
  - 사용자 자격 부여
  - 서비스 승인
  - 이스티오와 함께 OPA 사용
  - 다른 서비스 호출하기
  - OAuth2 토큰 교환 사용
  - 서비스 인증하기
  - 수표 작성 서비스 배포 및 실행
  - 가장 사용
  - 위임 사용
  - 서비스 간 토큰 전달
  - 단순 가장 사용
  - API 게이트웨이가 필요한가?

### 14장. 플랫폼 프로비저닝
  - 기술 요구 사항
  - 파이프라인 설계
  - 독단적 플랫폼
  - 파이프라인 보안
  - 플랫폼 요구 사항 구축
  - 기술 스택 선택
  - 클러스터 준비
  - cert-manager 배포
  - 도커 컨테이너 레지스트리 배포
  - 오픈유니슨 및 게이트키퍼 배포
  - 깃랩 배포
  - 예제 프로젝트 만들기
  - Tekton 배포
  - Hello World 만들기
  - 자동으로 빌드하기
  - ArgoCD 배포
  - 오픈유니슨을 사용한 프로젝트 온보딩 자동화
  - 깃옵스 전략 설계
  - 깃랩 통합
  - TektonCD 대시보드 통합
  - ArgoCD 통합
  - 오픈유니슨 업데이트
  - 애플리케이션 배포
  - 쿠버네티스에서 애플리케이션 생성
  - 개발자에게 접근하기
  - 개발 매니페스트 배포
  - Tekton 파이프라인 배포
  - 파이프라인 실행
  - 프로덕션으로 프로모션
