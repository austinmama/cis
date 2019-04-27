---

copyright:
  years: 2018, 2019
lastupdated: "2019-03-14"

keywords: configuration domain, Free Trial plan, CIS instance

subcollection: cis

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:faq: data-hd-content-type='faq'}



# FAQ
{:#faq}

## 카탈로그에 있던 조기 액세스 플랜에 어떤 상황이 발생했습니까?
{:#cis-faq-early-access-plan}
{: faq}

조기 액세스 플랜은 2018년 5월 31일에 카탈로그에서 제거되었습니다. 이는 표준 유료 플랜과 새 30일 무료 평가판 플랜으로 바뀌었습니다. 조기 액세스 플랜의 인스턴스가 있는 경우 데이터 손실을 방지하기 위해 즉시 표준 플랜으로 업그레이드하십시오. 조기 액세스 베타에 참여한 경우 무료 평가판 인스턴스를 작성할 수 없습니다.

## 무료 평가판 플랜에는 어떤 것이 제공됩니까?
{:#cis-faq-free-trial-plan}
{: faq}

무료 평가판 플랜은 계정당 하나의 구역만 허용합니다. 계정당 오직 하나의 인스턴스만 작성하고 구역 이름을 확인하도록 권장합니다. 구역 이름은 추가되기 전에 반드시 확인을 거쳐야 합니다. 구역이 삭제되면 무료 평가판 플랜 중에 다른 구역이나 동일한 구역을 추가할 수 없습니다.

## 몇 개의 무료 평가판 인스턴스를 가질 수 있습니까?
{:#cis-faq-free-trial-instances}
{: faq}

계정의 수명 동안 계정마다 최대 하나의 무료 평가판 인스턴스를 가질 수 있습니다. 무료 평가판 인스턴스가 이미 있거나 무료 시범 인스턴스를 삭제하거나 무료 평가판이 만료된 경우 다른 무료 평가판 인스턴스를 작성할 수 없습니다. 하지만 작성한 무료 평가판에 관계없이 다른 유료 플랜 유형(예: 표준)의 인스턴스를 작성할 수 있습니다.

## 조기 액세스 플랜에 등록된 서비스 인스턴스가 있습니다. 무료 평가판으로 변경할 수 있습니까?
{:#cis-faq-early-access-to-free-trial-plan}
{: faq}

아니요. 조기 액세스 플랜은 유료 플랜(현재 표준 플랜임)으로만 업그레이드할 수 있습니다.

## 삭제한(하지 않았을 수도 있음) 조기 액세스 인스턴스가 있었습니다. 지금 무료 평가판 인스턴스를 작성할 수 있습니까?
{:#cis-faq-early-access-and-free-trial-plan}
{: faq}

아니요. 각 계정에는 하나의 무료 인스턴스만 사용할 수 있습니다. 조기 액세스 플랜 및 이를 대체한 무료 평가판 플랜은 둘 다 무료 플랜으로 간주됩니다. 또한 이는 최대 하나의 무료 평가판 인스턴스를 가질 수 있음을 의미합니다.

## 표준에서 무료 평가판으로 다운그레이드할 수 있습니까?
{:#cis-faq-downgrade-standard-to-free-plan}
{: faq}

아니요. 이것은 허용되지 않습니다.

## 무료 평가판이 만료되었습니다. 선택할 수 있는 옵션은 무엇입니까?
{:#cis-faq-free-trial-plan-expired}
{: faq}

데이터 손실을 방지하려면 만기 날짜 이전에 무료 평가판에서 표준으로 업그레이드해야 합니다. 이후에는 플랜 업그레이드 또는 CIS 인스턴스 삭제만 지원합니다. 인스턴스 시작부터 45일 후에 인스턴스가 삭제되거나 업그레이드되지 않은 경우 구성 도메인, GLB, 풀 및 상태 검사가 자동으로 삭제됩니다.

## 내 CIS 인스턴스를 어떻게 삭제합니까?
{:#{:#cis-faq-delete-instance}
{: faq}

CIS 인스턴스를 삭제하려면 먼저 모든 GLB, 풀 및 상태 검사를 삭제해야 합니다. 그런 다음 연관된 도메인(구역)을 삭제하십시오. **개요** 페이지로 이동하고 **서비스 세부사항** 섹션에 있는 도메인 이름 옆 휴지통 아이콘을 클릭하여 삭제 프로세스를 시작하십시오.

## 사용자를 내 계정에 추가했고 이 사용자에게 Internet Services 인스턴스를 관리할 수 있는 권한을 부여했습니다. 해당 사용자에게 인증 문제가 발생하는 이유는 무엇입니까?
{:#cis-faq-user-authentication-issue}
{: faq}

사용자에게 "서비스 액세스 역할"을 지정하지 않았을 수 있습니다. 두 개의 별도의 역할 세트인 "플랫폼 액세스"와 "서비스 액세스"가 있습니다. 서비스 인스턴스를 작성하고 관리하려면 플랫폼 액세스 역할이 필요하지만 서비스 인스턴스에서 서비스 특정 오퍼레이션을 수행하려면 서비스 액세스 역할이 필요합니다. 콘솔에서 **관리 > 보안 > ID 및 액세스**를 선택하여 이러한 설정을 업데이트할 수 있습니다.

## 내 도메인이 보류 상태인 이유는 무엇입니까? 이를 어떻게 활성화합니까?
{:#cis-faq-pending-domain}
{: faq}

CIS에 도메인을 추가하는 경우에는 등록자에서(또는 하위 도메인을 추가 중인 경우에는 DNS 제공자에서) 구성할 2개의 이름 서버가 제공됩니다. 도메인 또는 하위 도메인은 이름 서버가 올바르게 구성될 때까지 보류 상태를 유지합니다. 두 이름 서버가 등록자 또는 DNS 제공자에 추가되었는지 확인하십시오. 당사는 정기적으로 공용 DNS 시스템을 스캔하여 이름 서버가 지시대로 구성되었는지 여부를 확인합니다. 이름 서버 변경사항을 확인할 수 있으며(이는 최대 24시간이 걸림) 당사는 즉시 사용자의 도메인을 활성화합니다. 개요 페이지에서 **이름 서버 재확인**을 클릭하여 이름 서버를 재확인하는 요청을 제출할 수 있습니다.

## 내 도메인의 등록자는 누구입니까?
{:#cis-faq-who-is-registrar}
{: faq}

이 정보에 대해서는 다음에 문의하십시오. https://whois.icann.org/ **참고**: 등록자에서 도메인의 구성을 편집하여 CIS에 추가 시에 도메인에 대해 제공된 이름 서버를 업데이트하거나 추가하려면 관리 권한이 있어야 합니다. CIS에 추가할 도메인에 대해 등록자가 누구인지 모르는 경우에는 등록자에서 도메인의 구성을 업데이트할 권한이 없을 수 있습니다. 조직의 도메인 소유자와 함께 작업하여 필요한 변경을 수행하십시오.

## 내 도메인(example.com)의 내 현재 DNS 제공자를 그대로 유지하고 싶습니다. 내 현재 DNS 제공자에서 CIS로 하위 도메인(subdomain.example.com)을 위임할 수 있습니까?
{:#cis-faq-keep-current-dns-provider}
{: faq}

예. 이 프로세스는 도메인 추가와 유사하지만, 등록자 대신 사용자가 직접 상위 레벨 도메인의 DNS 제공자와 함께 작업합니다. 하위 도메인을 CIS에 추가하면 일반적으로 구성할 2개의 이름 서버가 제공됩니다. 사용자는 기타 DNS 제공자가 관리하는 도메인 내에서 DNS 레코드로서 2개의 이름 서버 각각에 대해 이름 서버(NS) 레코드를 구성합니다. 필수 NS 레코드가 추가되었는지 확인할 수 있으면 당사는 사용자의 하위 도메인을 활성화합니다. 조직 내에서 상위 레벨 도메인을 관리하지 않는 경우, 사용자는 상위 레벨 도메인의 소유자과 함께 작업하여 추가된 NS 레코드를 가져와야 합니다.

## TLS는 무엇입니까?
{:#cis-faq-what-is-tls}
{: faq}

TLS는 온라인 통신에서 웹 서버와 브라우저 간의 암호화된 링크를 설정하기 위한 표준 보안 프로토콜입니다. TLS 인증서는 웹 사이트와의 TLS 연결을 작성하는 데 필요하며 도메인 이름, 회사 이름 및 추가 데이터(예: 회사 주소, 구/군/시, 시/도 및 국가)로 구성되어 있습니다. 인증서는 만기 날짜 및 발행 인증 기관(CA)의 상세 정보도 표시합니다.

## TLS는 어떻게 작동합니까?
{:#cis-faq-how-does-tls-work}
{: faq}

브라우저가 TLS 보안 웹 사이트와의 연결을 시작할 때 이는 우선 사이트의 TLS 인증서를 검색하여 해당 인증서가 아직 유효한지 여부를 확인합니다. 이는 CA를 브라우저에서 신뢰하며 발행된 대상 웹 사이트에서 해당 인증서를 사용 중임을 확인합니다. 이러한 확인에 실패하면 웹 사이트가 유효한 인증서로 보호되지 않음을 표시하는 경고를 받습니다.

TLS 인증서가 웹 서버에 설치된 경우, 이는 웹 서버와 이에 연결된 브라우저 간에 보안 연결을 사용합니다. 웹 사이트의 URL 접두부는 "http"가 아닌 "https"이며 자물쇠가 주소 표시줄에 표시됩니다. 웹 사이트에서 EV(Extended Validation) 인증서를 사용하는 경우에는 브라우저에서 초록색 주소 표시줄을 표시할 수도 있습니다.

## 개인정보 보호 경고가 표시되는 이유는 무엇입니까?
{:#cis-faq-privacy-warning}
{: faq}

IBM Cloud CIS에서 발행한 TLS 인증서는 루트 도메인(`example.com`) 및 한 레벨의 하위 도메인(`*.example.com`)을 커버합니다. 2차 레벨 하위 도메인(`*.*.example.com`)에 도달하려고 시도하는 경우, 해당 호스트 이름이 SAN에 추가되지 않았으므로 브라우저에서 개인정보 보호 경고가 표시됩니다.

또한 파트너 인증 기관(CA) 중 하나가 새 인증서를 발행하는 동안 최대 15분 정도 대기하십시오. 새 인증서가 아직 발행되지 않았으면 브라우저에서 개인정보 보호 경고가 표시됩니다.

## 왜 올바르지 않은 SSL 인증서 오류가 표시됩니까?
{:#cis-faq-invalid-ssl-cert-error}
{: faq}

사이트를 방문할 때 "오류 526, 올바르지 않은 SSL 인증서"가 표시되면 오리진 인증서가 올바르지 않음을 의미할 수 있습니다. CIS 프록시가 사용되면 기본 SSL 모드("엔드-투-엔드 CA 서명"임)에서 올바른 CA 서명 인증서가 오리진에 필요합니다. SSL 모드의 기본 설정은 이전에 "엔드-투-엔드 유연성"이었으며, 이 경우 오리진에서 제공하는 인증서의 유효성을 무시합니다. 새 기본값은 새로 추가된 도메인에만 적용됩니다. 기본 SSL 모드가 '엔드-투-엔드 유연성'일 때 도메인이 추가되는 경우 이 설정을 겹쳐쓰지 않습니다. 모드를 덜 엄격한 모드로 변경할 수 있지만 프로덕션 환경에는 권장되지 않습니다.

## DDoS는 무엇입니까?
{:#cis-faq-what-is-ddos}
{: faq}

분산 서비스 거부(DDoS) 공격은 여러 소스의 트래픽으로 제압하여 온라인 서비스를 사용 불가능하게 만들려는 시도입니다. DDoS 공격에서 다수의 감염된 컴퓨터 시스템은 서버, 웹 사이트 및 기타 네트워크 리소스 등의 대상을 공격하며 이는 대상 리소스의 사용자에게 영향을 미칩니다.

대상 시스템으로 마구 밀려오는 수신 메시지, 연결 요청 또는 잘못된 형식의 패킷 때문에 대상 시스템은 느려지거나 심지어는 장애가 발생하고 작동이 중지됩니다. 이에 따라 정당한 사용자나 시스템에 대한 서비스가 거부됩니다. DDoS 공격은 개인 범죄자 해커에서부터 조직적 범죄 단체와 정부 기관에 이르기까지 다양한 위협 행위자에 의해 자행되어 왔습니다.

## DDoS 공격을 받으면 어떻게 해야 합니까?
{:#cis-faq-what-to-do-in-ddos}
{: faq}

**1단계:** **개요** 화면에서 "방어 모드"를 켜십시오. 

![방어 모드](images/defense-mode.png)

**2단계:** 보안을 최대화하도록 DNS 레코드를 설정하십시오.

**3단계:** IBM CIS의 요청을 억제하거나 속도를 제한하지 마십시오. 해당 상황을 지원하려면 대역폭이 필요합니다.

**4단계:** 필요하면 특정 국가나 방문자를 차단하십시오.

## 522 오류가 발생했습니다. 지금 무엇을 해야 합니까?
{:#cis-faq-522-error}
{: faq}

522 오류는 오리진 서버(호스트)와의 연결을 설절할 수 없음을 표시합니다. 연결에 실패한 후 약 15초가 지나면 연결이 닫히며 522 오류 페이지가 표시됩니다.

이 문제는 대개 IP 주소를 우발적으로 차단하는 방화벽이나 보안 소프트웨어에 의해 발생합니다. CIS가 리버스 프록시로서 작동하므로 사용자 사이트에 대한 연결은 CIS IP 범위의 연결로서 나타납니다. 이 작동으로 특정 방화벽은 해당 연결을 차단할 수 있으며, 이에 따라 적절하게 사이트 방문자에게 컨텐츠를 서비스하지 못하도록 막습니다.

이 문제를 해결하려면 [여기](/docs/infrastructure/cis?topic=cis-ibm-cloud-cis-whitelisted-ip-addresses)에 나열된 모든 CIS IP 범위를 화이트리스트에 추가하도록 호스트에 요청하십시오.

522 오류를 피하려면 이 모든 IP가 화이트리스트에 추가되어야 합니다. 해당 범위의 IP가 차단되는지 여부를 확인하는 것도 좋은 방법입니다.

522 오류는 네트워크 연결 문제에 의해 발생할 수도 있습니다. 따라서 서버와 네트워크가 일반적으로 정상 상태이며 과부하 상태가 아님을 확인하십시오.

위의 단계를 수행한 후에도 여전히 오류가 수신되는 경우 IBM CIS 지원 팀에 문의하여 다음을 확인하십시오.

* IP 범위가 화이트리스트에 추가됨
* 서버/네트워크가 온라인 상태이며 일반적으로 정상 상태임

지원 팀에 문의하는 경우에는 최근 522 오류의 ray ID를 제공하십시오. 당사는 이를 사용하여 사용자가 히트 중인 CIS 데이터 센터를 판별하고 추가 테스트를 실행할 수 있습니다.

## 프록싱 레코드는 무엇이며 이는 왜 필요합니까?
{:#cis-faq-proxied-record}
{: faq}

프록싱 레코드는 IBM CIS를 통해 해당 트래픽을 프록싱하는 레코드입니다. 오직 프록싱 레코드만 보호를 위해 CIS IP가 오리진 IP로 대체된 IP 마스킹 등의 CIS 이점을 이용합니다.

```
$ whois 104.28.22.57 | grep OrgName
OrgName:        IBM
```

도메인의 CIS를 무시하려는 경우(당사는 여전히 DNS를 분석함) 레코드를 프록싱하지 않는 것이 가능한 솔루션입니다.

## DNS 유효성 검증 오류: 1004가 발생했습니다. 지금 무엇을 할 수 있습니까?
{:#cis-faq-dns-validation-error}
{: faq}

페이지 규칙이 작동하려면 DNS가 구역을 분석해야 합니다. 따라서 구역에 대한 프록싱 DNS 레코드가 필요합니다. 

## 루트 레코드에 CNAME을 추가할 수 있습니까?
{:#cis-faq-add-cname-root-record}
{: faq}

예. IBM CIS는 "CNAME 플래트닝"이라는 기능을 지원하며, 이를 사용하면 사용자들이 CNAME을 루트 레코드로 추가할 수 있습니다. 권한 있는 DNS 서버는 CNAME 대상의 레코드를 열거하고 CNAME 대신 이 레코드로 응답하여 사용자가 도메인의 루트에서 CNAME을 구성한 사실을 효과적으로 숨깁니다.

## 기본 상태 검사 제한시간은 무엇입니까?
{:#cis-faq-default-health-check-timeout}
{: faq}

무료 평가판 및 표준 플랜의 기본 상태 점검 제한시간은 60초입니다.

## 비HTTP/HTTPS 트래픽에 대해 상태 검사를 구성할 수 있습니까?
{:#cis-faq-health-check-non-http-traffic}
{: faq}

아니오, HTTP/HTTPS로만 구성할 수 있습니다.

## 비HTTP/HTTPS 트래픽에 대해 GLB를 구성할 수 있습니까?
{:#cis-faq-glb-non-http-traffic}
{: faq}

아니오, HTTP/HTTPS로만 구성할 수 있습니다.

## 오리진 풀에서 모든 오리진을 사용 안함으로 설정하면 전체 오리진 풀 자체가 사용 안함으로 설정됩니까?
{:#cis-faq-disabling-origins-disable-origin-pool}
{: faq}

예, 오리진 풀이 로드 밸런서에서 사용되고 있는 경우 트래픽은 다음 최상위 우선순위 풀 또는 폴백 풀로 라우팅됩니다.

## Kubernetes Ingress에 오류가 있는 경우 무엇을 해야 합니까?
{:#cis-faq-kubernetes-ingress-error}
{: faq}

Kubernetes Ingress의 호스트 이름은 소문자로 된 영숫자, '-' 또는 '.'로 구성되어야 하고 영숫자로 시작하고 끝나야 합니다. 로드 밸런서 이름에 `_`을 사용하면 허용된 경우에도 Kubernetes 클러스터에 ingress 오류가 발생할 수 있습니다. Kubernetes 클러스터에 문제가 발생하지 않도록 로드 밸런서 이름에 `-`를 사용하지 않는 것이 좋습니다.

## Edge Functions 조치를 저장하는 중에 502 오류가 발생하면 무엇을 해야 합니까?
{:#cis-faq-502-error}
{: faq}

[IBM 지원 센터](/docs/infrastructure/cis?topic=cis-getting-help-and-support)에 문의하여 저장하려고 했던 스크립트를 제공하십시오.