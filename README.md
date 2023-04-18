# OpenAI

## OpenAI API 를 이용한 예제

- openai 설치
<br> openai 버전은 0.27.0 이상, python 3.7.1 이상 에서 만 ChatCompletion.create 함수를 이용할 수 있다
<br> openai doc 참고: https://platform.openai.com/docs/api-reference/completions/create?lang=python
```
pip install openai           # openai 설치 
```
```
pip install --upgrade openai # 필요시, openai 업데이트
pip show openai              # 필요시 openai 버전 확인  
python -m pip --version 
```
- OpenAI API 예제

|소스명|설명|기타|
|:-----------------|:-----------------------------------------------------------|:---------------------|
|[chat_test](https://github.com/kobongsoo/OpenAI/blob/master/chat_test.ipynb)|ChatCompletion 예제|openapi key 필요|
|[document preprocessing](https://github.com/kobongsoo/OpenAI/blob/master/document%20preprocessing.ipynb)|문서 전처리 예제|openapi key 필요|
|[embedding](https://github.com/kobongsoo/OpenAI/blob/master/embedding.ipynb)|임베딩 예|openapi key 필요|
|[image_test](https://github.com/kobongsoo/OpenAI/blob/master/image_test.ipynb)|DALL-E와 Kario를 이용한 이미지 생성 예|openapi key / kakao api key 필요|
|[LlamaIndex_test](https://github.com/kobongsoo/OpenAI/blob/master/LlamaIndex_test.ipynb)|라마 인덱스를 이용항 GPT 인덱싱 예제|openapi key|
|[LlamaIndex_test_googledoc](https://github.com/kobongsoo/OpenAI/blob/master/LlamaIndex_test_googledoc.ipynb)|라마 인덱스와 구글 DOC 를 이용항 GPT 인덱싱 예제|openapi key/google doc key 필요|
|[langchain_agent_ex](https://github.com/kobongsoo/OpenAI/blob/master/langchain_agent_ex.ipynb)|Langchain 프레임워크를 이용한 gpt 연동 예|Google Serper 도구 API 키 필요|

- LangChain은 Language Model로 구동되는 애플리케이션을 개발하기 위한 프레임워크.
<br>Langchain 에 대한 자세한 내용은 [여기](https://python.langchain.com/en/latest/) 참조
```
pip install langchain
# or
conda install langchain -c conda-forge
```
