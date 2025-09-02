## Assistente Virtual por Voz (Colab/CPU) — STT + TTS + Ações
# Sistema de assistência virtual feito em Python no Google Colab (100% CPU) com:
- STT (fala → texto) via SpeechRecognition (Google)
- TTS (texto → fala) via gTTS (pt-BR)
- Ações por voz: Wikipedia, YouTube, farmácia mais próxima (Maps com - - - geolocalização), Google e previsão do tempo
- Fallback quando o microfone está bloqueado: seleção de arquivo de áudio ou comando por texto

## ✨ Funcionalidades
- Text-to-Speech (TTS): voz pt-BR com gTTS
- Speech-to-Text (STT): captura microfone no navegador e transcrição com SpeechRecognition
- Ações por voz (exemplos):
wikipedia <termo> / o que é <termo> / resumo <termo>
youtube <termo>
farmacia [cidade] (usa geolocalização se o usuário permitir)
google <termo>
tempo [cidade]
ajuda, sair
- Fallbacks:
Se o navegador negar microfone: upload/arquivo de áudio
Uso por texto para testar intents sem áudio
