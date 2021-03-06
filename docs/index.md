--- 
title: "데이터 과학 언플러그드"
author: "한국 알(R) 사용자회"
date: "2022-05-24"
site: bookdown::bookdown_site
output: bookdown::gitbook
documentclass: book
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
github-repo: r2bit/book_unplugged
description: "데이터 사이언스를 이해하는 꼭 필요한 개념을 정리했습니다."
---

# 데이터 과학 언플러그드 {-}

사단법인 한국 알(R) 사용자회는 디지털 불평등 해소와 통계 대중화를 위해 
2022년 설립되었습니다. 오픈 통계 패키지(BitStat) 개발을 비롯하여
최근에 데이터 사이언스 관련 교재도 함께 제작하여 발간하는 작업을 수행하고 있습니다.
그 첫번째 결과물로 John Fox 교수님이 개발한 설치형 오픈 통계 패키지 
`Rcmdr`[@fox2016using] [@rcmdr2022manual] [@rcmdr2005paper] 를 신종화 님께서 
한글화 및 문서화에 10년 넘게 기여해주신 한국알사용자회 저작권을 흔쾌히 
허락해 주셔서 [설치형 오픈 통계 패키지 - `Rcmdr`](https://r2bit.com/Rcmdr/)로 세상에 나왔습니다.

두번째 활동을 여기저기 산재되어 있던 시각화 관련 자료를 묶어
**[데이터 시각화(Data Visualization)](https://r2bit.com/book_viz/)**를 전자책 형태로 공개하였고,
데이터 분석 관련 저술을 이어 진행하게 되었습니다.

세번째 활동으로 데이터 사이언스가 하나로 구성되지 않은 것을 간파하고
데이터 사이언스를 지탱하는 기본기술을 5가지로 정리한 
**[데이터 과학을 지탱하는 기본기](https://r2bit.com/book_analytics/)** 전자책을 
공개했습니다.

네번째 활동으로 손으로 데이터 사이언스를 하는 분들은 없기 때문에
컴퓨터 프로그래밍 언어로 R을 채택하여 
**[데이터 사이언스 프로그래밍](https://r2bit.com/book_programming/) 전자책을 공개했습니다.

데이터 분석 언어 R에 관한 지식을 신속히 습득하여 독자들이 갖고 있는 문제에 
접목시키고자 하시는 분은 한국 알(R) 사용자회에서 번역하여 공개한 
[R 신병훈련소(Bootcamp)](https://dl-dashboard.shinyapps.io/rbootcamp/) 과정을
추천드립니다. 

---

"데이터 과학 언플러그드" 저작을 위해 
[Computer Science Unplugged](http://csunplugged.org/)의 클래식 버젼
[CS Unplugged](https://classic.csunplugged.org/)[@bell2015cs]의 
크리에이티브 커먼스 라이선스를 준용하고 있으며
한국적인 상황을 최대한 반영하여 내용 및 삽화를 일부 수정하였습니다. 
또한, 컴퓨터 과학 언플러그드 공유 및 협업을 위해 
[GitHub 저장소](https://github.com/r2bit/book_unplugged)에 그동안 작업결과를
정리했습니다.
특히, [소프트웨어 카펜트리(Software Carpentry)](http://software-carpentry.org/) 
템플릿과 [R bookdown](https://bookdown.org/) 패키지를 사용한 것이 도움이 많이 되었다. 
**Data Science Concept Maps - a remixable collection of teaching resources**
크리에이티브 커먼스 라이선스를 활용했음을 밝혀둡니다.
"데이터 과학 언플러그드" 저작물을 비롯한 
한국 알(R) 사용자회 저작물은 크리에이티브 커먼즈 
[저작자표시-비영리-동일조건 변경 허락 (BY-NC-SA)](http://ccl.cckorea.org/about/)
라이선스를 준용하고 있습니다. 

<p align="center">
  <img src="assets/images/CC-BY-NC-SA.png" alt="CC" width="25%" />
</p>

관련 문의와 연락이 필요한 경우 한국 알(R) 사용자회 admin@r2bit.com 대표전자우편으로 연락주세요.

---

::: {#book-sponsor .rmdtip}
**후원계좌**

디지털 불평등 해소를 위해 제작중인 오픈 통계패키지 개발과 고품질 콘텐츠 제작에 큰 힘이 됩니다.

  - 하나은행 448-910057-06204
  - 사단법인 한국알사용자회
:::


## 컴퓨터 과학 언플러그드 {-#cs-unplugged}

G-창업 프로젝트 [경기중소기업종합지원센터](http://www.egbiz.or.kr/) 지원을 
일부 받았고, 컴퓨터 과학 언플러그드 초기 한국어 번역 및 삽화 작업에 
도움을 주신 분들은 다음과 같다.

::: {#tuple-list-column .rmdnote}

**한국어 프로젝트 참여자 및 원저작자 정보**
 
- 한국어 번역: 이광춘  
- 한국어 삽화: 문춘경  
- 저자: Tim Bell, Ian H. Witten, Mike Fellows  
- 실험수업:  Robyn Adams and Jane McKenzie  
- 삽화: Matt Powell  

**한글 데이터/컴퓨터 과학 언플러그드 버젼**

- 2022년 05월 : 데이터 사이언스 언플러그드 신규 콘텐츠 
- 2017년 10월 : 전자책 버젼 및 신규 콘텐츠 보강
- 2016년 1월 : EBS 링크, 소프트웨어 세상 제작 동영상
    -  [링크, 소프트웨어 세상](http://bit.ly/1Vx98an)
- 2015년 05월: 컴퓨터 과학 언플러그드 3.1 버젼 한글 번역 완료 HTML/PDF/E-PUB 무료 전자책 배포
    - 인터넷에 대한 신규 활동 추가, 로고 변경
    - 버젼 3.0에서 Part I, Part II로 양분되었던 교재(MS 워드)가 하나로 합쳐짐.
    - 교육과정이 뉴질랜드 중심에서 글로벌 교육체계에 맞춰 변경.
    - 한국어 언플러그드 교재를 PDF, E-PUB, HTML로 다양화하여 제공. 
- 2015년 03월: 컴퓨터 과학 언플러그드 3.0 버젼 MS 워드 기반에서 마크다운 공개 소프트웨어 플랫폼 변환(GitHub)
- 2015년 02월: 컴퓨터 과학 언플러그드 3.0 버젼 삽화 한국화 작업
- 2015년 01월: 컴퓨터 과학 언플러그드 3.0 버젼 Part IV,V,VI 번역 (MS 워드)
- 2014년 08월: 컴퓨터 과학 언플러그드 3.0 버젼 Part I,II,III 번역 (MS 워드) 

:::

### 한국어 번역 {-#korean}

우리나라의 산업발달과정을 보면 1950~1960년대 수입대체를 목표로 신발, 섬유가 중심이 된 경공업시대, 1970~1980년 수출진흥을 목표로 철강, 조선, 자동차가 중심이 된 중공업시대, 1990~2000년대 기술혁신을 통한 반도체, 핸드폰, 디스플레이가 중심이 된 ICT 산업을 지나 2010~2020년대는 소프트웨어, 콘텐트, 과학기술이 중심이 되는 융합•지식 창조산업 시대로 발전해 갈 것으로 기대하고 있다.

첫 인터넷 웹 브라우저를 만든 마크 앤더슨은 소프트웨어가 세상을 먹고 있다(“Software is eating the world”)는 자극적인 표현으로 2011년 월스트리트 저널에 에세이를 썼고, 카네기멜론 대학의 쟈넷 윙 교수는 이론적 사고(Theoretical Thinking), 실험적 사고(Experimental Thinking))와 더불어 정보적 사고(Computational Thinking)가 현재도 그렇지만 앞으로 인간의 사고를 지배하는 중추적인 역할을 할 것을 주장했다. 이들의 결과는 정보적 사고를 배운 사람과 소프트웨어를 이해하고 활용하는 사람과 그렇지 못한 사람과의 차이는 산업경제의 빈부격차보다 더 큰 디지털 경제의 정보 불평등(Digital Divide)를 야기할 것으로 예측했다.

정부는 '14년 7월 세계 경제, 사회 환경이 소프트웨어 중심사회로 급격히 변화하고 있으며, 소프트웨어가 혁신과 성장, 가치창출의 중심이 되고, 개인•기업•국가의 경쟁력을 좌우하는 중요한 역할을 하고 있음에도 불구하고, 우리나라는 범정부적, 국민적 관심이 미흡한 상황이라고 진단하고, 미국, 영국, 이스라엘 등 선진국과 마찬가지로, 초•중•고에서 소프트웨어를 필수로 이수할 수 있는 방안을 강구하고 있다.

하지만, 지금까지 소프트웨어가 고등교육과 직업 교육에 초점이 맞추어줘서 초•중•고 및 소프트웨어에 관심을 가지고 있는 일반인이 접근하기에는 높은 장벽이 있었으나, '컴퓨터 과학 언플러그드 (Computer Science Unplugged)'를 통해서 소프트웨어를 처음 접하거나, 원리를 이해하고자 하는 분들에게는 큰 도움이 되고 특히, 컴퓨터적 사고 (Computational Thinking)에 대한 입문으로적 적합할 것으로 생각된다.

컴퓨터 과학 언플러그드는 정보 불평등 해소하고, 대한민국 전 국민을 단돈 천원($1) 정보교육으로 행복한 세상 만들기 위한 정보 소프트웨어 교육 xwMOOC 프로젝트 중의 하나이며, 정보교육을 위한 파이썬, 소프트웨어 카펜트리 등 다양한 프로젝트가 진행중이다.

많은 분들이 번역 및 감수에 참여하여 빠른 시간 내에 번역이 완료될 수 있었으며, 문춘경, 김이정님이 삽화와 그래픽 디자인에 도움을 주셨고, 위키 플랫폼 구축과 xwMOOC 클라우드 서비스를 운영해 주고 계신 한정수님, 그리고 프로젝트를 지원해주신 강환범님과 문용규 사장님께 특별한 감사를 드립니다.

이광춘 / 경기도 과천 / '14년 12월

### 감사의 말씀 {-#acknowledgement}

많은 어린이와 선생님 모두가 아이디어를 개선하도록 도움을 주셨습니다. 캐나다 브리티쉬 콜롬비아 빅토리아 사우스 파크 소재의 셜리 초등학교(Shirley Primary School), 이람 초등학교(Ilam Primary School), 뉴질랜드 크리스트 처치 웨스트번(Westburn Primary School)초등학교 선생님과 아이들이 초기 실험적 활동에 참여해 주셨습니다. 학습활동에 환대해 주셨으며, 여러 활동이 건설적으로 될 수 있도록 아낌없는 조언을 주신 Linda Picciotto, Karen Able, Bryon Porteous, Paul Cathro, Tracy Harrold, Simone Tanoa, Lorraine Woodfield, Lynn Atkinson 분께 특별한 감사의 말씀을 전한다. Gwenda Bensemann는 우리를 위해서 몇몇 활동을 시범적으로 수행해 주셨고, 변경 점에 대해서 조언을 주셨습니다. Richard Lynders, Sumant Murugesh 두 분은 학습활동을 도와주셨습니다. 일부 암호학 활동에서는 Ken Noblitz분이 도움을 주셨습니다. Kathy Beveridge 도움으로 Victoria “Mathmania”그룹활동 아래 몇몇 활동은 이루어졌습니다. 초기 삽화는 Malcolm Robinson, Gail Williams 도움을 주셨고, Hans Knutson으로부터의 조언도 도움이 되었습니다. Matt Powell도 언플러그드 프로젝트가 발전되는 동안 값진 도움을 주셨습니다. 이 책이 발전되는 초기단계 아낌없는 후원을 해주신 Brian Mason Scientific and Technical Trust에 무척 감사 드립니다.

도움이 되는 제안을 많이 해주시고 활동을 시범적으로 진행해 주신 Paul, Ruth Ellen Howard에 특별한 감사를 드립니다. Peter Henderson, Bruce McKenzie, Joan Mitchell, Nancy Walker-Mitchell, Gwen Stark, Tony Smith, Tim A. H. Bell , Mike Hallett, Harold Thimbleby는 많은 유용한 코멘트를 주셨습니다.

이 책이 있게 지원해준 가족 Bruce, Fran, Grant, Judith, Pam에게 많은 빚을 지고 있고, Andrew, Anna, Hannah, Max, Michael, Nikki는 이번 작업에 영감을 주었고 시범활동을 수행한 첫 아이들입니다.

언플러그드 프로젝트를 후원해고 자유롭게 다운로드될 수 있는 이 책을 만들게 해준 구글에 특별한 감사를 전합니다.
언플러그드 활동에 대해서 조언과 코멘트를 언제나 환영합니다. 저자들은 [csunplugged.org](http://csunplugged.org/)를 통해서 만날 수 있습니다.
