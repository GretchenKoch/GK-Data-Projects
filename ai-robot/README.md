
## 📁 `ai-robot/` (Voice assistant on Raspberry Pi)

## Goal
Build a voice-controlled AI robot using a Raspberry Pi, microphone, and speaker. It should be able to:
- Listen to voice input
- Process input using a chatbot model (e.g., GPT)
- Speak the response using text-to-speech

## Status
📦 Project planned, not yet started. Currently focusing on data analysis and app development.

## Dependencies (future)
- Python 3
- `speech_recognition`
- `pyttsx3` or `gTTS`
- OpenAI or Hugging Face `transformers`

## Stretch Goals
- Servo motor for movement
- LED responses
- Wake-word activation

## 🛠 Possible Stack:

| Function              | Tool                                          | Notes                                            |
|-----------------------|-----------------------------------------------|--------------------------------------------------|
| Speech-to-text        | `speech_recognition`                          | Wraps Google Speech API, others optional         |
| Text-to-speech        | `pyttsx3`, `gTTS`, or Hugging Face TTS        | Offline or online options                        |
| Brain (chatbot model) | `transformers`, `openai`, or rule-based logic | Start with small responses                       |
| Interaction control   | Plain Python                                  | All tied together with simple logic              |
| Optional robot motion | GPIO + `gpiozero` or `pigpio`                 | If you want servos later                         |
