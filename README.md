# Akahs models

On-device model files used by the Akahs apps (downloaded on request, never bundled).

## ggml-small-khmer-q5_1.bin

Khmer speech recognition for whisper.cpp — the "Accurate" Khmer option in Akahs Memo.

- Source model: [seanghay/whisper-small-khmer-v2](https://huggingface.co/seanghay/whisper-small-khmer-v2) by Seanghay Yath — a fine-tune of OpenAI's whisper-small on Google FLEURS, OpenSLR SLR42 and km-speech-corpus.
- Licence: Apache-2.0 (see LICENSE). Unmodified weights, converted to ggml with whisper.cpp's `convert-h5-to-ggml.py` and quantized to q5_1 with `whisper-quantize`.
- SHA-256: `283dcbee4b9e7e6725aa0546ca169064bef20c1f732d0ad5486c3478cfb13102`
- Size: 190,085,504 bytes
