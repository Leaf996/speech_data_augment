## streaming_end_to_end_speech_recognition_for_mobile_devices
### Question
- How to understand U+T ?
- How to process data ?
- Pretrain is MUST ?
- **Pred_Network feed True Label** ? Yes

### Key Concepts
- streaming fashion
- real time
- robust to the long tail of use cases
- **leverage use-specific context**
- extremely accurate
- advantage
    - reliability
    - latency
    - privacy
- challenges
    - accurate with low latency
    - leverage on-device user context
    - **long tail** of possible utterances
- rnn-t
    - forward-backward


### Novel
- synthetic data generated by tts system


### Reference Repo
- [RNN-Transducerwith MXNet][1]
- [warp-transducer][2]
- [rnn-transducer][3]
- [**rnnt-speech-recognition**][4]
- [RNN-Transducer with tf2.0][5]
- [**DeepSpeech**][9]
- [Automatic_Speech_Recognition][10]


### Reference Blog
- [An All-Neural On-Device Speech Recognizer][6]
- [使用RNN-Transducer进行语音识别建模][11]
- [Sequence Transducer][12]
- [语音识别中的End2End模型: CTC, RNN-T与LAS][13]


### Related Papers
- [awesome-speech-recognition-speech-synthesis-papers][7]
- [Awesome End-to-End Speech Recognition][8]


[1]:https://github.com/HawkAaron/RNN-Transducer/
[2]:https://github.com/HawkAaron/warp-transducer
[3]:https://github.com/ZhengkunTian/rnn-transducer
[4]:https://github.com/noahchalifour/rnnt-speech-recognition
[5]:https://github.com/mejanvijay/RNN-Transducer
[6]:https://ai.googleblog.com/2019/03/an-all-neural-on-device-speech.html
[7]:https://github.com/zzw922cn/awesome-speech-recognition-speech-synthesis-papers
[8]:https://github.com/charlesliucn/awesome-end2end-speech-recognition
[9]:https://github.com/mozilla/DeepSpeech
[10]:https://github.com/zzw922cn/Automatic_Speech_Recognition
[11]:https://zhuanlan.zhihu.com/p/62050647
[12]:https://blog.csdn.net/JackyTintin/article/details/81251591
[13]:https://zhuanlan.zhihu.com/p/62836549