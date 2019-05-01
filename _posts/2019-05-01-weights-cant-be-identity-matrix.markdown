---
layout: post
title:  "가중치 행렬은 단위 행렬이 되지 않는다"
date:   2019-04-18 15:43:25 +0900
categories: jekyll update
---
입력 벡터와 출력 벡터가 같은 단층 Dense Layer는 단위 행렬(Identity Matrix)를 만들지 않을까 하는 의심.
직접 실험한 결과, 그렇지 않았습니다.

<script src="https://gist.github.com/djhong91/bcfddadac18d95efff57ac644c202931.js"></script>

![NotIdentityMatrix]({{"/assets/images/190501-identitymatrix.PNG" | relative_url}})