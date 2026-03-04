## 역학 일제 사격(Kinetic Fusillade) 쇠뇌 토템 히에로팬트


---

## 1. 빌드 개요

Pohx가 3.28 신기루(Mirage) 리그 스타터로 선택한 빌드는 **역학 일제 사격 + 쇠뇌 토템 보조 + 히에로팬트**입니다. 지난 FCA 이벤트에서 성기사(Paladin) 버전으로 테스트했고, 이번에는 히에로팬트로 전환했습니다. Tatiantel의 토템 버전이나 Loc의 자가 시전 버전이 이미 있었지만, FCA 이후 쇠뇌 버전이 본격적으로 주목받기 시작했습니다.

---

## 2. 역학 일제 사격 메카닉

**기본 원리:** 공격 시 투사체가 충전되고, 일정 지연 후 일제히 발사됩니다. 최대 12개까지 충전 가능하며, 떠 있는 투사체가 많을수록 피해 배율이 상승합니다. 연쇄(Chain) 최대 3회.

**핵심 공식:**
- 기본 지속시간: 0.7초
- 투사체당 추가 지연: 0.05초
- 상위 사격 공세(Greater Volley) + 완드 숙련으로 총 6발 → 추가 0.3초
- **총 지연시간 = 약 1.0초**

**중요 규칙:** 공격 시간이 지연시간보다 길어야(= 공격 속도가 충분히 느려야) 투사체가 즉시 발사됩니다. 공격이 너무 빠르면 투사체가 계속 쌓이기만 하고 발사되지 않아 무한루프에 빠집니다.

**쇠뇌 토템의 장점:** 쇠뇌 토템 보조(Ballista Totem Support) 자체에 **50% 감폭(less) 공격 속도**가 있어, 자가 시전보다 지속시간 감소를 훨씬 적게 맞춰도 됩니다. 장비 자유도가 높고, 용암 방패(Molten Shell)나 수호 스킬 등 보조 스킬도 지속시간이 거의 0이 되는 문제 없이 정상 사용 가능합니다.

**지속시간 감소 확보처:**
- **지속시간 감소 보조(Less Duration Support)** — 필수, 최대한 빨리 레벨링 + 품질 투자
- **기회의 창(Windows of Opportunity) 클러스터**: 15% 감소 + 소형 노드 10% + 숙련 10% 감폭
- 이 정도면 수호석(Watchstone) 2개까지 충분

**후반 추가 옵션 (하나만 선택, 과도하게 줄이지 말 것):**
- **뒤틀린 시계(Warped Timepiece)** — 목걸이. 최대 20% 감소 + 공속 + 이속. 가장 추천
- **시간의 속박(Timeclasp)** — 반지. 20% 증가~20% 감소 사이로 롤링, 감소가 높은 것 필요
- **황혼의 반지(Dusk Ring)** — 왼쪽 반지 슬롯. 15% 감소된 스킬 효과 지속시간
- **성급한 최후(Hasty Demise) 도유** — 나쁘지 않지만 히에로팬트는 도유가 중요해서 비추

**PoB 확인법:** 캐릭터 가져오기 → 공격 속도(attack rate)와 최대 유효 APS(max effective APS) 비교. 최대 유효 APS가 현재 공격 속도보다 높으면 정상(초록색). **문제가 있으면 체감으로 확실히 느껴집니다** — 토템이 충전만 하고 한참 후에야 발사하거나 아예 안 쏩니다. 단순히 데미지가 낮아지는 게 아니라 클리어 자체가 망가집니다.

---

## 3. 왜 토템인가 (자가 시전 대비)

- 50% 감폭 공격 속도 덕분에 지속시간 감소 맞추기가 훨씬 수월 → **장비 자유도 높음**, 나선형 반지(Helical Ring) 등 엔드게임 장비 부담 감소
- 보스전 시 안전하게 후방에서 플레이 가능, 조준 불필요
- **3.28 토템 대규모 버프**: 토템 설치 속도가 출현 시간(emerge time, 기존 633ms 고정)도 스케일링하게 변경됨. 히에로팬트는 전직만으로 140% 설치 속도 확보 → 약 200% 설치 속도로 플레이

---

## 4. 전직: 히에로팬트 선택 이유

- 3.28에서 히에로팬트 버프됨 (별도 영상 참고)
- 설치 속도가 프리미엄 능력치가 된 상황에서 히에로팬트 압도적. 듀얼리스트 쪽은 토템 열의(Totemic Zeal) 등이 있지만 140% 설치 속도에는 미치지 못함
- **전환 옵션이 다양** → 수호석 4개 파밍 후 마나 빌드, 군집의 역학 폭발(Kinetic Blast of Clustering), 심문관(Inquisitor), 에너지 칼날(Energy Blade), 신규 신성 스킬, 수호자(Guardian) 등으로 전환 가능

**핵심 전직 노드:**
- **신념의 추구(Pursuit of Faith)**: +1 토템, 100% 증가된 토템 설치 속도. 엄청난 파워 스파이크. 참고로 토템 지속시간은 감소된 지속시간에 영향받지 않으므로 걱정 불필요
- **각성의 의식(Ritual of Awakening)**: 토템당 최대 40% 증폭(more) 피해 + 마나/생명력 재생. 토템 빌드에서 흡수가 불가능한 점을 보완
- **힘의 확신(Conviction of Power)**: 최소 인내 충전/권능 충전 — 안정적인 방어+공격

**혈통(Bloodline, 4번째 노드):**
- 최적: **올빼미 왕의 유산(Owl King's Heritage)** — 결의(Determination) 효과 + 분노(Anger) 효과 50%. 둘 다 사용 중이라 시너지 최고
- 단, 올(Owl)을 먼저 파밍/구매해야 함. 화석이 이제 광산(Delve) 전용이라 광산 플레이어 증가 예상 → 비교적 구하기 쉬울 것
- 대안: **폭풍의 재(Ash of the Storm)** — 시냅틱 반지(Synaptic Ring) 2개 조합, 원소 저항 무시. 첫 줄만 필요
- 트레일러에서 새로운 혈통이 보임 → 리그 시작 후 업데이트 예정

---

## 5. 피해 스케일링 특징

**고정 피해와 오라가 핵심:**
- 완드는 한손 무기라 캠페인 중 좋은 완드를 도박으로 얻기가 거의 불가능 → **진노(Wrath), 분노(Anger), 전령(Herald)** 등 오라에서 대부분의 피해 확보
- 장비에서도 고정 피해가 프리미엄. 에센스(분노/진노/증오 에센스)로 완드에 고정 피해 부여
- 엔드게임에서도 분노(Anger) 버프가 약 86% 증폭 피해 수준

**주문 피해 = 공격 피해:**
- 역학 일제 사격은 **"주문 피해의 증가 및 감소가 공격 피해에 150% 효율로 적용"**
- 즉, 주문 피해 10% = 공격 피해 15%
- 신성의 빛(Light of Divinity) 같은 주문 피해 노드가 매우 강력

---

## 6. 방어 구성

상단 트리라서 일반적인 회피 + 주문 피해 억제 + 유연한 전투원(Versatile Combatant) 패키지를 쓸 수 없음.

**주요 방어:**
- **방어도 + 용암 방패(Molten Shell)**: 용암 방패 ON/OFF 차이가 매우 큼. 방어도 빌드는 용암 방패가 핵심 — 용암 방패 안 쓰면 빌드가 구려짐
- **발전기(Dynamo) 노드**: 40% 증가된 지속시간으로 reduced duration 단점을 상쇄하여 용암 방패 유지시간 정상화
- **주문 막기**: 폭풍의 방패(Tempest Shield, 무료 ~25% 주문 막기) + 안전장치(Safeguard) + 비전 수호자(Arcane Guardian) + 막기 숙련 → **78% 주문 막기 상한 달성 가능 (장비 없이)**
- **공격 막기**: 초반엔 47% 정도로 부족. 엔드게임에서 해결

**엔드게임 방어:**
- **비호의 오로라(Aegis Aurora)** — 2등급(Tier 2) 고유 방패. 막기 시 방어도의 2%만큼 에너지 보호막 회복 → **비껴내기(Glancing Blows)**와 조합
- 방어도 52,000 기준 → 막기마다 1,040 에너지 보호막 회복. 맵핑에서 여러 몬스터가 때릴 때 거의 안 죽음
- **비껴내기(Glancing Blows)는 반드시 비호의 오로라와 함께만 사용.** 단독 사용은 절대 금지 — 비호의 오로라 없이는 그냥 쓰레기
- 비호의 오로라 장착 시 비전 수호자 + 안전장치 스펙 아웃 → 포인트 절약, 비껴내기로 블록 캡
- 바디아머를 방어도+에너지 보호막 또는 풀 에너지 보호막으로 전환 (ES 2,000~4,000 목표)

**기타:**
- **카오스 저항 반드시 확보** → -60 카오스 저항으로 죽으면 본인 잘못
- **판테온**: 소금왕의 영혼(Soul of the Brine King) — 동결 면역 필수. 현재 '머빌 더 리턴드(Merville the Returned)'가 지하 해저 지도(Underground Sea) 보스이나, 3.28에서 산호 폐허 지도(Coral Ruins)가 추가되므로 변경 가능성 있음. 소형은 애버래스의 영혼(Soul of Abberath)

---

## 7. 진행 단계별 구성

### A. 초반 지도 (비호의 오로라 이전)

**패시브:** 상단 패싱. 붉은 지도 진입 시 주문 막기 노드 확보. 평소 레드맵에서 불굴(Inveterate) + 행운의 주문 억제를 찍듯이, 이 빌드에서는 안전장치 + 비전 수호자 + 폭풍의 방패로 주문 막기 78% 캡.

**필수 4연결 (이것 없이는 플레이 불가):**
- 역학 일제 사격(Kinetic Fusillade) + 쇠뇌 토템 보조(Ballista Totem Support) + 지속시간 감소 보조(Less Duration Support) + 상위 사격 공세 보조(Greater Volley Support)

**나머지 서포트:**
- 공격 시 원소 피해 보조(Elemental Damage with Attacks Support) + 치명타 피해 증가 보조(Increased Critical Damage Support)
- 3.28에서 7번째 서포트 획득 방법이 새로 생기지만, 가격은 리그 시작 후 확인 필요

**오라:**
- 분노(Anger) + 결의(Determination) — 안전 우선
- 또는 분노(Anger) + 진노(Wrath) — 약 36% 증폭 피해. 폭딜 우선
- 폭풍의 방패(Tempest Shield) — 감전 면역 + 주문 막기
- 정밀함(Precision): 오만 보조(Arrogance Support) 위에 장착 (생명력 일부 점유, 마나 점유 문제 해결)

**유틸리티:**
- 회오리(Tornado) + 신비학자 낙인(Arcanist Brand) + 시전 속도 증가 보조(Faster Casting Support) — 회오리가 20히트 제한이라 낙인으로 반복 시전 필수. **다른 스킬을 여기에 넣으면 안 됨** (교대 시전되어 효율 반감)
- 격분(Frenzy) + 치명타 시 시전 보조(Cast On Critical Strike Support) + 원소 약화(Elemental Weakness) — 디버프용. 상위 사격 공세 보조 추가 (격분이 투사체 2개라 V자 형태로 빗나가는 문제 해결)
- 방패 돌진(Shield Charge) + 공격 속도 증가 보조(Faster Attacks Support) + 기세 보조(Momentum Support) + 서리점멸(Frostblink) — 방패 돌진 끝에 애니메이션 캔슬 가능
- 용암 방패(Molten Shell) + 피격 시 시전 보조(Cast when Damage Taken Support) — 핵심 방어층

**장비:**
- 완드: 에센스(분노/진노/증오)로 고정 피해 부여, 관통 제작, 치명타 옵션 필요. **캠페인 중 완드 도박 절대 금지**
- 방패: 주문 피해 + 막기 확률
- 갑옷: 방어도 베이스, 6연결 저가 아스트랄 판금(Astral Plate) 등 빠르게 확보
- **도이드리의 임기(Doedre's Tenure)**: 약 150% 공격 피해, 3~5 카오스 오브. 강력한 초반 파워 스파이크
- 무거운 허리띠(Heavy Belt)로 힘 확보 → 강철의 의지(Iron Will)로 피해 연결
- 자수정 반지(Amethyst Ring) + 하이브리드 제작으로 카오스 저항 확보
- 선대의 유대(Ancestral Bond) 필수 장착
- **토템 저항 클러스터** 왼쪽(32% 원소 저항) 반드시 확보 — 토템 기본 원소 저항이 40%밖에 안 되므로, 이걸 찍으면 토템의 원소 피해 최대 적중량이 약 2배

**약병:** 이 시점에서는 기본적인 구성

### B. 비호의 오로라 직전 단계

- **뒤틀린 시계(Warped Timepiece)** 목걸이 장착 → 감시(Surveillance) 도유 가능. 오팔레센트(Opalescent) 오일 필요
- 장비가 전반적으로 소폭 업그레이드: 엘드리치 암시, 카오스 저항 추가, 고정 피해 추가, 힘 롤 추가
- **약병 최적화**: 다이아몬드 약병(치명타 확률), 수은 약병(이동 속도), 석영 약병(저주 효과 감소 + 위상), 화강암 약병(**% 방어도 효과 중 접미사 필수** — 초반에 증가된 방어도가 부족하기 때문)
- 위상(Phasing)으로 몹 사이를 뚫고 달리는 플레이

### C. 비호의 오로라(Aegis Aurora) 이후

- 비껴내기(Glancing Blows) 키스톤 활성화
- 비전 수호자(Arcane Guardian) + 안전장치(Safeguard) 스펙 아웃 → 포인트 절약, 다른 곳에 배분
- 바디아머를 방어도+에너지 보호막 또는 풀 에너지 보호막으로 전환 (ES 2,000~4,000 목표, 지능 너프 반영됨)
- 방어도 52,000 × 0.02 = **막기당 1,040 에너지 보호막 회복** → 맵핑에서 강력한 생존력
- 다만 토템 빌드이므로 굳이 몹 한가운데 서 있을 필요 없음. 용암 방패가 꺼진 상태에서 큰 한방(특히 카오스 피해)은 여전히 위험

---

## 8. 엔드게임 업그레이드

- **파편의 비(Rain of Splinters)** (주얼): +2 투사체 → 약 39% 증폭 피해. 단, 투사체 증가로 지연시간도 늘어남 (최대 유효 APS 4.33 → 3.79). 공격 속도 과투자 주의

- **붉은 악몽(Red Nightmare)** (주얼): 반경 내 화염 저항 패시브가 50%만큼 막기 확률로 전환 → 상단 트리의 공격 막기 부족 해결. 문신(Tattoo)으로 화염 저항 추가 투입 가능. 3.28에서 문신이 캠페인에도 등장하므로 가격 하락 예상. 신념과 강철(Faith and Steel) 반경 8 저항 = 4 막기, 신성한 위력(Holy Dominion) = 6 막기 등

- **치명적 긍지(Lethal Pride)**: 이중 피해, 위협, 추가 힘, % 생명력 등. 신비적 요새(Mystic Bulwark), 투사체 완성(Projectile Perfection), 완드 불안정(Wand Instability), 대원 준비(Crew Preparation) 등 다수 활용 가능

- **스킬 군 주얼(Cluster Jewel)**: 맹공(Onslaught, 이동 속도+공격 속도), 추가 설치 속도, 일제사격과 분해(Fusillade and Disintegration) 등. **너무 일찍 투자하지 말 것** — 비쌈. 기본 트리 노드로도 충분. 대형 클러스터를 먼저 넣고 중형을 넣는 것이 중요

- **끈 허리띠(Cord Belt)** (신규 기반 아이템): 카시아(Cassia) 도유 가능 → 목걸이에 감시(Surveillance) + 허리띠에 망루(Watchtowers) = **총 8개 토템**. 추가 투사체 선택도 가능 (연사/Multi-shot)

---

## 9. 레벨링

- **1~4막**: 신성한 화염 토템(Holy Flame Totem) + 몰려오는 마그마(Rolling Magma) (+ 선택적으로 화염 폭풍(Firestorm))
- **4막**: 기회의 창(Windows of Opportunity) 감소된 지속시간 클러스터 도달 시 리스펙 → **역학 일제 사격으로 전환**, 이후 쭉 진행. 골드 비용이 저렴하여 리스펙이 쉬움
- 완드는 캠페인 중 **도박 절대 금지** — 좋은 완드 나올 확률이 극히 낮음
- 별도 레벨링 영상 제작 예정

---

## 10. 기타

- Pohx는 트위치(twitch.tv/pohx)에서 리그 첫 주 풀타임 스트리밍 예정
- Maxroll 서면 가이드 출시됨 (핀 댓글에 링크)
- **리그 첫 주 매일 3~4개 업데이트 영상** 예정 (미발견 요소, 조정 사항, 진행 상황)
- Jungroan이 5시간짜리 풀 플레이 영상 업로드 (빌드 진행 참고용)
- 전환 옵션: 마나 빌드, 에너지 칼날(Energy Blade), 군집의 역학 폭발(Kinetic Blast of Clustering), 신규 신성 스킬, 수호자(Guardian) 등
- 결투의 용사(Champion) 버전 가이드도 시간이 되면 별도 출시 예정

---

## 용어 대조표 (주요 항목)

| 영문 | 한글 (나랏말서미누기 사전) |
|---|---|
| Kinetic Fusillade | 역학 일제 사격 |
| Kinetic Blast of Clustering | 군집의 역학 폭발 |
| Ballista Totem Support | 쇠뇌 토템 보조 |
| Less Duration Support | 지속시간 감소 보조 |
| Greater Volley Support | 상위 사격 공세 보조 |
| Elemental Damage with Attacks Support | 공격 시 원소 피해 보조 |
| Increased Critical Damage Support | 치명타 피해 증가 보조 |
| Cast On Critical Strike Support | 치명타 시 시전 보조 |
| Cast when Damage Taken Support | 피격 시 시전 보조 |
| Faster Attacks Support | 공격 속도 증가 보조 |
| Faster Casting Support | 시전 속도 증가 보조 |
| Momentum Support | 기세 보조 |
| Arrogance Support | 오만 보조 |
| Anger | 분노 |
| Wrath | 진노 |
| Determination | 결의 |
| Hatred | 증오 |
| Precision | 정밀함 |
| Tempest Shield | 폭풍의 방패 |
| Molten Shell | 용암 방패 |
| Tornado | 회오리 |
| Arcanist Brand | 신비학자 낙인 |
| Frenzy | 격분 |
| Elemental Weakness | 원소 약화 |
| Shield Charge | 방패 돌진 |
| Frostblink | 서리점멸 |
| Holy Flame Totem | 신성한 화염 토템 |
| Rolling Magma | 몰려오는 마그마 |
| Firestorm | 화염 폭풍 |
| Energy Blade | 에너지 칼날 |
| Aegis Aurora | 비호의 오로라 |
| Warped Timepiece | 뒤틀린 시계 |
| Timeclasp | 시간의 속박 |
| Doedre's Tenure | 도이드리의 임기 |
| Rain of Splinters | 파편의 비 |
| Red Nightmare | 붉은 악몽 |
| Lethal Pride | 치명적 긍지 |
| Glancing Blows | 비껴내기 |
| Ancestral Bond | 선대의 유대 |
| Elemental Overload | 원소 과부하 |
| Versatile Combatant | 유연한 전투원 |
| Iron Will | 강철의 의지 |
| Spark | 전기불꽃 |
