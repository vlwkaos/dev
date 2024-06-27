## r.w

blog of vlwkaos.
Curated articles with personal note.

### Highlight

- [웹 텍스트 에디터 개발 가이드 (WIP)](웹%20텍스트%20에디터%20개발%20가이드%20(WIP).md)

---

### Archive

- (2024-06-18) [UndefinedToOptionalParameter](https://stackoverflow.com/questions/72449057/how-can-i-make-an-undefined-parameter-not-required) #typescript 
- (2024-06-16) [이정도면 충분한 설계를 하는 방법](https://www.georgefairbanks.com/book/) #software-design
	- 내가 항상 하는 고민과 너무 닮은 부분을 공략해주는 책이다. 추상 레이어를 잘 설계하려고 해도, 다른 개발자가 그런 형태의 개발 (개인적인 생각으로는 이런식으로 레이어를 쌓고 아키텍팅 하는 것 자체를 이해하고 실행하는 개발자는 매우 적은 것 같다.)을 이해하지 못한다면, 결국 그 추상화를 깨버리고 low-level API를 이용해버린다. 아직 완성해나가는 단계에 있다면, 그 조금의 차이로 설계 전체의 목적이 깨질 수 있다. 아키텍팅을 이해하는 사람이라면 당장의 구현을 위해 코드를 짜는 것이 아니라 어떻게 변경하면 좋을지를 논의하러 와야한다고 생각한다. 
	- 또한 저자의 말처럼 언어를 잘하는 것과 설계를 잘하는 것에는 차이가 있다. 둘을 구분하지 못하는 사람은 언어적으로는 뛰어난 최적화된 코드를 작성할 순 있지만, 프로젝트의 장기적 관점에서 어떻게 작성해야 할지 올바르게 이해하지 못하는 경우를 많이 보았다. 가장 빠르고 짧은 것이 답이 아닌 경우가 많기 때문이다. 개발은 혼자하는것이 아니기 때문에 좀 더 인본주의적으로 접근할 필요가있다.
	- 선언적 지식의 모순: 조금 반발이 있을 수 있는 의견이지만, 디자인 패턴과 같은 책이 특정 개념을 구체화하고 명명하는 이유는 그것을 학습 차원에서 전파하려는 목적보다, 이미 현실의 것들을 추상화하는 과정에서 자연스럽게 특정 형태로 가공할 수 있는 능력을 가진 사람들이 그렇게 하지 못하는 사람들에게 자신의 개념의 또렷하게 전달하고자 하는데에 있다고 생각한다. 어떠한 선언적 지식 없이 스스로 어떤 형태가 나은지 판단하여 그렇게 해보지 못한이상, 지식을 아무리 학습해봐야 적절한 상황에 그런 패턴을 적용하지 못한다는 것을 너무 자주 봐왔기 때문이다.
- (2024-06-10) [WebKit fix: Quirk news.ycombinator to skip TextAutoSizing](https://news.ycombinator.com/item?id=40631439)
	- 우리가 웹킷을 싫어하는 이유가 여기 모두 있다. 이는 웹킷의 웹스펙 구현 코드가 적절히 설계되지 못했다는 반증이다. 웹킷은 웹호환을 위해 올바른 스펙 구현이 아니라, 유명한 사이트별로 예외 로직을 짜버렸고, 깨진 창문이 보수되는 일은 없었다. 프로젝트 관리가 지속되기 위해서는 정말 많은 노력이 필요하고, 문서를 이용하든 뭐든 개발 배경 컨텍스트(히스토리)의 연속성이 한번이라도 깨지면 '바꿔야하는', '새로 만들어야하는' 소프트웨어가 되어버린다. 
- (2024-05-20) [XYProblem](http://mywiki.wooledge.org/XyProblem)
	- 요즘은 정확한 원인 분석과 근거에 의해 개발을 하기보다, 잘 동작한다는 현상에 기대어 뭔가를 만드는 사람들이 많아진 것 같다. 최근의 다양한 개발 도구나 패러다임은 효율을 가져다주는 동시에 개발자들의 원인파악 능력을 떨어트린 것 같다는 생각이 든다.
- (2024-05-06) [Simplicity is An Advantage but Sadly Complexicy Sells Better](https://eugeneyan.com/writing/simplicity/)
	- 복잡한 문제를 복잡하게 해결하는 것은 잘하는게 아니다. 엔지니어라면 자주 빠지게 되는 함정인 것 같다. 해결하려는 문제의 범주를 정확하게 인지하고 붙들고 있어야하는데, 여러 생각이 꼬리를 물면서 문제를 키우는 경우를 많이 보는 것 같다. 결국 본인이 해결하고 있는 과정이 처음 문제의 정의와는 멀어지는 것이다.
- (2024-05-01) predicate #typescript
- (2024-04-27) [How I rewired my brain to become fluent in math](https://nautil.us/how-i-rewired-my-brain-to-become-fluent-in-math-235085/)
	- 이해만을 강조하는 교육 체계에서 반복학습을 통한 유창함의 중요성을 강조한다. 처음 유학 생활을 하며 영어를 배웠을 때가 생각난다. 다른 과목의 시험을 공부하기 위해 교과서의 문장을 전부 단순 암기 했었는데, 이렇게 암기를 하는 과정 중 문장들의 패턴이 익숙해지며 문법을 자연스레 터득한 것같다.
- (2024-04-26) [Make invalid states unrepresentable](https://geeklaunch.io/blog/make-invalid-states-unrepresentable/) #software-design 
	- 값의 변형을 좀 더 엄격하게 관리하기 위해 최근에 고민하던 패턴인데, 게임쪽에서는 이미 잘 알려진 구조조인 것 같다. 스토어 위주 상태관리만이 팽배한 지금 다른 개발자들에게 값의 상태관리를 어떻게 다르게 제어할 수 있는지 모호하게만 설명했었는데, 이 자료로 대체할 수 있을 듯. 항상 드는 생각이지만, 디자인 패턴의 용어는 소통을 위해 나온 것이지 학습은 위해 나온건 아닌 것 같다. 이 주제에 대해서는 나중에 다룰 예정이다.
- (2024-04-26) [DOM attribute vs properties](https://jakearchibald.com/2024/attributes-vs-properties/) #web-api
	- 당연하다고 생각했지만 자세하게 들여다보지 않으면 놓치기 쉬운 부분을 알려준다.
- (2024-04-25) [근시안은 청소년기에 시작되는 에피데믹인가](https://theconversation.com/nearsightedness-is-at-epidemic-levels-and-the-problem-begins-in-childhood-225255)
- (2024-04-23) [Typescript - distribute type over union to make intersection](https://stackoverflow.com/questions/63401066/distribute-a-generic-type-over-a-union) #typescript
	- [Typescript - distributive conditonal types](https://www.typescriptlang.org/docs/handbook/2/conditional-types.html#distributive-conditional-types) 여기를 보면 분배법칙으로 union type을 확장할 수 있는데, 분배를 통해 intersection type으로 확장하는 방법은?
- (2024-04-14) [HTMX and the Rule of Least Power](https://blog.gypsydave5.com/posts/2024/4/12/htmx-and-the-rule-of-least-power/)
	- 요즘 배보다 배꼽이 커지는 툴체인을 보며 항상 드는 생각
- (2024-04-13) [웹 텍스트 에디터 개발, 어떤 형태가 좋을지에 대한 답변](notes/웹%20텍스트%20에디터%20개발,%20어떤%20형태가%20좋을지에%20대한%20답변.md)
- (2024-02-27) [Write Dumb Code](https://matthewrocklin.com/write-dumb-code.html) #cleancode
	- 장기 프로젝트를 진행하며 많이 공감하는 내용이 담겨있는 글. 모든 코드는 결국 비용이다.
- (2024-02-24) (DRAFT) [지속가능한 프로젝트 운영방법?](notes/지속가능한%20프로젝트%20운영방법?.md)
- (2024-02-23) [Nobody Ever Gets Credit for Fixing Problems that Never Happened](https://web.mit.edu/nelsonr/www/Repenning=Sterman_CMR_su01_.pdf) #management #work-process