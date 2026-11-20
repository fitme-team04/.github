<div align="center">

# Fit Me

**사진 한 장으로 먼저 입어 보는 3D 피팅룸**

MS AI School 1차 프로젝트 4팀 · 2026.11.04 ~ 11.18 · 6명

<a href="https://github.com/fitme-team04/Fit-Me-Team-04">
  <img src="https://raw.githubusercontent.com/fitme-team04/Fit-Me-Team-04/main/docs/images/demo.gif" alt="Fit Me 시연" width="720">
</a>

</div>

## 무엇을 만들었나요

온라인에서 옷을 사면 "내 사이즈인데 안 맞는" 일이 자주 생깁니다. Fit Me는 사기 전에 내 몸으로 먼저 입어 봅니다.

1. 전신 사진 한 장과 키·몸무게로 **내 몸 그대로의 3D 모델**을 만듭니다.
2. 고른 옷을 그 몸에 **입혀서** 3D로 돌려 봅니다.
3. 몸 둘레와 옷 실측을 비교해 **"입을 수 있어요 / 작아요 / 커요"** 를 알려 줍니다.

## 프로젝트

| | |
|---|---|
| 코드 | **[Fit-Me-Team-04](https://github.com/fitme-team04/Fit-Me-Team-04)** : 웹, 3D 신체·의류 서버, ML, 인프라 코드를 파트별 폴더로 정리 |
| 구조 | [서비스 구조와 파트별 진행](https://github.com/fitme-team04/Fit-Me-Team-04#구조) · [인프라 아키텍처 그림](https://github.com/fitme-team04/Fit-Me-Team-04/tree/main/architecture/infra) |
| 인프라 | [인프라·DevOps 정리](https://github.com/fitme-team04/Fit-Me-Team-04/blob/main/docs/infra/README.md) · [손댄 것 전체 목록](https://github.com/fitme-team04/Fit-Me-Team-04/blob/main/docs/infra/inventory.md) |

<div align="center">
<a href="https://github.com/fitme-team04/Fit-Me-Team-04/tree/main/architecture/infra">
  <img src="https://raw.githubusercontent.com/fitme-team04/Fit-Me-Team-04/main/architecture/infra/structure-2-all.png" alt="Fit Me 아키텍처" width="820">
</a>
</div>

## 기술

| 분야 | 사용 기술 |
|---|---|
| 웹 | FastAPI, HTML/JS, model-viewer, Redis, nginx |
| 3D | SAM 3D Body, MoGe, Blender, Docker + NVIDIA Container Toolkit |
| ML | Azure Machine Learning (Designer, 관리형 온라인 엔드포인트) |
| 데이터 | Azure SQL, Blob Storage |
| 인프라 | Azure VM (T4 GPU), VNet·NSG, Key Vault, Container Registry, Terraform, GitHub Actions (OIDC), Azure Monitor |

## 팀

<table>
  <tr>
    <td align="center"><a href="https://github.com/kim-ye-jun"><img src="https://github.com/kim-ye-jun.png?size=100" width="100" alt="김예준"><br><b>김예준</b></a><br>3D</td>
    <td align="center"><a href="https://github.com/Gwone"><img src="https://github.com/Gwone.png?size=100" width="100" alt="김평권"><br><b>김평권</b></a><br>데이터</td>
    <td align="center"><a href="https://github.com/itmina04"><img src="https://github.com/itmina04.png?size=100" width="100" alt="박미나"><br><b>박미나</b></a><br>데이터 · ML</td>
    <td align="center"><a href="https://github.com/an2026seong"><img src="https://github.com/an2026seong.png?size=100" width="100" alt="박상호"><br><b>박상호</b></a><br>프론트</td>
    <td align="center"><a href="https://github.com/kradipa"><img src="https://github.com/kradipa.png?size=100" width="100" alt="손의성"><br><b>손의성</b></a><br>인프라</td>
    <td align="center"><a href="https://github.com/yys0714-max"><img src="https://github.com/yys0714-max.png?size=100" width="100" alt="유영서"><br><b>유영서</b></a><br>ML</td>
  </tr>
</table>
