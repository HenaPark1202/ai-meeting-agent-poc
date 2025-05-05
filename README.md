# ai-meeting-agent-poc
KT DS / MS AI Tech team

# 1.목표
- 회의(실시간/배치 녹음파일) STT, 화자분리
- 회의 요약(전체 및 주제별), 화자별 액션제안

# 2.구성



# 3.모드별 상세 설명
### realtime
- Speech SDK ConversationTranscriber
- 회의종료시) Ctrl+C 혹은 "이제 회의를 종료하겠습니다."
- 결과: results/

### batch
- Speech Batch Transcription API
- 결과: results/

# Code

```
git clone
cp [개인 파일].env .env
pip install -r requirmrent.txt
python -m src.main --mode realtime //실시간 회의 STT,화자분리
python -m src.main --mode batch --input data/conf_3min.wav //배치파일 STT,화자분리

```
