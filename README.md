## Related Repositories

<table>
<thead>
  <tr>
    <th>플랫폼</th>
    <th><a href="https://github.com/K-PaaS/cp-deployment">컨테이너 플랫폼</a></th>
    <th>&nbsp;&nbsp;&nbsp;<a href="https://github.com/K-PaaS/sidecar-deployment.git">사이드카</a>&nbsp;&nbsp;&nbsp;</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td align="center">포털</td>
    <td align="center"><a href="https://github.com/K-PaaS/cp-portal-release">CP 포털</a></td>
    <td align="center">-</td>
  </tr>
  <tr>
    <td rowspan="8">Component <br>/서비스</td>
    <td align="center"><a href="https://github.com/K-PaaS/cp-portal-ui">Portal UI</a></td>
    <td align="center"><a href="https://github.com/K-PaaS/sidecar-portal-ui">Portal UI</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/K-PaaS/cp-portal-api">Portal API</a></td>
    <td align="center"><a href="https://github.com/K-PaaS/sidecar-portal-api">Portal API</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/K-PaaS/cp-portal-common-api">Common API</a></td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/K-PaaS/cp-metrics-api">Metric API</a></td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/K-PaaS/cp-terraman">Terraman API</a></td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/K-PaaS/cp-catalog-api">🚩Catalog API</a></td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/K-PaaS/cp-chaos-api">Chaos API</a></td>
    <td align="center"></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/K-PaaS/cp-chaos-collector">Chaos Collector API</a></td>
    <td align="center"></td>
  </tr>
</tbody></table>

<i>🚩 You are here.</i>

<br>

## K-PaaS 컨테이너 플랫폼 Catalog API
K-PaaS 컨테이너 플랫폼 포털 내 Helm 기반의 Catalog 관리 기능을 제공합니다.
- [시작하기](#시작하기)
    - [컨테이너 플랫폼 Catalog API 빌드 방법](#컨테이너-플랫폼-catalog-api-빌드-방법)
- [문서](#문서)
- [개발 환경](#개발-환경)
- [라이선스](#라이선스)

<br>

## 시작하기
K-PaaS 컨테이너 플랫폼 Catalog API가 수행하는 애플리케이션 관리 작업은 다음과 같습니다.
- Repository 관리
- Chart 관리
- Release 관리

#### 컨테이너 플랫폼 Catalog API 빌드 방법
K-PaaS 컨테이너 플랫폼 Catalog API 소스 코드를 활용하여 로컬 환경에서 빌드가 필요한 경우 다음 명령어를 입력합니다.
```
$ go build
```

<br>

## 문서
- 컨테이너 플랫폼 활용에 대한 정보는 [K-PaaS 컨테이너 플랫폼](https://github.com/K-PaaS/container-platform)을 참조하십시오.

<br>

## 개발 환경
K-PaaS 컨테이너 플랫폼 Catalog API의 개발 환경은 다음과 같습니다.

| Situation                   | Version |
|-----------------------------| ------- |
| go                          | 1.21    |
| helm                        | v3.13.3 |
| gofiber/fiber               | v2.52.5 |
| gofiber/contrib/jwt         | v1.0.10 |
| gofiber/contrib/fiberi18n   | v2.0.2  |
| gofiber/swagger             | v1.0.0  |
| hashicorp/vault-client-go   | v0.4.3  |
| k8s.io/kubectl              | v0.29.2 |
| spf13/viper                 | v1.18.2 |

<br>

## 라이선스
K-PaaS 컨테이너 플랫폼 Catalog API는 [Apache-2.0 License](http://www.apache.org/licenses/LICENSE-2.0)를 사용합니다.