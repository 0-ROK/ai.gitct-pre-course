# 인공지능 사관학교 프리코스 과제 목차

## 1주차 과제 (2020.06.02)

인공지능은 현재 다양한 제품과 서비스에서 사용되고 있는데요. 4가지 분야에서의 사례를 조사해 보았습니다.

### 언어

자연재해, 전쟁 등의 상황으로 인류의 역사를 담은 진귀한 문서들은 언제든 파괴될 수 있습니다. 이를 방지하기 위해 학자들은 오래된 고문서들을 스캔하여 디지털화하고 있습니다. 이러한 **언어학 연구**에 사진상의 문자를 인식하는 **OCR(Optical Character Recognition), 광학식 문자 인식** 기술이 사용됩니다.

일본의 **쿠주시지(Kuzushiji)**라는 스크립트는 필기체 서체로 쓰였기 때문에 극히 일부분의 전문가만이 읽을 수 있는 데다가 그 양 또한 수백만권에 이르기 때문에 이를 읽기 위한 시간과 노력이 매우 많이 필요합니다. 따라서 이를 대신하기 위한 AI 모델이 연구되었습니다.

일본의 **인문학 오픈 데이터센터**의 **타린 클라누왓**, **일본 국립정보연구소**의 **아사노부 키타모토**, **몬트리올 학습 알고리즘 연구소**의 **알렉스 램**이 공동으로 연구를 진행했고, 이들이 만들어낸 모델인 구로넷의 평균 정확도는 85%에 이른다고 합니다. 이 외에도 고대 인도 언어인 **산스크리트어** 등 다양한 언어학 연구에 인공지능이 사용되고 있습니다.

_[출처 : nVIDIA 블로그](https://blogs.nvidia.co.kr/2019/06/19/japanese-texts-ai/)_

### 음성

**TTS(Text To Speech)** 기술은 텍스트 데이터를 음성으로 읽어주는 기술입니다. 네이버의 인공지능 플랫폼 **클로바(Clova)**에 탑재된 **nVoice**는 네이버에서 자체적으로 개발한 TTS입니다.  기존의 **UTS(Unit-selection Text-to-Speech)** 기술은  한 사람의 목소리를 자연스럽게 구현해내기 위해 40시간 이상의 녹음 시간이 필요했습니다.  네이버의 nVoice는 그들이 개발한 **HDTS(Hybid DNN Text-to-Speech)** 기술을 통해 단 4시간의 녹음으로도 배우 유인나 씨의 목소리를 매우 자연스럽게 구현해냈습니다. 인공지능 기술은 음성이 필요한 곳에 성우 없이 혹은 더 적은 녹음 시간으로 음성을 적극적으로 활용할 수 있게 하고 있습니다.

_[출처 : 네이버(주)](https://www.navercorp.com/promotion/pressReleasesView/30240), [aitimes](http://www.aitimes.kr/news/articleView.html?idxno=12956)_

### 이미지

![1-1](https://user-images.githubusercontent.com/54888076/83895406-9b8a9780-a78d-11ea-8c36-406f4f811693.png)


인공지능은 과거 인간의 전유물로만 여겨졌던 창작활동에도 도전하고 있습니다. 구글은 2015년, **예술 스타일의 신경 알고리즘(A Neural Algorithm of Artistic Style)**이라는 논문을 발표했습니다. 논문에서 구현한 모델에 사진을 입력하면 해당 사진을 반 고흐, 뭉크 등 유명 화가의 화풍으로 사진을 순식간에 재구성합니다. 비슷한 시기에 나온 고흐 화풍의 애니메이션 영화 <러빙 빈센트>가 제작기간 10년에 6만장이 넘는 작품으로 제작된 것과 대조적이죠. 

![1-2](https://drive.google.com/file/d/188wSdYIMTZKuow6eC0eAdldFNZRJUIzL/view?usp=sharing)

구글은 또한 인공 신경망 기술을 사용하여 **딥드림(Deep Dream)** 모델 또한 만들었습니다. 이 모델은 입력된 사진 속 패턴을 분석해 물체를 인식합니다. 그 다음 이미지를 조작하여 다양한 패턴을 추가해 새로운 이미지를 창조해냅니다.

인공지능은 기존의 흑백 사진을 컬러로 변환해 주거나, 강아지 사진을 마치 실제 촬영된 것처럼 그럴듯하게 만들어내는 등 놀랍게 발전하고 있습니다.

_출처 : [동아비즈니스리뷰](https://dbr.donga.com/article/view/1303/article_no/9290), [A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576)_

### 자율주행

**자율주행**은 운전자의 조작 없이 자동차 스스로 운행이 가능하게 하는 기술입니다. 자율주행은 카메라, 라이더 센서, 적외선 센서 등으로 구현됩니다. 이 중 특히 카메라를 통해 촬영된 수많은 주행 영상 데이터들을 **인공 신경망(Neural Network)**을 통해 학습시키며 발전해나가고 있습니다. **구글 웨이모**, **GM 크루즈**, **포드 오토노머스 비히클즈** 등이 선구적으로 연구를 수행해나가고 있습니다. 양산형 모델에서 가장 앞선 수준의 자율주행기능을 구현하고 있는 **테슬라**의 **오토 파일럿**은 테슬라의 차량을 통해 계속하여 데이터를 축적하고 발전하여 업데이트되고 있습니다.

*출처 : [연합뉴스](https://www.yna.co.kr/view/AKR20190322175300003), [M오토데일리](https://www.autodaily.co.kr/news/articleView.html?idxno=417029), [LG CNS](https://blog.lgcns.com/1997)*

