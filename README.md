# TTS_Finetune
## Install
```
git submodule init
cd TTS
pip install -e '.[all,dev,notebooks]'
pip install -r TTS/demos/xtts_ft_demo/requirements.txt
cd ..
```

## Finetuning
```
python TTS/TTS/demos/xtts_ft_demo/xtts_demo.py
```
