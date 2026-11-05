<h1 align="center" style="margin:0;">
  <a href="https://unsloth.ai/docs"><picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/unslothai/unsloth/main/images/unsloth%20logo%20white%20text.png">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/unslothai/unsloth/main/images/unsloth%20logo%20black%20text.png">
    <img alt="Logo Unsloth" src="https://raw.githubusercontent.com/unslothai/unsloth/main/images/unsloth%20logo%20black%20text.png" height="80" style="max-width:100%;">
  </picture></a>
</h1>
<h3 align="center" style="margin: 0; margin-top: 0;">
Unsloth to pierwsza aplikacja desktopowa do uruchamiania i trenowania modeli AI.
</h3>

<p align="center">
  <a href="./README.md">English</a> · <b>Polski</b>
</p>

<p align="center">
  <a href="#-funkcje">Funkcje</a> •
  <a href="#-szybki-start">Szybki start</a> •
  <a href="#-co-oznacza-nazwa-unsloth">Znaczenie nazwy</a> •
  <a href="https://unsloth.ai/docs">Dokumentacja</a>
</p>

## 🦥 Co oznacza nazwa "Unsloth"?

Nazwa **Unsloth** (wym. *an-slof*) to gra slow oparta na dwoch angielskich elementach:

- **sloth** — leniwiec (zwierze) lub lenistwo
- **un-** — przedrostek oznaczajacy zaprzeczenie, odwrocenie stanu

Po polsku mozna to przetlumaczyc jako **"odleniwic"** — przeciwienstwo lenistwa, czyli przejscie na pelne obroty.

Nazwa jest celowa ironia: tradycyjne trenowanie duzych modeli jezykowych (LLM) jest bardzo wolne i zasobozerne — niczym leniwiec. Unsloth ma to **odleniwic**, przyspieszajac trening nawet **2-5x** przy **70% mniejszym zuzyciu pamieci VRAM**, bez utraty dokladnosci.

## ⚡ Szybki start

Pobierz natywna aplikacje Unsloth Desktop:

| Platforma | Pobieranie |
| --- | --- |
| **Windows** | [Pobierz](https://github.com/unslothai/unsloth/releases/latest/download/Unsloth-Desktop-Windows.exe) |
| **macOS** | [Pobierz](https://github.com/unslothai/unsloth/releases/latest/download/Unsloth-Desktop-MacOS.dmg) |
| **Linux / Ubuntu (deb)** | [Pobierz](https://github.com/unslothai/unsloth/releases/latest/download/Unsloth-Desktop-Ubuntu.deb) |
| **Linux / Ubuntu (ARM64)** | [Pobierz](https://github.com/unslothai/unsloth/releases/latest/download/Unsloth-Desktop-Ubuntu-ARM64.deb) |
| **Linux (AppImage)** | [Pobierz](https://github.com/unslothai/unsloth/releases/latest/download/Unsloth-Desktop-Linux.AppImage) |
| **Windows (ARM64)** | [Pobierz](https://github.com/unslothai/unsloth/releases/latest/download/Unsloth-Desktop-Windows-ARM64.exe) |

Pobierz z [Unsloth](https://unsloth.ai/download) lub [GitHub Releases](https://github.com/unslothai/unsloth/releases).

Instalacja reczna:

#### macOS, Linux, WSL:
```bash
curl -fsSL https://unsloth.ai/install.sh | sh
```

#### Windows:
```powershell
irm https://unsloth.ai/install.ps1 | iex
```

#### Docker:
Obraz [Unsloth Docker](https://hub.docker.com/r/unsloth/unsloth) `unsloth/unsloth` jest dostepny na Docker Hub. [Przeczytaj przewodnik.](https://unsloth.ai/docs/get-started/install/docker)

#### Homebrew:
```bash
brew install --cask unsloth
```

#### Winget (Windows):
```powershell
winget install --id UnslothAI.Unsloth -e
```

## ⭐ Funkcje

Unsloth dziala na **Windows, Linux, WSL** i **macOS**. Obsluguje **konfiguracje multi-GPU, karty NVIDIA, AMD, Intel, procesory CPU** oraz backend **Vulkan**.

### Uruchamianie i budowanie z AI
* Uruchamiaj i trenuj modele LLM, MLX, GGUF, dyfuzyjne, decyzyjne, embeddingowe i audio
* **Agenci i narzedzia:** Uzywaj lokalnych modeli z Claude Code, Codex i MCP, wlacznie z wywolywaniem narzedzi i wykonywaniem kodu
* **Wyszukiwanie i RAG:** Prywatne i nieograniczone wyszukiwanie w sieci, deep research, auto-kompaktowanie i RAG
* **Obraz i wideo:** Uruchamiaj i trenuj modele dyfuzyjne oraz multimodalne
* **Zdalnie i LAN:** Dostep do lokalnych modeli z dowolnego urzadzenia przez LAN lub zdalnie przez bezpieczne Cloudflare HTTPS
* **Polaczenia:** Serwuj modele przez API kompatybilne z OpenAI. Podlacz subskrypcje ChatGPT/Codex i dostawcow chmurowych

### Trenowanie i wdrazanie
* **Fine-tuning:** Trenuj modele 2x szybciej z 70% mniejszym VRAM bez utraty dokladnosci
* **Pelne wsparcie:** RL, LoRA, QLoRA, pelny fine-tuning, pretraining, GRPO, DPO i FP8
* **Eksport i wdrazanie:** Eksportuj modele do formatow GGUF, NVFP4, FP8 i innych
* **Zestawy danych:** Tworzenie zbiorow danych z plikow PDF, CSV, DOCX z Data Recipes

## 🚀 Unsloth Start

[Unsloth Start](https://unsloth.ai/docs/integrations/unsloth-start) laczy Claude Code, Codex i innych agentow z lokalnymi modelami jednym poleceniem.

```bash
unsloth start claude --model unsloth/Qwen3.8-27B-GGUF:UD-Q4_K_XL
```

| Agent | Polecenie |
| --- | --- |
| Claude Code | `unsloth start claude` |
| OpenAI Codex | `unsloth start codex` |
| Visual Studio Code | `unsloth start vscode` |

## 🤝 Spolecznosc

- [Discord](https://discord.gg/unsloth)
- [𝕏 (Twitter)](https://x.com/UnslothAI)
- [Reddit](https://reddit.com/r/unsloth)

## 📜 Licencja

Szczegoly licencji znajduja sie w plikach [LICENSE](./LICENSE) i [COPYING](./COPYING).
