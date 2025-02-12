# Meta은행(2024년 메타넷 클라우드 인프라 엔지니어 양성과정 최종 프로젝트)

## Meta은행

## 프로젝트 개요
최근 급리 하락으로 인해 대출 및 부동산 거래 수요가 증가하면서, 관련 금융 서비스에 대한 이용자 요구가 확대되고 있습니다. <br>
이에 따라 ㅇㅇ은행은 기존 모놀리식(Monolithic) 아키텍처 기반의 금융 서비스를 퍼블릭 클라우드 기반의 마이크로서비스 아키텍처(MSA)로 전환하는 프로젝트를 추진하였습니다. <br>

주요 목표 및 구현 내용 <br>
	1.	MSA 기반 서비스 전환 <br>
기존의 모놀리식 서비스 구조를 MSA로 마이그레이션하여 확장성과 유지보수성을 개선하였습니다. 이를 통해 개별 서비스 단위로 독립적인 배포 및 운영이 가능해지고, 서비스 장애 발생 시 영향 범위를 최소화할 수 있도록 설계하였습니다. <br>
	2.	재해 복구(DR) 체계 구축 <br>
온프레미스 환경에서 DB 백업 시스템을 구축하여 안정적인 재해 복구 체계를 마련하였습니다. 이를 통해 장애 발생 시 신속한 데이터 복구가 가능하며, 금융 서비스의 연속성을 보장할 수 있도록 구성하였습니다. <br>
	3.	테스트 환경 구축 <br>
백업된 DB를 활용하여 테스트 환경을 구성함으로써 시스템의 유연성과 안정성을 확보하였습니다. 이를 통해 신규 기능 개발 및 서비스 업데이트 시 운영 환경에 미치는 영향을 사전에 검증할 수 있도록 하였습니다. <br>

본 프로젝트를 통해 ㅇㅇ은행은 보다 안정적이고 확장 가능한 금융 서비스를 제공할 수 있으며, 급변하는 금융 환경에 신속하게 대응할 수 있는 기반을 마련하였습니다. <br>

<img width="1020" alt="Image" src="https://github.com/user-attachments/assets/e1e03de8-2111-42ae-a697-f7e02ce136b5" />

## Architecture(기존 Monolithic)
![image](https://github.com/user-attachments/assets/0c73905a-57b8-48bd-a394-d501642ed4fe)

## Architecture(MSA 컨설팅 설계)
![image](https://github.com/user-attachments/assets/0c73905a-57b8-48bd-a394-d501642ed4fe)

## Architecture(GitOps 기반 CI/CD 및 DR 구축​)
![image](https://github.com/user-attachments/assets/0c73905a-57b8-48bd-a394-d501642ed4fe)

## Architecture(온프레미스 DR 전략​)
![image](https://github.com/user-attachments/assets/0c73905a-57b8-48bd-a394-d501642ed4fe)

## Architecture(온프레미스 K8S 다중 클러스터 구축​​)
![image](https://github.com/user-attachments/assets/0c73905a-57b8-48bd-a394-d501642ed4fe)

<br />

## Preview

### 회원가입 및 로그인
<!--
![회원가입](https://github.com/user-attachments/assets/52c1ad5c-e2ba-4eed-a3c1-534f1a82eb9b)
-->
<br/>

### 전세 매물 조회
<!--
![회원가입](https://github.com/user-attachments/assets/52c1ad5c-e2ba-4eed-a3c1-534f1a82eb9b)
-->
<br/>

### 사용자 위치 기반 은행 및 부동산 정보 제공
<!--
![회원가입](https://github.com/user-attachments/assets/52c1ad5c-e2ba-4eed-a3c1-534f1a82eb9b)
-->
<br/>

### 금융 상식을 기르기 위한 퀴즈
<!--
![회원가입](https://github.com/user-attachments/assets/52c1ad5c-e2ba-4eed-a3c1-534f1a82eb9b)
-->
<br/>

## Development_Skills

#### FRONT-END

<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white"/></a>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white"/></a>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white"/></a>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=white"/></a>
<img src="https://img.shields.io/badge/MUI-007FFF?style=flat&logo=mui&logoColor=white"/>

#### BACK-END

<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat&logo=Spring Boot&logoColor=white"/> <a>
<img src="https://img.shields.io/badge/Java-007396?style=flat&logo=Java&logoColor=white"/> <a>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white"/> <a>
<img src="https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white"/> <a> 
<img src="https://img.shields.io/badge/postman-FF6C37?style=flat&logo=postman&logoColor=white"/> <a>


#### AI
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white"/> </a>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=Pandas&logoColor=white"/> </a>
<img src="https://img.shields.io/badge/Numpy-013243?style=flat&logo=Numpy&logoColor=white"/> </a>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=OpenCV&logoColor=white"/> </a>
<img src="https://img.shields.io/badge/keenetic-009EE2?style=flat&logo=keenetic&logoColor=white"/> 
</a>
<img src="https://img.shields.io/badge/pytorch-EE4C2C?style=flat&logo=pytorch&logoColor=white"/> </a>
<img src="https://img.shields.io/badge/huggingface-FFD21E?style=flat&logo=huggingface&logoColor=black"/> </a>
<img src="https://img.shields.io/badge/scikitlearn-F7931E?style=flat&logo=scikitlearn&logoColor=white"/> </a>

#### DB
<img src="https://img.shields.io/badge/postgresql-4169E1?style=flat&logo=postgresql&logoColor=white"/></a>
<img src="https://img.shields.io/badge/supabase-3FCF8E?style=flat&logo=supabase&logoColor=white"/></a>
<img src="https://img.shields.io/badge/sqlite-003B57?style=flat&logo=sqlite&logoColor=white"/></a>

#### CI/CD

<img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=Git&logoColor=white"/></a>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=Jenkins&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=flat&logo=Amazon EC2&logoColor=white"/></a>
<img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Filezilla-BF0000?style=flat&logo=filezilla&logoColor=white"/></a> 

# 프로젝트 상세

## 기간
**25.02.10~25.02.20**

