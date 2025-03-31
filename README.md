```bash
git clone https://github.com/voiceflow-gallagan/llmlingua-api.git
cd llmlingua-api
pip install -r requirements.txt
export MODEL=microsoft/llmlingua-2-xlm-roberta-large-meetingbank
uvicorn app:app --port 10000 --host 0.0.0.0
```

