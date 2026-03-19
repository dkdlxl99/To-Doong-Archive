# 🐣 투둥! 게이미피케이션 습관 관리 서비스

<div align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white">
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white">
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white">
  <br/><br/>
  <p>🎮 할 일을 완료하고, 나만의 캐릭터를 성장시키는 즐거움! 🎮</p>
</div>

<br/>

<div align="center">
  <img src="https://github.com/user-attachments/assets/041a1669-bc62-4a6b-a65a-de2c75e00391" alt="Main Screen" width="800" style="border-radius: 10px;"/>

  <br/><br/>
  <p><i>"매일 조금씩 자라나는 습관, 더 나은 내일을 준비해 볼까요?"</i></p>
</div>

<br/>

## 1. 프로젝트 소개

### [기획 의도]
> **"왜 할 일 관리는 지루해야 할까요?"**
>
> 매일 반복되는 루틴과 할 일 관리에 지친 사용자들에게 '성취감'과 '재미'를 동시에 제공하기 위해 기획되었습니다.<br>
> 사용자가 할 일을 완료하면 경험치(XP)와 골드를 획득하고, 이를 통해 알에서 아기, 성체로 캐릭터를 진화시킬 수 있습니다.<br>
> 또한, 모은 재화로 가구를 구매하여 나만의 공간을 꾸미는 인터랙티브 요소를 도입하여 지속적인 앱 사용 동기를 부여합니다.<br>
> 단순한 투두리스트를 넘어, 사용자의 성장이 곧 캐릭터의 성장으로 이어지는 **게이미피케이션(Gamification)** 서비스입니다.

### [주요 특징]
- **성장 시스템**: 투두 완료 시 경험치 획득 및 캐릭터 진화 (알 -> 아기 -> 성체 -> 캐릭터 꾸미기)
- **방 꾸미기**: 상점에서 가구를 구매하고 자유롭게 배치하는 인터랙티브 UI
- **강력한 루틴**: 요일별/주간/월간 반복 설정 및 상황별(기상 후, 출근 길 등) 시간 설정 지원
- **쉬어가기 모드**: 아프거나 여행 갈 때, 스트릭(Streak)이 끊기지 않도록 루틴 일시 정지 기능
- **통계 분석**: 히트맵(잔디 심기)과 레이더 차트를 통한 나의 능력치(건강, 공부 등) 분석

<br>

## 2. 팀원 소개 및 역할

| **🐶 팀장** | **🐱 팀원** |
| :------: | :------: |
| <img src="https://github.com/user-attachments/assets/f406f5b7-0fae-44c9-9f77-93f7099baebd" height=150 width=150> | <img src="https://github.com/user-attachments/assets/72069b1d-e87e-4916-9eae-aebd5e446fe9" height=150 width=150> |
| **[@정선우](https://github.com/sunwoo9801)** | **[@변다혜](https://github.com/dkdlxl99)** |
| **기획 & UI 디자인** | **코어 로직 & DB 설계** |
| **기획:** 서비스 전반 기획 및 정책 수립<br>**기능:** 할 일 생성(Create), 진화 쉐이크 애니메이션 구현<br>**UI 구현:** 프롤로그(온보딩) 및 캘린더 UI 렌더링<br>**인증:** Firebase Auth 기본 계정 연동<br>**디자인:** 캐릭터(투둥이) 및 가구 에셋 디자인, 목업 설계 | **DB 설계:** Firestore NoSQL 구조 설계 및 전체 연동<br>**핵심 기능:** 할 일 RUD 및 루틴 CRUD 전체 로직 개발<br>**게임 시스템:** 캐릭터 진화 알고리즘, 상점 및 인벤토리 시스템 구현<br>**부가 기능:** Google 소셜 로그인, 쉬어가기(Rest) 예외 처리 로직<br>**데이터:** Radar Chart 및 히트맵 등 전체 통계 시스템 구축 |

<br>

## 3. 기술 스택

### **Frontend**
| 분류 | 기술 스택 |
| :--: | :--- |
| **Framework** | <img src="https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white"/> <img src="https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white"/> |
| **UI Library** | `flutter_slidable` (스와이프 액션), `table_calendar` (캘린더), `fl_chart` (통계 차트), `tutorial_coach_mark` (튜토리얼) |
| **State Mgt** | `StreamBuilder` (Real-time updates), `StatefulWidget` |

### **Backend & Database**
| 분류 | 기술 스택 |
| :--: | :--- |
| **Platform** | <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=white"/> |
| **Auth** | Firebase Authentication (Email, Google) |
| **Database** | Cloud Firestore (NoSQL) |

### **Collaboration**
| 분류 | 툴 |
| :--: | :--- |
| **Tools** | <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"/> <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white"/> <img src="https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white"/> |

<br>

## 4. 주요 기능 및 스크린샷

### 4-1. 간편한 시작 및 온보딩
<table>
  <tbody>
    <tr>
      <td align="center" width="300px">
        <img src="https://github.com/user-attachments/assets/3b1fc7a4-6829-4a42-87b2-390ec6f43c95" alt="회원가입 및 온보딩" />
      </td>
      <td>
        <strong>사용자 친화적 인증 및 데이터 초기화</strong>
        <ul>
          <li><strong>안전한 인증 플로우:</strong> Firebase Auth를 활용한 이메일/소셜 로그인 및 비밀번호 재설정 기능 구현</li>
          <li><strong>초기 데이터 자동 세팅:</strong> 신규 회원가입 시 Firestore를 통해 기본 캐릭터(알) 상태와 웰컴 루틴 데이터를 자동으로 DB에 세팅(Seeding)</li>
          <li><strong>코치마크 온보딩:</strong> <code>TutorialCoachMark</code> 패키지를 연동하여, 첫 진입 시 핵심 액션(투두 추가, 완료 체크 등)을 직관적으로 학습하도록 유도</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

### 4-2. 투두 등록 및 보상 시스템
<table>
  <tbody>
    <tr>
      <td align="center" width="300px">
        <img src="https://github.com/user-attachments/assets/9f933f5a-0b03-4900-921c-186ff175f7be" alt="투두 완료 및 보상" />
      </td>
      <td>
        <strong>데이터 무결성이 보장된 실시간 보상 로직</strong>
        <ul>
          <li><strong>실시간 상태 동기화:</strong> <code>StreamBuilder</code>를 활용해 체크박스 클릭 즉시 경험치(XP)와 골드가 차오르는 반응형 UI 구축</li>
          <li><strong>트랜잭션(Transaction) 처리:</strong> 다중 클릭 등 동시성 문제(Race Condition)를 방지하기 위해, Firestore 트랜잭션을 적용하여 투두 상태와 캐릭터 보상 데이터를 안전하게 업데이트</li>
          <li><strong>마이크로 인터랙션:</strong> 목표 달성 순간 <code>HapticService</code>를 통한 진동 피드백과 화려한 커스텀 보상 다이얼로그를 띄워 사용자 성취감 극대화</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

### 4-3. 캐릭터 진화 및 육성
<table>
  <tbody>
    <tr>
      <td align="center" width="300px">
        <img src="https://github.com/user-attachments/assets/050e2fe8-5e24-4686-9cd9-e69fadd2da5e" alt="캐릭터 진화" />
      </td>
      <td>
        <strong>조건부 렌더링 기반 동적 캐릭터 시스템</strong>
        <ul>
          <li><strong>동적 진화 알고리즘:</strong> 누적된 경험치(XP)가 <code>GameRules</code>에 정의된 임계치 도달 시 알 → 아기 → 성체로 진화하는 이벤트 로직 개발</li>
          <li><strong>실시간 이미지 합성:</strong> <code>Stack</code> 위젯을 활용해 장착한 옷, 모자, 등 장식 등 다중 레이어를 실시간으로 합성하여 캐릭터 렌더링</li>
          <li><strong>인터랙티브 UI 피드백:</strong> 진화 임계치 도달 시 커스텀 애니메이션(Shake 효과)과 축하 팝업을 제공하고, 캐릭터 이름을 직접 지어주는 기능을 통해 유저의 애착도 상승 유도</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

### 4-4. 상점 및 인터랙티브 방 꾸미기
<table>
  <tbody>
    <tr>
      <td align="center" width="300px">
        <img src="https://github.com/user-attachments/assets/842168ec-e342-4423-8648-ef651a26e158" alt="방 꾸미기" />
      </td>
      <td>
        <strong>렌더링 최적화가 적용된 Drag & Drop</strong>
        <ul>
          <li><strong>상대 좌표 배치 시스템:</strong> <code>GestureDetector</code>를 활용해 기기 화면 비율(<code>constraints.maxWidth</code>)에 비례하는 상대 좌표(0.0~1.0)로 가구 이동 및 DB 실시간 저장</li>
          <li><strong>프레임 드랍 방지(최적화):</strong> 드래그 시 발생하는 과도한 리렌더링을 막기 위해 배경과 개별 가구에 <code>RepaintBoundary</code>를 적용하고, 제스처 스로틀링(Throttling)을 도입해 60fps 확보</li>
          <li><strong>안전한 인벤토리:</strong> 아이템 구매 시 골드 차감과 보유 배열(<code>arrayUnion</code>) 추가를 단일 작업으로 묶어 에러 발생 시 롤백되도록 구현</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

### 4-5. 체계적인 루틴 관리 및 생성 (Core Scheduler)
<table>
  <tbody>
    <tr>
      <td align="center" width="300px">
        <img src="https://github.com/user-attachments/assets/37563cfb-96c0-4212-9dcc-2a455b1d8999" alt="루틴 생성" />
      </td>
      <td>
        <strong>Blueprint 패턴 기반의 다차원 스케줄링 시스템</strong>
        <ul>
          <li><strong>일간(Daily): 라이프사이클 기반 타임라인</strong>
            <ul>
              <li>단순 시간 정렬을 넘어 '기상 후', '출근 길', '취침 전' 등 사용자의 생활 문맥에 가중치(<code>sortTime</code>)를 부여한 <strong>Contextual Sorting 알고리즘</strong> 적용</li>
            </ul>
          </li>
          <li><strong>주간(Weekly): 유연한 목표 달성 트래킹</strong>
            <ul>
              <li>'주 N회 수행' 루틴을 위해 당해 주차의 월요일부터 일요일까지의 데이터를 실시간 집계하여 <strong>달성률 캡슐 UI</strong>로 시각화</li>
            </ul>
          </li>
          <li><strong>월간(Monthly): 장기 습관 형성 가이드</strong>
            <ul>
              <li>월 단위 반복 루틴을 위해 Firestore <code>Timestamp</code> 범위 쿼리를 활용하여 캘린더의 각 셀과 루틴 청사진을 <strong>동적으로 매칭(Instantiation)</strong>하는 로직 구현</li>
            </ul>
          </li>
          <li><strong>데이터 아키텍처 최적화:</strong> 루틴을 매일 생성하지 않고 '규칙(Blueprint)' 데이터로 관리하여 <strong>서버 부하와 스토리지 소모를 90% 이상 절감</strong></li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

### 4-6. 쉬어가기 모드 (Streak 보호)
<table>
  <tbody>
    <tr>
      <td align="center" width="300px">
        <img src="https://github.com/user-attachments/assets/6c89bdd0-4725-4bb4-b07d-d92e772a70a2" alt="쉬어가기 모드" />
      </td>
      <td>
        <strong>사용자 이탈을 막는 유연한 상태 관리</strong>
        <ul>
          <li><strong>데이터 보호 알고리즘:</strong> 루틴 원본을 삭제하지 않고 <code>restStartDate</code> ~ <code>restEndDate</code> 기간을 DB에 저장하여, 해당 기간 동안만 일시 비활성화하는 로직 개발</li>
          <li><strong>스트릭(Streak) 예외 처리:</strong> 연속 달성일수(잔디) 계산 시, 쉬는 기간은 미달성으로 체크되지 않도록 필터링 쿼리 적용</li>
          <li><strong>스와이프 인터랙션:</strong> <code>flutter_slidable</code>을 커스텀하여 항목을 밀어서 상태를 변경(휴식/깨우기/삭제)하는 직관적인 UX 제공</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

### 4-7. 통계 분석 및 데이터 시각화
<table>
  <tbody>
    <tr>
      <td align="center" width="300px">
        <img src="https://github.com/user-attachments/assets/731912ca-1b90-4ca7-af64-7af3a298df57" alt="통계 및 리포트" />
      </td>
      <td>
        <strong>데이터 시각화를 통한 실시간 리포트</strong>
        <ul>
          <li><strong>다차원 능력치 분석:</strong> <code>fl_chart</code>를 커스텀하여 카테고리별(건강, 공부 등) 누적 달성도를 RPG 게임 스탯 창 형태의 방사형(Radar) 차트로 렌더링</li>
          <li><strong>성장 히트맵 캘린더:</strong> 날짜별 투두 완료 개수를 그룹핑하고, 일일 달성률에 따라 캐릭터 표정 아이콘(😴/😀/🥰)이 다르게 출력되는 커스텀 알고리즘 구현</li>
          <li><strong>비동기 통계 산출:</strong> <code>Stream</code>(실시간 갱신)과 <code>Future</code>(1회성 연산)를 조합하여 주간 획득 XP, 연속 달성일 등의 데이터를 지연 없이 로드</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

<br>


## 5. 데이터베이스 구조 (ERD)

<div align="center">
  <img src="https://github.com/user-attachments/assets/16e38949-4800-4048-9bdd-36da7fbd04d0" alt="Raising Todo ERD" width="800" style="border-radius: 10px; border: 1px solid #eee;"/>
</div>

### NoSQL 기반 최적화 설계 포인트
* **Habit과 Todo의 분리 (Blueprint 패턴):** `Habits` 컬렉션은 반복 규칙만 저장하고, 해당 조건이 만족될 때만 `Todos` 문서를 생성하여 Firestore의 스토리지 및 쿼리 비용을 최소화했습니다.
* **Embedded Data 적용:** 관계형 DB라면 분리했을 방 꾸미기 위치(`itemPositions`)나 인벤토리(`inventory`) 데이터를 `Character` 문서의 하위 필드(Map, List)로 내장하여 한 번의 읽기(Read)로 캐릭터 관련 렌더링이 가능하도록 설계했습니다.
* **통계를 위한 외래키(FK) 참조:** 동적으로 생성된 `Todo` 문서에 원본 `habitId`를 남겨두어, 특정 루틴의 주간/월간 달성률(Progress)을 추적할 수 있도록 구성했습니다.

<br>

## 6. 트러블 슈팅 & Deep Dive (Technical Challenges)

프로젝트를 진행하며 직면한 기술적 도전과 이를 해결하기 위한 의사결정 과정을 GitHub Wiki에 상세히 기록하였습니다. 각 항목을 클릭하면 상세 페이지로 이동합니다.

| 주제 | 핵심 기술 및 해결 방안 | 상세 보기 |
| :--- | :--- | :---: |
| **데이터 무결성 보장** | Firebase Transaction, WriteBatch, 원자적 연산 | [📄 Wiki](https://github.com/dkdlxl99/to-doong-archive/wiki/[데이터-무결성]-Firebase-트랜잭션과-배치-처리를-활용한-안정적인-결제-보상-시스템) |
| **리소스 최적화** | Widget Lifecycle, LayoutBuilder, 반응형 UI 설계, RepaintBoundary | [📄 Wiki](https://github.com/dkdlxl99/to-doong-archive/wiki/[리소스-최적화]-Flutter-위젯-생명주기-관리-및-반응형-UI-구현-기술) |
| **데이터 아키텍처** | Timestamp Range Query, Virtual Object(VO), Soft Delete | [📄 Wiki](https://github.com/dkdlxl99/to-doong-archive/wiki/[데이터-아키텍처]-NoSQL-환경에서의-복잡한-쿼리-설계-및-가상-객체(VO)-활용) |
| **버전 관리 전략** | Feature Branch Workflow, Git Flow, Conflict Resolution | [📄 Wiki](https://github.com/dkdlxl99/to-doong-archive/wiki/[버전-관리]-Git-Flow-전략-및-효과적인-충돌-해결-프로세스) |

<br>

## 7. 프로젝트 구조
```text
TODOLIST
├── android
├── assets
├── ios
├── lib
│   ├── config
│   │   └── game_rules.dart
│   ├── data
│   │   └── item_data.dart
│   ├── models
│   │   ├── character_model.dart
│   │   ├── habit_model.dart
│   │   ├── item_model.dart
│   │   ├── monthly_todo_model.dart
│   │   ├── stats_model.dart
│   │   └── todo_model.dart
│   ├── screens
│   │   ├── auth_checker.dart
│   │   ├── character_screen.dart
│   │   ├── closet_screen.dart
│   │   ├── decorate_screen.dart
│   │   ├── habit_list_screen.dart
│   │   ├── home_screen.dart
│   │   ├── login_screen.dart
│   │   ├── main_navigation_screen.dart
│   │   ├── report_screen.dart
│   │   ├── signup_screen.dart
│   │   └── splash_screen.dart
│   ├── services
│   │   ├── auth_service.dart
│   │   ├── character_service.dart
│   │   ├── habit_service.dart
│   │   ├── haptic_service.dart
│   │   ├── monthly_todo_service.dart
│   │   ├── notification_service.dart
│   │   ├── stats_service.dart
│   │   ├── todo_service.dart
│   │   └── tutorial_service.dart
│   ├── tabs
│   │   ├── calendar_tab.dart
│   │   ├── routine_daily_view.dart
│   │   ├── routine_monthly_view.dart
│   │   ├── routine_tab.dart
│   │   ├── routine_weekly_view.dart
│   │   └── stats_tab.dart
│   ├── theme
│   │   └── app_colors.dart
│   ├── widgets
│   │   ├── dialogs
│   │   │   └── (각종 바텀 시트 및 다이얼로그 위젯들)
│   │   ├── home
│   │   │   └── (홈 화면 관련 위젯 모음)
│   │   ├── shop
│   │   │   └── shop_item_card.dart
│   │   ├── character_renderer.dart
│   │   ├── interactive_room_preview.dart
│   │   └── todo_tile.dart
│   ├── firebase_options.dart
│   └── main.dart
