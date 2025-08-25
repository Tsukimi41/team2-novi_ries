# team2--
game-narration-mvp/  
├── main.py                  # 全ての処理を呼び出す実行スクリプト  
├── video_analyzer.py        # 映像解析モジュール (OpenCV, YOLO)  
├── narration_generator.py   # ナレーション原稿生成モジュール (GPT API)  
├── tts_client.py            # 音声合成モジュール (Google TTS API)  
├── config.py                # APIキーや設定を管理  
├── .env                     # APIキーを記述 (gitignore対象)  
├── requirements.txt         # 依存ライブラリ一覧  
├── models/  
│   └── yolov5s.pt           # YOLOv5の学習済みモデル  
├── input_videos/  
│   └── sample.mp4           # 解析対象の動画ファイル  
└── output_audios/  
    └── sample_narration.mp3 # 生成された音声ファイル  

