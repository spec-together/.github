# spectogether : SeSAC 2024

<!--
초기, 빈 프로젝트에 알맞게 config.json을 작성하였습니다.
각자 개발해 나아가면서 config.json에 변경사항이 생길 경우
README.md에 반드시 적용해주셔야 합니다.

gitignore에 포함되어 있어, 공유가 안되면 관리가 되지 않습니다.

참고로, gitignore은 window, macOS, linux, node, react를 사용하는 환경에 알맞게 작성되어 있습니다.

추가하실 사항이 있다면 상의 후 수정 부탁드립니다.
-->

## 👥 팀원 소개

#### Mentor : [나동빈 강사님](https://github.com/ndb796)

- Team Leader : [박경운](https://github.com/kyeoungwoon)
- Team Member : [최재원](https://github.com/JayOneC)

## 🌟 **프로젝트 개요**

**Spectogether**는 세상의 모든 취업 준비생들을 위한 종합 지원 플랫폼입니다.  
공모전, 자격증 정보를 한곳에 모아 제공하며, **스터디 그룹 생성**을 손쉽게 돕습니다.  
또한, **매너 온도**와 **스펙 레벨** 시스템을 통해 사용자 스스로 객관적인 위치를 파악하고 발전할 수 있도록 지원합니다.


## 💡 **주요 기능**
1. **공모전 및 자격증 정보 제공**
   - 최신 정보 업데이트로 효율적인 취업 준비 가능.
3. **스터디 그룹 생성 지원**  
   - 관심 분야별로 맞춤 스터디를 쉽게 구성.
4. **매너 온도 시스템**  
   - 커뮤니티 내 신뢰도를 나타내는 지표.
5. **스펙 레벨 제도**  
   - 나의 현재 위치를 객관적으로 파악하고 성장 방향 설정.
  
## 🚀 **Spectogether와 함께 취업 성공을 향해!**
준비된 당신에게 더 나은 길을 열어드립니다. 🙌

## ⚙️ Tech Spec

- **Frontend**: React + tailwind
- **Backend**: Node.js + express.js
- **Deploy** : NGINX + Docker
- **CI/CD**: GitHub Actions

## 🗂️ Git Strategy: GitHub Flow

- **`main`**: 항상 안정적인 상태를 유지하는 브랜치입니다.
- **`develop`**: `feature` 브랜치에서 변경된 사항들을 1차적으로 합치는 공간입니다.  
  `main` 브랜치에 PR하기 전, 마지막 체크 단계로 사용됩니다.
- **`feature`**: 각 팀원이 새로운 기능을 자유롭게 구현하는 공간입니다.
