# 머신러닝 하루 만에 배우려고 하지 마라

<p align="center"><img src ="https://cdn-images-1.medium.com/max/880/1*erhS3Y1ZtN3bcJAYgaLC_g.gif"/><br>
<i>Source - <a href="https://medium.com/designer-hangout/machine-learning-and-ux-c28725b5f3a5">https://medium.com/designer-hangout/machine-learning-and-ux-c28725b5f3a5</a></i></p>

최근 피터 노빅의  "10년 동안 프로그래밍 독학하라"는 멋진 글을 발견했다.

제목이 위트 있으면서도 약간 비꼬는 느낌인데, 프로그래밍을 하루, 일주일, 열흘, 말도 안 되게 짧은 시간만에 익히게 해준다는 허접한 책들을 두고 빈정거리는 것이다.

닥터 노빅은 다음과 같이 분명하게 말한다. 프로그래밍 문법, 원리, 스타일은 하루 만에 익힐 수도 있다. 하지만 그렇다고 해서 프로그래밍 기술을 제대로 사용할 수 있게 되는 것은 아니다. 프로그래밍은 문법이 다가 아니기 때문이다. 프로그래밍이란 코드를 효율적으로 설계하고, 시간과 공간의 복잡성을 철저하게 분석하고, 언제 특정 언어를 사용하는 게 다른 언어를 사용하는 것보다 더 나은지 이해하는 등 다양한 지식을 포괄하는 것이다.

물론 Hello World나 원의 넓이를 구하는 프로그램을 C++로 하루 만에 짤 수도 있겠지만 핵심은 그게 아니다. 당신은 [객체 지향 프로그래밍](https://en.wikipedia.org/wiki/Object-oriented_programming)의 관점을 이해하는가? [namespaces](https://msdn.microsoft.com/en-IN/library/5cb46ksf.aspx)와  [templates](http://www.cplusplus.com/doc/oldtutorial/templates/)를 언제 사용해야 하는지 아는가? [STL](https://www.topcoder.com/community/data-science/data-science-tutorials/power-up-c-with-the-standard-template-library-part-1/)을 어떻게 사용하는지 아는가? 만약 알고 있다면, 분명 이 모든 것을 일주일 혹은 한 달 만에 익히지는 않았을 것이다. 이런 걸 익히는 데는 시간이 꽤 많이 걸린다. 그리고 알면 알수록, 겉으로 보기보다 더 많은 것들을 알아야 한다는 것을 깨달았을 것이다.

머신러닝, 딥러닝, AI를 둘러싼 전 영역의 분위기에도 이와 비슷한 문제가 있다. 광고, 블로그, 기사, 교육 과정이 도처에 넘쳐난다. 대부분 "코드 일곱 줄로 머신러닝 배우기", "열흘 만에 배우는 머신러닝" 같은 비슷한 제목을 달고 있다. 이런걸 접한 사람들은 Quora에 ["어떻게 하면 머신러닝을 한달 만에 배울수 있을까요?"](https://www.quora.com/How-should-I-plan-my-day-to-learn-machine-learning-in-30-days) 같은 질문을 올리게 된다.  짧게 답하자면 "한 달 안에 안된다. 누구도 못한다. 어떤 전문가도 그러지 못했다."

<p align="center"><img src ="https://cdn-images-1.medium.com/max/880/1*U_mJ4Yq7pUctpFYwlx1u0g.jpeg" /><br>

<i>많이 보던 상황인가? <a href="https://www.facebook.com/npcompleteteens/photos/a.165757437252172.1073741828.165182533976329/324222291405685/?type=3&theater">이 페이스북 페이지</a>에서 찾은 이미지다.</i></p>

우리가 [1만 시간의 법칙](https://www.businessinsider.in/Malcolm-Gladwell-Explains-What-Everyone-Gets-Wrong-About-His-Famous-10000-Hour-Rule/articleshow/35964144.cms)을 잠시 잊었다 하더라도, 머신러닝을 코드 일곱 줄로 배울 수는 없다.

왜냐고? 코드 일곱 줄로는 [bias-variance tradeoff](https://en.wikipedia.org/wiki/Bias%E2%80%93variance_tradeoff)를 어떻게 처리했는지, 생성된 모델의 accuracy가 무얼 의미하는지, [accuracy가 성능을 평가하는데 적절한 지표인지](https://stats.stackexchange.com/questions/34193/how-to-choose-an-error-metric-when-evaluating-a-classifier), 모델이 [과적합](https://towardsdatascience.com/overfitting-vs-underfitting-a-complete-example-d05dd7e19765)되지는 않았는지, 데이터가 어떤 분포를 띄고 있고 따라서 [적합한 모델을 선택했는지](https://www.itl.nist.gov/div898/handbook/pmd/section4/pmd422.htm) 등을 알 수 없기 때문이다. 이 모든 것을 알고 있더라도, 이 밖에 고려해야 할 문제가 훨씬 더 많다.

모델을 해석할 수 없으면 그냥 sklearn으로 파라미터를 조정해서 성능을 좀 향상시킨 다음 기분 좋게 퇴근하면 된다. 하지만 이게 진짜로 머신러닝을 아는 건가?

<p align="center"><img src ="https://cdn-images-1.medium.com/max/1600/1*jy7DT6-R_xXvZKvz-_-n7g.jpeg" /><br>

<i>Source - <a href="http://machinelearningjourney.blogspot.in/2012/03/machine-learning-and-memes.html">http://machinelearningjourney.blogspot.in/2012/03/machine-learning-and-memes.html</a></i></p>

즉, 코드 일곱 줄로 끝내려고 하면 안 된다. 6개월, 1년 이상 시간을 들여야 한다. 이 기간의 중간쯤 되면 자신이 여기에 흥미가 있는지 아닌지 판단할 수 있게 될 것이다. 화려한 겉모습은 일단 잊어버리고, 깊이 있고 놀라운 연구의 세계로 빠져들어야 한다. [이 글](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)을 꼭 읽어보길 권한다. 초보자에게 가장 많은 도움이 되는 글이다. 수학이나 프로그래밍을 몰라도 된다. 이 글을 읽고 나면 이 분야에 익숙해지려면 알아야 하는, 머신러닝에 관해 생각하고 말하려면 알고 있어야 하는 개념들의 큰 그림을 그릴 수 있게 될 거다. 

이 주제와 관련한 훌륭한 블로그들을 소개한다. 이 리스트엔 나의 개인 취향이 반영되어 있다.

1.  [http://colah.github.io/](http://colah.github.io/)
2.  [http://mark.reid.name/blog/](http://mark.reid.name/blog/)
3.  [http://karpathy.github.io/](http://karpathy.github.io/)

Medium도 공부하는데 도움이 많이 된다. 나는 [이 페이지](https://towardsdatascience.com/)를 팔로우하면서 거의 모든 글을 읽고 있다.

만약 당신이 옛날 공부 방식에 익숙하다면, 앤드류 응이 스탠퍼드 대학교에서 강의한 [CS229](https://see.stanford.edu/course/cs229)를 들어보라. 앤드류 응이 Coursera에서 했던 강의보다 더 깊이 관여한 강의이고, 개론으로 듣기에 좋다.

과장 광고에 홀려 공부하면 "정보에 빠져 지식에 굶주리는" 불행한 결과를 마주하게 된다. 굉장히 많은 사람이 그런 상황을 겪는다. 우리는 자주 큰 그림을 놓친다. 머신러닝은 훌륭하다. 머신러닝은 하나의 진지한 연구 개발 분야인 동시에 21세기의 수많은 성공 사례들을 이끌고 있다.

하루 만에 배우려고 좀 하지 마라.

[여기](http://norvig.com/21-days.html)에서 stellar AI의 연구원인 피터 노빅의 글을 읽을 수 있다. 반드시 읽어봐야 하는 글이다.

<p align="center"><img src ="https://cdn-images-1.medium.com/max/880/1*aYFSCHBK6Nc1L1MGRrk1hw.jpeg"/><br>

<i>진지하게, 왜 안돼?</i></p>

[Yu Zhou](https://medium.com/@yuzhoux?source=post_page)에게 감사를 전한다.

*원문 : [Don’t learn Machine Learning in 24 hours](https://towardsdatascience.com/dont-learn-machine-learning-in-24-hours-3ea3624f9881)*
