# MidiDrumpad

Código-fonte e firmware para microcontrolador Arduino implementando um controlador MIDI percussivo (Drumpad). Detecta toques em botões/pads e converte em sinais MIDI USB para acionamento de instrumentos em DAWs (Ableton Live, FL Studio, Reaper).

## 🛠️ Tecnologias

- **Arduino C/C++**
- **MIDI Protocol**
- **DAW Integration**

## 📂 Estrutura do Projeto

- `MidiDrumPad.ino`: Sketch principal do Arduino com mapeamento das notas e canais MIDI.
- `Buttons.cpp` & `Buttons.h`: Biblioteca para leitura e debounce dos pads físicos.

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).
