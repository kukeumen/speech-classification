# age Dataset

### Change directory structure
**Original directory structure**
```bash
├── ksponspeech
│   ├── 자유대화 음성(노인남녀)
│   │   ├── Training
│   │   │   ├── [라벨]1.AI챗봇
│   │   │   ├── ...
│   │   │   ├── [원천]1.AI챗봇
│   │   │   ├── ...
│   │   ├── Validation</br
|   │   │   ├── [라벨]1.AI챗봇
│   │   │   ├── ...
│   │   │   ├── [원천]1.AI챗봇
│   │   │   ├── ...
│   ├── 자유대화 음성(소아, 유아)
│   │   ├── Training
│   │   │   ├── [라벨]1.AI챗봇
│   │   │   ├── ...
│   │   │   ├── [원천]1.AI챗봇
│   │   │   ├── ...
│   │   ├── Validation
│   │   ├── [라벨]1.AI챗봇
│   │   │   ├── ...
│   │   │   ├── [원천]1.AI챗봇
│   │   │   ├── ...
│   └── 자유대화 음성(일반남녀)
│   │   ├── Training
│   │   │   ├── [라벨]1.AI챗봇
│   │   │   ├── ...
│   │   │   ├── [원천]1.AI챗봇
│   │   │   ├── ...
│   │   ├── Validation
│   │   ├── [라벨]1.AI챗봇
│   │   │   ├── ...
│   │   │   ├── [원천]1.AI챗봇
│   │   │   ├── ...
└──────────────
```

**Changed directory structure**
```bash
├── ksponspeech
│   ├── 자유대화 음성(노인남녀)
│   │   ├── Training
│   │   │   ├── AI스피커
│   │   │   │   ├── Female  
│   │   │   │   └── Male  
│   │   │   ├── AI챗봇
│   │   │   │   ├── Female  
│   │   │   │   └── Male 
│   │   │   ├── 음성수집도구
│   │   │   │   ├── Female  
│   │   │   │   └── Male 
│   │   │   ├── 스튜디오
│   │   │   │   ├── Female  
│   │   │   │   └── Male 
│   │   ├── Validation
│   │   │   ├── AI스피커
│   │   │   │   ├── Female  
│   │   │   │   └── Male  
│   │   │   ├── AI챗봇
│   │   │   │   ├── Female  
│   │   │   │   └── Male 
│   │   │   ├── 음성수집도구
│   │   │   │   ├── Female  
│   │   │   │   └── Male 
│   │   │   ├── 스튜디오
│   │   │   │   ├── Female  
│   │   │   │   └── Male 
│   ├── 자유대화 음성(소아, 유아)
│   │   ├── Training
│   │   │   ├── AI챗봇
│   │   │   │   ├── Female  
│   │   │   │   └── Male 
│   │   │   ├── 음성수집도구
│   │   │   │   ├── Female  
│   │   │   │   └── Male 
│   │   │   ├── 스튜디오
│   │   │   │   ├── Female  
│   │   │   │   └── Male 
│   │   ├── Validation 
│   │   │   ├── AI챗봇
│   │   │   │   ├── Female  
│   │   │   │   └── Male 
│   │   │   ├── 음성수집도구
│   │   │   │   ├── Female  
│   │   │   │   └── Male 
│   │   │   ├── 스튜디오
│   │   │   │   ├── Female  
│   │   │   │   └── Male 
│   ├── 자유대화 음성(일반남녀)
│   │   ├── Training
│   │   │   ├── AI챗봇
│   │   │   │   ├── Female  
│   │   │   │   └── Male 
│   │   │   ├── 음성수집도구
│   │   │   │   ├── Female  
│   │   │   │   └── Male 
│   │   │   ├── 스튜디오
│   │   │   │   ├── Female  
│   │   │   │   └── Male 
│   │   ├── Validation 
│   │   │   ├── AI챗봇
│   │   │   │   ├── Female  
│   │   │   │   └── Male 
│   │   │   ├── 음성수집도구
│   │   │   │   ├── Female  
│   │   │   │   └── Male 
│   │   │   ├── 스튜디오
│   │   │   │   ├── Female  
│   │   │   │   └── Male 
└──────────────
```
