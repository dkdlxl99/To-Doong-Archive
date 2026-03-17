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
-  **강력한 루틴**: 요일별/주간/월간 반복 설정 및 상황별(기상 후, 출근 길 등) 시간 설정 지원
- **쉬어가기 모드**: 아프거나 여행 갈 때, 스트릭(Streak)이 끊기지 않도록 루틴 일시 정지 기능
- **통계 분석**: 히트맵(잔디 심기)과 레이더 차트를 통한 나의 능력치(건강, 공부 등) 분석

<br>

## 2. 팀원 소개 (풀스택 2명)

| **🐶 팀원 A (팀장)** | **🐱 팀원 B** |
| :------: | :------: |
| <img src="https://avatars.githubusercontent.com/u/00000000?v=4" height=150 width=150> | <img src="https://avatars.githubusercontent.com/u/00000000?v=4" height=150 width=150> |
| **[@GitHubID](https://github.com/)** | **[@GitHubID](https://github.com/)** |
| **Full Stack** | **Full Stack** |
| 인증/계정 관리, 캐릭터/상점 시스템<br>방 꾸미기(인터랙티브 UI), Firebase 연동 | 투두/습관 CRUD, 통계/리포트 시스템<br>알림/햅틱 서비스, 캘린더 구현 |

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
        <strong>사용자 친화적인 첫 만남</strong>
        <ul>
          <li><strong>직관적인 회원가입:</strong> 이메일/비밀번호 입력을 통한 빠르고 간편한 가입 프로세스</li>
          <li><strong>초기 캐릭터 생성:</strong> 가입 즉시 알(Egg) 상태의 캐릭터를 지급하여 성장의 시작을 알림</li>
          <li><strong>튜토리얼 시스템:</strong> <code>TutorialCoachMark</code>를 통해 주요 기능(할 일 추가 등)을 자연스럽게 학습 유도</li>
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
        <strong>동기 부여를 위한 즉각적인 피드백</strong>
        <ul>
          <li><strong>할 일 관리:</strong> 난이도(상/중/하) 설정이 가능한 투두 리스트 작성</li>
          <li><strong>완료 보상:</strong> 체크박스 클릭 시 <strong>경험치(XP)와 골드</strong>가 실시간으로 증가하는 시각적 효과 제공</li>
          <li><strong>햅틱 피드백:</strong> 완료 순간 진동 효과를 통해 성취감을 극대화 (<code>HapticService</code> 활용)</li>
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
        <strong>성장하는 나, 진화하는 캐릭터</strong>
        <ul>
          <li><strong>단계별 진화:</strong> 누적된 경험치에 따라 <strong>알 → 아기 → 성체</strong>로 외형이 변화하며 성장</li>
          <li><strong>애정 형성:</strong> 캐릭터에게 직접 이름을 지어주고, 터치 반응을 통해 유대감 형성</li>
          <li><strong>소화 시스템:</strong> 시간 경과에 따라 포만감이 감소하는 리얼리티 요소 도입 (지속적인 관리 유도)</li>
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
        <strong>자유로운 커스터마이징</strong>
        <ul>
          <li><strong>아이템 상점:</strong> 획득한 골드로 다양한 가구(침대, 러그, 소품 등)와 벽지/바닥 구매</li>
          <li><strong>인터랙티브 배치:</strong> 구매한 가구를 화면 내 원하는 위치로 자유롭게 <strong>Drag & Drop</strong> 하여 배치</li>
          <li><strong>레이어 시스템:</strong> 캐릭터와 가구의 앞뒤 관계(Z-Index)를 고려한 자연스러운 공간 연출</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

### 4-5. 체계적인 루틴 관리 및 생성
<table>
  <tbody>
    <tr>
      <td align="center" width="300px">
        <img src="https://github.com/user-attachments/assets/37563cfb-96c0-4212-9dcc-2a455b1d8999" alt="루틴 생성" />
      </td>
      <td>
        <strong>습관 형성을 위한 강력한 도구</strong>
        <ul>
          <li><strong>반복 설정:</strong> 요일별, 주 n회, 월 n회 등 다양한 반복 주기 지원</li>
          <li><strong>상황별 시간 설정:</strong> 단순 시간뿐만 아니라 '기상 후', '출근 길' 등 라이프스타일 문맥에 맞춘 태그 제공</li>
          <li><strong>자동 투두 생성:</strong> 설정된 루틴은 해당 날짜에 자동으로 '오늘의 할 일' 리스트에 추가됨</li>
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
        <strong>지속 가능한 습관 관리</strong>
        <ul>
          <li><strong>Rest Mode:</strong> 여행이나 질병 등으로 수행이 불가능할 때, 루틴을 일시 정지 상태로 전환</li>
          <li><strong>스트릭 보호:</strong> 쉬는 기간 동안은 미달성으로 처리되지 않아 연속 달성 기록(Streak) 유지 가능</li>
          <li><strong>직관적인 UX:</strong> 리스트 아이템을 스와이프하여 간편하게 휴식 설정 및 해제</li>
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
        <strong>한눈에 보는 나의 성장 기록</strong>
        <ul>
          <li><strong>주간 리포트:</strong> '성실한 모험가' 등 칭호 부여 및 주간 완료 개수 요약</li>
          <li><strong>레이더 차트:</strong> 건강, 공부, 생산성 등 카테고리별 수행 횟수를 분석하여 나의 강점 파악 (RPG 스탯 스타일)</li>
          <li><strong>성장 캘린더 (히트맵):</strong> 잔디 심기 UI로 날짜별 달성도를 캐릭터 표정 변화(😴/😀/🥰)로 시각화</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

<br>

## 5.트러블 슈팅 (Technical Challenges)

개발 과정에서 마주친 기술적 문제와 해결 과정을 GitHub Wiki에 정리했습니다.

- [데이터 무결성 보장을 위한 트랜잭션 및 배치 처리](https://github.com/본인ID/레포지토리명/wiki/트러블슈팅-1.-데이터-무결성-보장)
- [반응형 UI 구현 및 렌더링 최적화 (LayoutBuilder & RepaintBoundary)](https://github.com/본인ID/레포지토리명/wiki/트러블슈팅-2.-UI-최적화)
- [복잡한 날짜 필터링 및 가상 객체(Virtual Object) 설계](https://github.com/본인ID/레포지토리명/wiki/트러블슈팅-3.-캘린더-필터링-알고리즘)
- [과거 기록 보존을 위한 Soft Delete 전략](https://github.com/본인ID/레포지토리명/wiki/트러블슈팅-4.-Soft-Delete-전략)

<br>

## 6. 프로젝트 구조
```
TODOLIST
├── android
│   ├── app
│   ├── gradle
│   ├── build.gradle.kts
│   ├── gradle.properties
│   ├── gradlew
│   ├── gradlew.bat
│   ├── local.properties
│   └── settings.gradle.kts
├── assets
├── build
├── ios
├── lib
│   ├── config
│   │   └── game_rules.dart
│   ├── data
│   │   └── item_data.dart
│   ├── models
│   │   ├── character_model.dart
│   │   ├── habit_model.dart
│   │   ├── item_model.dart
│   │   ├── monthly_todo_model.dart
│   │   ├── stats_model.dart
│   │   └── todo_model.dart
│   ├── screens
│   │   ├── auth_checker.dart
│   │   ├── character_screen.dart
│   │   ├── closet_screen.dart
│   │   ├── decorate_screen.dart
│   │   ├── habit_list_screen.dart
│   │   ├── home_screen.dart
│   │   ├── login_screen.dart
│   │   ├── main_navigation_screen.dart
│   │   ├── report_screen.dart
│   │   ├── signup_screen.dart
│   │   └── splash_screen.dart
│   ├── services
│   │   ├── auth_service.dart
│   │   ├── character_service.dart
│   │   ├── habit_service.dart
│   │   ├── haptic_service.dart
│   │   ├── monthly_todo_service.dart
│   │   ├── notification_service.dart
│   │   ├── stats_service.dart
│   │   ├── todo_service.dart
│   │   └── tutorial_service.dart
│   ├── tabs
│   │   ├── calendar_tab.dart
│   │   ├── routine_daily_view.dart
│   │   ├── routine_monthly_view.dart
│   │   ├── routine_tab.dart
│   │   ├── routine_weekly_view.dart
│   │   └── stats_tab.dart
│   ├── theme
│   │   └── app_colors.dart
│   ├── widgets
│   │   ├── dialogs
│   │   │   ├── add_routine_sheet.dart
│   │   │   ├── add_todo_sheet.dart
│   │   │   ├── base_habit_sheet.dart
│   │   │   ├── edit_habit_sheet.dart
│   │   │   ├── edit_todo_sheet.dart
│   │   │   ├── feedback_sheet.dart
│   │   │   ├── habit_delete_dialog.dart
│   │   │   ├── reauth_sheet.dart
│   │   │   ├── rest_habit_dialog.dart
│   │   │   ├── reward_dialog.dart
│   │   │   └── settings_modal.dart
│   │   ├── home
│   │   │   ├── character_dashboard.dart
│   │   │   ├── monthly_todo_section.dart
│   │   │   ├── quest_header.dart
│   │   │   └── todo_list_section.dart
│   │   ├── shop
│   │   │   └── shop_item_card.dart
│   │   ├── character_renderer.dart
│   │   ├── interactive_room_preview.dart
│   │   └── todo_tile.dart
│   ├── firebase_options.dart
│   └── main.dart
├── linux
├── macos
├── test
├── web
└── windows
```
<br>
