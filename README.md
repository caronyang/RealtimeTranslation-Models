# RealtimeTranslation - Model weights

本 repo 只放 **RealtimeTranslation** 用到的模型權重，程式碼在
caronyang/RealtimeTranslation（私有）。

模型以 GitHub Releases 的資產形式提供，**依版本分路徑**：

- tag `v1.1.1` → 1.1.1 版安裝程式會下載的模型

## 內容

| 檔案 | 用途 | 大小 |
|---|---|---|
| models-asr-medium.tar | faster-whisper medium（遠端/final 辨識） | 1.46 GB |
| models-asr-base.tar | faster-whisper base（逐字 + 本地輕量） | 141 MB |
| models-mt-nllb600.tar | NLLB-200 distilled 600M CT2 int8 | 617 MB |
| models-tts-kokoro.tar | Kokoro multi-lang v1.0（語音輸出） | 383 MB |
| models-vad.tar | Silero VAD v5 | 2 MB |
| models-samples.tar | 測試音檔 | 1 MB |

## 授權

| 模型 | 授權 |
|---|---|
| faster-whisper (Whisper) | MIT |
| Kokoro | Apache-2.0 |
| Silero VAD | MIT |
| **NLLB-200** | **CC-BY-NC-4.0（非商業使用）** |

NLLB-200 為非商業授權，商業使用請自行確認。