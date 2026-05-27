# 🌊 MindWave — Rastreador de Meditação

PWA para rastrear sessões de meditação com 3 fases baseadas em neurociência, Bluetooth para frequência cardíaca, contador de respiração e relatório estilo hipograma do sono.

## Fases (Neurociência)

| Fase | Onda | Hz | FC | Respiração | Cor |
|---|---|---|---|---|---|
| 🔵 Alfa | Ondas Alfa | 8–14 Hz | 65–80 bpm | 8–12 resp/min | Azul |
| 🟣 Teta | Ondas Teta | 3–7 Hz | 55–68 bpm | 4–7 resp/min | Roxo |
| 🟦 Delta | Ondas Delta | 0.5–3 Hz | 45–60 bpm | 2–5 resp/min | Índigo |

## Funcionalidades

- 📡 Bluetooth para monitor cardíaco (Heart Rate LE)
- 🌬️ Contador de respiração manual (toque a cada expiração)
- 🧠 Detecção automática de fase por FC + Respiração combinados
- ⏱️ Timer com fase ativa em destaque e cores por estado
- 📊 Relatório final completo:
  - Score 0–100
  - Hipograma minuto a minuto (estilo ciclo do sono)
  - Tempo e % por fase
  - FC média, máxima, mínima + gráfico
  - Respiração média, máxima e mínima
- 📱 PWA — instala como app nativo
- 🌊 Ícone com 3 ondas nas cores das fases

## Como subir no GitHub Pages

1. Crie um repositório no GitHub
2. Faça upload dos 3 arquivos: `index.html`, `sw.js`, `README.md`
3. Vá em **Settings → Pages → Branch: main → Save**
4. Acesse: `https://SEU-USUARIO.github.io/NOME-DO-REPO`

## Instalar no celular

**Android (Chrome):** Banner aparece automaticamente → toque **Instalar**

**iPhone (Safari):** Compartilhar → **Adicionar à Tela de Início**

## Bluetooth

> ⚠️ Web Bluetooth requer HTTPS. GitHub Pages fornece HTTPS automaticamente.
> Funciona no Chrome Android e Edge. Safari iOS não suporta Web Bluetooth.

Compatível com: Polar H10, H9, Garmin HRM-Dual, Wahoo TICKR e qualquer monitor Bluetooth LE Heart Rate Profile.
