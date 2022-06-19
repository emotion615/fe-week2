# Week 2 review

## 실습 1>

### -실습 1번의 과제는 Text 컴포넌트를 수정하는 문제였습니다.</br>

<br>다음 사진과 같이 const StyledText의 margin, font-size,color, font-weight, text-align을 props 주어 재사용성이 가능하도록 코드를 짜 보았습니다.</br>

<img width="60%" src="https://user-images.githubusercontent.com/102964287/174475395-946a16fc-555d-433e-ac7a-ab7c9e4fe923.png"/>

<br>-App.js에는 ./component/Text에서의 TextBox를 불러와 color, fontweight,fontsize를 "박서정"에 각각 적용되도록 지정해주었습니다.</br>

<img width="60%" src="https://user-images.githubusercontent.com/102964287/174475471-86a0580b-a866-4fe0-9641-e6b06aa3362f.png">

<br>-실행결과 다음과 같이 각각의 "박서정"이 화면상에 나타났습니다. color,fontweight, fontsize를 다르게 나타남을 확인할 수 있습니다.</br>

<img width="60%" src="https://user-images.githubusercontent.com/102964287/174475558-154bf10f-5778-4b43-84f2-f5c5896486ac.png"/>

## 실습 2>

### -실습 2번의 과제는 CardWrapper와 ColorWrapper를 각각 지정해준 후 색상코드를 입력하면 색상과 text가 나오는 카드를 만들어보는 문제였습니다.</br>

<br> 다음 사진과 같이 CardWrapper와 ColorWrapper에 관한 내용을 props 주고 글자는 실습1에서 사용한 TextBox를 사용하였습니다.
<br>- CardWrapper의 경우 border-radius만 props주고 나머지는 고정하였습니다.
<br> - ColorWrapper는 height와 broder만 고정해두고 나머지는 props해주었습니다.</br>

<img width="60%" src="https://user-images.githubusercontent.com/102964287/174475878-68de1881-7a83-4f10-88dc-ae87cc5664ae.png"/>

<br> 위에서 지정해준 CardWrapper와 ColorWrapper,Text박스를 ColorCard속에 적어두어 App.js에서는 ColorCard만 이용하여 각각의 카드를 변경시키도록 합니다.</br>

<img width="60%" src="https://user-images.githubusercontent.com/102964287/174475941-6aa31b22-78a4-471d-bc78-94123a5324ba.png"/>

<br> 다음은 결과값입니다.</br>
<img width="60%" src="https://user-images.githubusercontent.com/102964287/174475963-cea2e355-aecb-42a5-8ed3-9f2132d0d3b6.png"/>

## 실습 3>

### -대망의 실습 3!! 실습 3번에서는 Media Card 컴포넌트를 제작했습니다. 카드 각각의 사진과 Text, Button의 색상은 달리하는 조건이었습니다.

<br> 다음 사진과 같이 StyledCardWrapper, StyledImage, TextBox,StyledButton Mediacard로 한 번에 묶어서 나타낸 걸 볼 수 있습니다. </br>
<br> App.js에서는 실습1,2와 마찬가지로 MediaCard에 적을 내용들, 사진(URL)이용하여 각각의 미디어 카드를 만들어 주었다. </br>

<br>-tip) 이번에는 각각의 요소들을 index.js를 만들어서 적어줘서 "import ... from ../.."가 많았는데 하나의 index.js를 만들어서 한번에 적으면 귀찮음을 덜 수 있다는 것을 깨달았다...</br>

<img width="100%" src="https://user-images.githubusercontent.com/102964287/174476440-fa390363-4c51-4f57-925f-1f53637e2fb4.png"/>

<br> 다음과 같이 나온다!!! 두두둥 </br>
<br> 사실 사진이 카드만 나오고 사진이 안나와서 시간이 오래걸렸다.ㅜㅜ</br>
그리고 MediaCard를 만들면서 사진이나 Text, Button사이에 간격을 조절하고 싶어서 Margin에 props를 줘서 가능하도록 해주었다 ⭐⭐
<img width="60%" src="https://user-images.githubusercontent.com/102964287/174476729-bdb304c0-f160-48d8-907e-85be43a2a881.png"/>
