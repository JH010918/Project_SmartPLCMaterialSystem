# PLC 기반 소재 판별형 자동 입출고 시스템
Q PLC를 활용하여 컨베이어 이송 중 금속·비금속 소재 판별 및 적재 자동화 시스템 구현하기 위한 시스템입니다.
## 📌 프로젝트 개요
- 수행 기간 : 2026.02.04 ~ 2026.02.09
- 팀원 : 김세일
- 주요 기능 :
  - 금속/비금속 소재 판별
  - 선입, 선출
  - 지정한 위치 상태 점검
  - HMI를 통한 시각적 피드백
## 🔧 기술 스택
| 기술 | 설명 |
|----------|------------|
| PLC | 자동화 제어 및 시스템 로직 구현 |
| GX Works2 | Ladder 기반 제어 프로그램 작성 |
| GT Designer3 | HMI 사용자 인터페이스 설계 |
<h2>🛠 개발 환경 (Development Environment)</h2>

<table width="100%">
<tr>
<td width="50%" valign="top">

<h3>🔧 Hardware</h3>

<b>PLC 시스템</b><br>
- Mitsubishi Q03UDV (Q-Series)<br>
- Q-Series Base Unit<br><br>

<b>I/O 및 모션 모듈</b><br>
- 디지털 입력 : QX40<br>
- 디지털 출력 : QY10<br>
- 아날로그 입출력 : Q64AD2DA<br>
- 위치결정 모듈 : QD77MS2<br><br>

<b>모션 제어 시스템</b><br>
- 서보 앰프 : MR-J4-10B<br>
- 서보 모터 : HG-KR13J<br>
- 1축 볼스크류 구동 구조<br><br>

<b>공압 시스템</b><br>
- 공급 / 가공 / 스토퍼 / 흡착 실린더 적용<br><br>

<b>센서</b><br>
- 근접 센서 : CR18-8DN<br>
- 금속 감지 센서 : PRL18-8DN<br>

</td>

<td width="50%" valign="top">

<h3>💻 Software</h3>

<b>PLC 프로그래밍</b><br>
- GX Works2 (v1.631H)<br><br>

<b>서보 파라미터 설정</b><br>
- MR Configurator2 (v1.165X)<br><br>

<b>HMI 설계</b><br>
- GT Designer3 (v1.2565)<br><br>

<b>제어 로직 구현</b><br>
- Ladder Logic 기반 제어 프로그램 설계<br>
- 위치 제어 및 모션 제어 통합 구성<br>

</td>
</tr>
</table>

## 구현 상세
###1️⃣ 
