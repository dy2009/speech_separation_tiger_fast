# speech_separation_tiger_fast
## **33x faster inference speed of Tiger model, Speech Separation**


Speed on CPU:

| Model Name  | CPU RTF (binding 1 cpu core) |
|--------|--------|
|       Tiger Large  |    3.9 |
|       Tiger Fast v1  |     **0.12** |


effect on EchoSet:

| Model Name  | SDRi | SI-SDRi |
|--------|--------|
|       Tiger Large  |     14.22   | 13.73 |
|       Tiger Fast v1  |   12.75     | 12.35 |


train:
python train.py
test:
python test.py -m model.ckpt


Package include 8k and 16k model:
tiger_fast_v1_8k
tiger_fast_v1_16k


get train code and pretrained model:
kongdw8@gmail.com
