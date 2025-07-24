### 1. 프로젝트 소개
#### 1.1. 개발배경 및 필요성
대한민국의 여행 문화는 서울, 부산, 제주 등 특정 대도시에 집중되어 있으며, 상대적으로 지방 여행지에 대한 정보는 부족합니다. 특히 소규모 도시나 잘 알려지지 않은 지역은 방문자 수가 적어 자연스러운 홍보가 어렵고, 사용자 간의 공유도 활발하지 않습니다. 이에 따라, 사용자 스스로 여행지를 개척하고, 공유하고, 즐길 수 있는 참여형 여행 플랫폼의 필요성이 대두되었습니다.
<br/>
#### 1.2. 개발목표 및 주요내용
두도지는 일상 속에서도 여행의 감각을 느낄 수 있는 플랫폼을 목표로 하며, 여행 중에는 물론이고 평소에도 지도를 밝히고 핀을 찍으며 나만의 이야기를 기록하고 공유할 수 있도록 설계되었습니다. 주요 기능은 다음과 같습니다:
* 지도를 밝히는 탐험 요소
* 특정 지역의 랜드마크 정복
* 핀을 통한 여행 기록 및 피드 공유
* 친구의 여행을 구경하며 정보 공유

#### 1.3. 세부내용 
* 사용자는 안개로 가려진 지도 위를 실제 이동하며 탐험하고, 해당 지역이 밝혀지면 핀을 남겨 여행 일기를 작성할 수 있습니다.
* 랜드마크에 도달 시 특별한 효과와 함께 지도 영역이 크게 개방됩니다.
* 친구 기능을 통해 서로의 여행 피드를 구경하고, 관심 지역에 대한 정보를 얻을 수 있습니다.
* 업적, 일일 퀘스트 등의 시스템을 통해 지속적인 사용을 유도합니다.

#### 1.4. 기존 서비스(상품) 대비 차별성
* 단순한 관광지 정보 제공을 넘어, 사용자 스스로 지도를 밝히며 게임처럼 즐기는 여행 플랫폼
* 일회성 이용이 아닌, 일상 속 탐험과 기록을 지속적으로 유도
* SNS 요소 + 위치 기반 게임화된 구조로, 기존 플랫폼과 확연히 차별화
<br/>

#### 1.5. 사회적가지 도입 계획
* 지역 소도시에 대한 관심을 유도해 지방 경제 및 관광 활성화
* 이용자 간의 자발적 공유로 지속 가능한 지역 홍보 구조 구축
* 일상 속 건강한 이동과 탐험을 장려함으로써 웰빙 증진 기여
<br/>


### 2.상세설계
#### 2.1. 시스템 구성도
<img width="515" height="479" alt="dudoji-structure" src="https://github.com/user-attachments/assets/f2dc1259-4896-4cc3-8d95-b65dc087aead" />


#### 2.3. 사용기술
| | 이름                  |
|:--:|:---------------------:|
|Backend| Spring Boot           |
|Frontend| Android Studio-kotlin |
|Database| PostgreSQL            |
|Deployment| AWS EC2               |
|Design| Figma                 |
|Collaboration|GitHub, Notion, Discord, Slack|
<br/>


### 3. 개발결과
#### 3.1. 전체시스템 흐름도
<img width="616" height="476" alt="dudoji-flow" src="https://github.com/user-attachments/assets/a9d04c64-970a-4cec-8b6c-2578c6e97b48" />


#### 3.4. 디렉토리 구조
<img width="644" height="469" alt="dudoji-android-directory-structure" src="https://github.com/user-attachments/assets/fda35730-2ab2-44b1-8f7b-31c4efea6b39" />
<img width="641" height="491" alt="dudoji-backend-directory-structure" src="https://github.com/user-attachments/assets/0d6f532a-2eb4-4f0b-865f-04a99206fec0" />


### 4. 설치 및 사용 방법
**필요 패키지**
- 위의 사용 기술 참고

```bash
  git clone https://github.com/team-dudoji/dudoji-backend.git
  cd dudoji-backend
  ./gradlew build
  java -jar build/libs/*.jar
```

```bash
  git clone https://github.com/team-dudoji/dudoji-android.git
  cd dudoji-android.git
  ./gradlew assembleDebug
```
<br/>

### 6. 팀 소개
<table>
<tr>
    <td align="center">
        기획자
    </td>
    <td align="center">
        디자이너
    </td>
    <td align="center">
        개발자
    </td>
    <td align="center">
        개발자
    </td>
    <td align="center">
        개발자
    </td>
  </tr>
  <tr>
    <td align="center" width="200px">
      <a href="https://github.com/team-dudoji" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/194190710?s=96&v=4" alt="천영현 프로필" />
      </a>
    </td>
    <td align="center" width="200px">
      <a href="https://github.com/team-dudoji" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/194190710?s=96&v=4" alt="김수현 프로필" />
      </a>
    </td>
    <td align="center" width="200px">
      <a href="https://github.com/dev-yunseong" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/88422717?v=4" alt="정윤성 프로필" />
      </a>
    </td>
    <td align="center" width="200px">
      <a href="https://github.com/Vackam" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/53655740?v=4" alt="이요환 프로필" />
      </a>
    </td>   
    <td align="center" width="200px">
      <a href="https://github.com/chaeminseok1234" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/181972752?v=4" alt="채민석 프로필" />
      </a>
    </td>   
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/team-dudoji" target="_blank">
        천영현
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/team-dudoji" target="_blank">
        김수현
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/dev-yunseong" target="_blank">
        정윤성
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Vackam" target="_blank">
        이요환
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/chaeminseok1234" target="_blank">
        채민석
      </a>
    </td>
  </tr>
</table>

<br/>
