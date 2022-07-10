# Reference
link: [심리 성향 데이터셋](https://dacon.io/competitions/official/235647/data)
# 데이터 설명
설문에 대한 답변과 답변자의 개인 정보(ex.연령, 교육 수준, 투표 여부)가 담긴 데이터셋
# 데이터 변수
- Q_A / Q_E (a~t) : 질문과 질문에 대한 대답   
(1=Disagree, 2=Slightly disagree, 3=Neutral, 4=Slightly agree, 5=Agree)
    * Qa : Secret
    * Qb : The biggest difference between most criminals and other people is that the criminals are stupid enough to get caught.
    * Qc : Anyone who completely trusts anyone else is asking for trouble.
    * Qd : Secret
    * Qe : P.T. Barnum was wrong when he said that there's a sucker born every minute.
    * Qf : There is no excuse for lying to someone else.
    * Qg : Secret
    * Qh : Most people forget more easily the death of their parents than the loss of their property.
    * Qi : Secret
    * Qj : It is safest to assume that all people have a vicious streak and it will come out when they are given a chance.
    * Qk : All in all, it is better to be humble and honest than to be important and dishonest.
    * Ql : Secret
    * Qm : It is hard to get ahead without cutting corners here and there.
    * Qn : Secret
    * Qo : The best way to handle people is to tell them what they want to hear.
    * Qp : Secret
    * Qq : Most people are basically good and kind.
    * Qr : One should take action only when sure it is morally right.
    * Qs : It is wise to flatter important people.
    * Qt : Secret
- Q_E(a~t) : 질문을 답할 때까지의 시간
- age_group : 연령
- education : 교육 수준
(1=Less than high school, 2=High school, 3=University degree, 4=Graduate degree, 0=무응답)
- engnat : 모국어가 영어 (1=Yes, 2=No, 0=무응답)
- familysize : 형제자매 수
- gender : 성별 (Male, Female)
- hand : 필기하는 손 (1=Right, 2=Left, 3=Both, 0=무응답)
- married : 혼인 상태 (1=Never married, 2=Currently married, 3=Previously married, 0=Other)
- race : 인종
- religion : 종교
- tp__(01~07) : items were rated "I see myself as:" _____ such that
    * tp01 : Extraverted, enthusiastic.
    * tp02 : Critical, quarrelsome.
    * tp03 : Dependable, self-disciplined.
    * tp04 : Anxious, easily upset.
    * tp05 : Open to new experiences, complex.
    * tp06 : Reserved, quiet.
    * tp07 : Sympathetic, warm.
    * tp08 : Disorganized, careless.
    * tp09 : Calm, emotionally stable.
    * tp10 : Conventional, uncreative.
- urban : 유년기의 거주 구역 
(1=Rural (country side), 2=Suburban, 3=Urban (town, city), 0=무응답)
- wr_(01~13) : 실존하는 해당 단어의 정의을 앎 (1=Yes, 0=No)
- wf_(01~03) : 허구인 단어의 정의를 앎 (1=Yes, 0=No)
- voted (타겟): 지난 해 국가 선거 투표 여부 (1=Yes, 2=No)  
(+) [데이터셋 설명 출처](https://www.dacon.io/competitions/official/235647/talkboard/401534?page=1&dtype=recent&ptype=pub) 