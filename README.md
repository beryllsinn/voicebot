# 음성 비서 프로그램

이 프로젝트는 음성 인식(STT), 대화 생성(GPT), 음성 출력(TTS) 기능을 통합한 스트림릿 기반 음성 비서 프로그램입니다.

## 기능

- **STT(Speech-to-Text)**: OpenAI Whisper 모델을 사용하여 음성을 텍스트로 변환합니다.
- **GPT 기반 응답**: OpenAI GPT 모델을 사용하여 입력된 질문에 대한 응답을 생성합니다.
- **TTS(Text-to-Speech)**: Google Translate TTS를 사용하여 텍스트 응답을 음성으로 출력합니다.
- **UI**: Streamlit을 사용하여 간단한 웹 UI를 제공합니다.

## 설치 방법

1. 이 리포지토리를 클론합니다:
  git clone https://github.com/beryllsinn/voicebot.git
2. 필요한 패키지를 설치합니다:
  pip install -r requirements.txt
3. OpenAI API 키를 환경 변수로 설정합니다:
  export OPENAI_API_KEY='your-api-key'


## 사용 방법
1. 프로젝트 디렉토리로 이동하여 Streamlit 앱을 실행합니다:
  streamlit run app.py
2. 웹 브라우저에서 제공된 로컬 주소로 접속하여 음성 비서 프로그램을 사용할 수 있습니다
