# 오픈 API란?

오픈 API(Open Application Programming Interface, Open API, 공개 API) 또는 공개 API는 개발자라면 누구나 사용할 수 있도록 공개된 API를 말하며, 개발자에게 사유 응용 소프트웨어나 웹 서비스의 프로그래밍 적인 권한을 제공한다. 반대말은 프라이빗 API(Private API)다. 쉽게 말하면, "하나의 웹 사이트에서 자신이 가진 기능을 이용할 수 있도록 공개한 프로그래밍 인터페이스가 오픈 API다"라고 정의할 수 있다.

## 특징
- 개방성: 오픈 API는 누구나 사용할 수 있도록 공개되어 있습니다. 개발자들은 해당 API를 활용하여 자신의 소프트웨어나 웹 서비스에 기능을 추가할 수 있습니다.
- 프로그래밍 권한 제공: 오픈 API는 개발자들에게 프로그래밍적인 권한을 제공합니다. 이를 통해 개발자들은 API를 호출하고 데이터를 가져오거나 서비스의 기능을 활용할 수 있습니다.
- 데이터 형식: 주로 JSON(JavaScript Object Notation)이나 XML(Extensible Markup Language) 형식을 사용하여 데이터를 주고 받습니다. 이러한 형식을 통해 데이터를 쉽게 구조화하고 해석할 수 있습니다.
- 반대 개념: 프라이빗 API(Private API)는 제한된 범위의 사용자만 접근할 수 있는 API를 말합니다. 일반적으로 내부 시스템이나 서비스 간의 통신에 사용됩니다.

![image](https://github.com/HunMyeong/AndroidOpenAPI/assets/102712296/07ce2d8c-b4c0-4826-9771-9c7a225151cb)

어떠한 방식으로 정보를 요청해야 하는지, 그리고 그러한 요청을 보냈을 때 어떠한 형식으로 무슨 데이터를 전달받을 수 있는지를 정확히 알고 있어야한다.

API 결과(데이터) 제공 형식: 주고 받는 데이터 형식은 주로 "JSON", "XML"입니다. 요청의 결과로 받는 데이터의 구조에도 통일감을 줄 수 있도록 공통의 포맷을 정한 것인데요. 최근은 JSON이 많이 쓰이고 있습니다.
![2](https://github.com/HunMyeong/AndroidOpenAPI/assets/102712296/68caba60-b3db-469c-8c30-7f27bfc4d3d9)

JSON 형식은 다음과 같은 특징을 가지고 있습니다:

- key / value 구조
- 쌍따옴표를 사용하여 key값이나 문자열을 표기
- 객체, 배열 등의 표기 가능
- 중첩 가능
- 데이터 형식으로는 null, number, string, array, object, boolean 사용 가능

![요청](https://github.com/HunMyeong/AndroidOpenAPI/assets/102712296/1ab04aac-1b53-45ed-80ba-c481ecb86e74)

### 요청 예시
- 필수 입력 값
- 추가 설정 가능한 값

![응답](https://github.com/HunMyeong/AndroidOpenAPI/assets/102712296/4582e69b-ae0f-484b-b4d4-ec6693e49d8d)

### 응답 예시
응답은 다음과 같은 형식으로 제공됩니다:
- 응답 필드(KEY: VALUE): 어떤 이름으로 어떤 값(형태)이 전달되는지 상세히 설명됩니다.
이를 통해 코드를 작성하여 원하는 항목의 값(VALUE)을 가져올 수 있습니다.


# 테스트 결과 [ PPT 참고 ]
