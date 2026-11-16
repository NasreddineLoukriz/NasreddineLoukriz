# Nasreddine Loukriz

**I build Flutter apps where the data never leaves the device** — on-device AI, end-to-end
encryption, and a cybersecurity background that shapes both.

Most "AI apps" are a screen in front of someone else's API. Mine run the model on the phone:
no audio, no transcript and no plaintext is uploaded, because there is nothing to upload.

---

## Featured work

### 🛡️ SYcore Guard — an offline privacy guard for text and voice

<img src="https://raw.githubusercontent.com/NasreddineLoukriz/sycore_guard/main/docs/img/hero.png" width="100%" alt="Three phone screens: a blocked message with its password masked, a locally transcribed voice note, and a spoken verdict">

Type or speak a message. On-device rules and a Qwen3-0.6B classifier decide whether it carries
a phone number, an email, a card number, an ID or a password — **block it, and hand it back
with the secrets masked**. Speech-to-text (Whisper-tiny) and the spoken verdict (Matcha-TTS)
are local too, as is the Arabic-Indic digit masking.

`Flutter 3.47` · `LiteRT-LM` · `Whisper` · `Matcha-TTS` · `fail-closed design` · `Arabic RTL`
→ **[NasreddineLoukriz/sycore_guard](https://github.com/NasreddineLoukriz/sycore_guard)**

### 🔐 SyCore — an encrypted storage layer your server cannot read

<img src="https://raw.githubusercontent.com/NasreddineLoukriz/SyCore/main/docs/img/app-en.png" width="360" alt="The SyCore Flutter client, paper-and-ink design with a message list">

AES-256-GCM on the client, a **blind FastAPI server** that stores ciphertext and holds no key,
cross-implementation conformance vectors, a Dart SDK and a Flutter client. The server cannot
decrypt a record even if it is fully compromised — that is a property of the design, not a
promise in a privacy policy.

`Dart` · `FastAPI` · `SQLite` · `AES-256-GCM` · `zero-trust boundaries`
→ **[NasreddineLoukriz/SyCore](https://github.com/NasreddineLoukriz/SyCore)**

### ⚡ Upstream: flutter_edge_ai

My change replaced the log-mel frontend's direct DFT with a Bluestein chirp-z FFT plus cached
windows and a sparse mel matmul — **482M trig calls per Whisper window** became two 1024-point
FFTs, with bit-identical output. Merged and shipped in `flutter_edge_ai_speech 0.6.1`
([PR #815](https://github.com/DenisovAV/flutter_edge_ai/pull/815)).

### 🤝 Team work: elFulk mobile app

Contributor on a feature-first Flutter codebase (bloc, go_router, freezed, dio): auth flows,
update management, and code review.

---

## What I'm good at

- **On-device inference in Flutter** — LiteRT/LiteRT-LM, Whisper, TTS, model install and
  memory budgeting on real Android devices, not just a demo on a laptop.
- **Privacy engineering** — what a threat model actually claims, where keys live, what
  "encrypted" is allowed to mean, and how to make failure modes fail closed.
- **Bilingual UI (Arabic/English, RTL)** — interfaces that a non-technical user trusts at a
  glance, not dashboards full of AI slop.

## Stack

`Dart` / `Flutter` · `Python` / `FastAPI` · `SQLite` · `LiteRT` · `ONNX` · `Docker` · `Linux`

**Studying:** Cybersecurity (Technicien Supérieur, INSFP) · **Open to:** freelance Flutter and
on-device AI work.

📫 [LinkedIn](https://www.linkedin.com/in/nasreddine-loukriz-185442435)
