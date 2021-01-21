# (번역) Safari는 왜 evergreen browser가 아닌가요?

> 번역을 하게 된 시작은.. Chrome browser는 사용자가 강제로 업데이트를 막지 않으면 항상 최신 version의 chrome으로 자동 업데이트 됩니다. 즉, chrome browser는 항상 최신 버전을 유지합니다. 이를 기술 용어로 [evergreen browser](https://tomdale.net/2013/05/evergreen-browsers/)라고 합니다. 쉽게 이야기해서 항상 최신 버전으로 자동 업데이트되는 브라우저입니다. 대표적으로 Mozilla 재단의 Firefox와 Google의 Chrome browser가 있습니다. 그런데 Safari는 evergreen browser가 아니랍니다. 무려 Safari는 web browser 시장의 점유율 2위인데 말이죠([자료](https://gs.statcounter.com/browser-market-share)). 여기서 관련 자료를 찾던 중 좀 더 세심하게 알고자 번역을 시도하였습니다. 오역이 있더라도 양해해주세요. 저는 토종 한국인입니다.

## 사파리는 evergreen browser가 아닙니다.

> *를 붙힌 내용은 제가 번역하면서 조금 더 세심하게 표현하고 싶었던 부분입니다. 또한, 개발자로서 단순 번역이 아니라 조금 더 정확하게 표현해보고 싶었습니다. 오역이 있더라고 양해바랍니다. 오역에 대한 의견은 환경합니다! 

다양한 이유로 지난 몇 년 전보다 웹 개발자의 삶은 점점 더 편해지고 있습니다. 개발자들이 과거의 플랫폼 호환을 고민하지 않고 최신 기술을 사용할 수 있도록 해주는 [babel](https://babeljs.io)(javascript transpiler), [postcss autoprefixer](https://github.com/postcss/autoprefixer)와 같은 강력한 도구들이 있기 때문입니다. 그러나 웹은 항상 지저분한 곳(*** '파편화된 웹 환경'라고, 신사적으로 표현하고 싶습니다. 한편으론 얼마나 지저분했으면...**)이었고, 앞으로도 그럴 것입니다. 그리고 이 난장판(파편화된 웹 환경)을 완벽하게 추상화 시킬 수 있는 방법은 없습니다. 

본론으로 가서 저(원 저작자)는 safari를 새로운 IE(*** Safari 비하 발언이라고 생각합니다.**)라고 말한 사람은 아니지만 다음 사안들을 고려해보세요. 주요 브라우저(chrome, firefox)와 달리 safari는 evergreen browser가 아닙니다.

Safari는 Apple의 운영체제(OS X, iOS, iPad OS)에 종속적이며, Apple의 운영체제는 하드웨어 종속적입니다. 과거에는 이와 같은 사실을 무시해도 됐지만, 현 상황은 변하고 있습니다(***무시할 수 없는 상황에 왔습니다.**).

대부분의 Mac 사용자가 운영 체제를 별 생각없이 업데이트를 하던 때가 있었습니다; Mountain Lion(OS X 버전 이름)을 구동시킬 수 있는 컴퓨터(Mac book, iMac)에 Mavericks, Yosemite, 그리고 El Capitan가 지원되었습니다. 그로 인해, 웹 개발자들은 대부분의 맥 사용자들이 최신 버전의 Safari를 사용할 수 있다고 추측하였습니다.

위와 같은 부분은 Sierra(OS X 버전 이름)와 함께 변화하였습니다.















