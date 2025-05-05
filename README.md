# ai-meeting-agent-poc
KT DS / MS AI Tech team

# 1.목표
- 회의(실시간/배치 녹음파일) STT, 화자분리
- 회의 요약(전체 및 주제별), 화자별 액션제안

# 2.구성



# 3.START

```
git clone
cp [개인 파일].env .env
pip install -r requirmrent.txt
python -m src.main --mode realtime //실시간 회의 STT,화자분리
python -m src.main --mode batch --input data/conf_3min.wav //배치파일 STT,화자분리

```
