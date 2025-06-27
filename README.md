1일차 25.06.23

vscode extensions 설치:
1. jupyter
2. jupyter notebook
2. jupyter-notebook-vscode
4. python
5. python Debugger


https://bit.ly/4lguyKT
https://drive.google.com/drive/folders/1tHMk1YbsFsdLr-3DV8yFmkKqSW0N7x1s

python 3.11


가상환경 활성화 : py -m venv llm
C:\LLM\1stDay_code-20250623T002322Z-1-001\1stDay_code 폴더에서 
./llm/Scripts/activate

deactivate



모델이 저장된 로컬 경로:
C:\Users\Administrator\.cache\huggingface\hub\models--meta-llama--Llama-3.2-1B-Instruct\snapshots\9213176726f574b556790deb65791e0c5aa438b6


perplexity

LLM은 다음에 올 단어를 예상하는 방식으므로 할루시네이션 발생

-- 프리젠테이션 만드는 사이트
감마
https://gamma.app/create

2일차 실습1 에서 사용할 키값



1. 필수패키지

%pip install faiss-cpu

===2일차 

2일차 25.06.24

https://tinyurl.com/yjyxpzy3

백터db : https://tinyurl.com/889h6pw5

pip install -r requirements.txt



pip install tool_calls




pip install langchain_chroma

langchain_chroma


include_domains=["naver.com","github.io","wikidocs.net"],

로또 번호 생성기를 출력하는 코드를 작성하세요


langchain 에서....   stream과 invoke 차이점


with open(self.file_path, encoding=self.encoding) as f:


 임베딩은 단어나 문장 같은 텍스트 데이터를 저차원의 연속적인 벡터로 변환하는 과정입니다.




===3일차 25.06.25==






== 4일차 25.06.26

https://tinyurl.com/326xe7nw


pip install langchain_teddynote
pip install pdfplumber






==== test ===
langchain 목적  LLM응용프로그램을 위함 프레임웍

chain 이란? 컴퍼넌트 순차적 연결

랭그래프-랭체인과 비교의 주요이점...  상태관리 복잡한 워크플러우 지원

랭체인 에이전트 .....    도구를 사용하여 작업을 완료하는결정을 내리는 LLM

lcel  . 컴퍼넌트 연결

그래프 내에 실행가능한 작업단위

랭그래프 프롬프트 템플릿 주요기능    ...   동적으로


랭그래프 상태관리 주오방식 ....  상태머신


랭체인 리액트 패턴 ..... 리즈닝+액팅

랭체인 에서 툴 .... 에이전트가 특정작업을 수행할수 인ㅆ는 함수 

랭체인 리트리뷰 컴퍼넌트... 관련문서나 정보 검색 

백터저장소가 랭체인에서 중요한 이유  ... 의미적 유사성 기반 검색 지원 

랭체인 임베트... 텍스트를 백터값으로 변환

rag ㅈ주요목적...  llm 응답을 외부지식으로 보강

랭그래프 status .... 워크플로우 현재상태와 컨텍스트 관리

워크플로우 중간에 사람의 입력이나 

랭그래프 상태변경....... 리두서 함수

랭그래프 컨디션널 엣지.... 조건에 따라 워크플로의 다음단계


랭그래프  persistance는 무엇을 제공하는가 ... 워크플로우 지속적 저장

랭그래프 트래딩 ... 여려대화의 병렬처리



















