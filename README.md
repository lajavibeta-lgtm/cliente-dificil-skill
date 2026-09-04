# El Cliente Difícil / The Difficult Client

**Pon a prueba tu estrategia antes de presentársela al cliente.**  
**Pressure-test your strategy before your client does.**

Una skill bilingüe para equipos de agencia, estrategas, creativos, cuentas y consultores. Convierte Claude, Gemini u OpenAI/Codex en un cliente exigente que cuestiona una propuesta con un máximo de cinco preguntas y luego muestra qué está listo y qué necesita trabajo.

A bilingual skill for agency teams, strategists, creatives, account leads, and consultants. It turns Claude, Gemini, or OpenAI/Codex into a demanding client who challenges a proposal with up to five questions, then shows what is ready and what still needs work.

La skill detecta si escribes en español o inglés y realiza toda la sesión en ese idioma. También puedes pedir el idioma explícitamente.

The skill detects whether you write in Spanish or English and runs the full session in that language. You can also request a language explicitly.

## Qué hace / What it does

- Elige el perfil más relevante / Chooses the most relevant profile: **CFO**, **Skeptic**, **Busy CMO**, **Operator** or **Political Stakeholder**
- Usa tres niveles de presión / Uses three pressure levels: **Supportive**, **Skeptical** or **Brutal**
- Hace hasta cinco preguntas, una por una / Asks up to five questions, one at a time
- Adapta cada reto a tus respuestas / Adapts every challenge to your answers
- Entrega un diagnóstico final / Delivers a final verdict:
  - Lo que sobrevive / What survives
  - Lo que el cliente cuestionará / Client will challenge
  - Esto podría matar la propuesta / This could kill the proposal
  - Un argumento más sólido / Stronger framing
  - Nivel de preparación / Client Readiness Score

Una sesión suele tomar 7–10 minutos. / A session usually takes 7–10 minutes.

## Cómo usarla / How to use it

### Claude

Añade la carpeta `cliente-dificil` como Skill si tu entorno admite Skills. Si no, agrega `SKILL.md` a un Project o pega su contenido antes de tu propuesta.

Add the `cliente-dificil` folder as a Skill if your environment supports Skills. Otherwise, add `SKILL.md` to a Project or paste its contents before your proposal.

### OpenAI / Codex

Coloca la carpeta `cliente-dificil` en tu directorio de skills de Codex e invócala por su nombre. También puedes adjuntar o pegar `SKILL.md` en una conversación de ChatGPT u OpenAI.

Place the `cliente-dificil` folder in your Codex skills directory and invoke it by name. You can also attach or paste `SKILL.md` into a ChatGPT or OpenAI conversation.

### Gemini

Usa `SKILL.md` como las instrucciones de un Gem o pega el archivo en una conversación antes de tu propuesta.

Use `SKILL.md` as the instructions for a Gem, or paste the file into a Gemini conversation before your proposal.

Los nombres de funciones y las opciones para importar archivos pueden variar. La alternativa universal es usar `SKILL.md` como instrucciones de la conversación.

## Inicia una sesión / Start a session

**Español**

> Pon a prueba esta estrategia de campaña. El cliente debe aprobar un piloto de $150K. La principal stakeholder es una CMO adversa al riesgo que duda que la marca impulse ventas. Usa el modo Skeptical.

**English**

> Stress-test this campaign strategy. The client needs to approve a $150K pilot. The main stakeholder is a risk-averse CMO who doubts that brand activity drives sales. Use Skeptical mode.

Puedes adjuntar un deck, pegar una propuesta o describir la idea. Si omites el nivel de presión, la skill usa **Skeptical**.

You can attach a deck, paste a proposal, or describe the idea. If you omit the pressure level, the skill uses **Skeptical**.

Consulta [`example.md`](example.md) para ver un ejemplo bilingüe. / See [`example.md`](example.md) for a bilingual example.

## Medición de descargas / Download measurement

Descarga el ZIP desde la Release de GitHub. GitHub registra un `download_count` para cada asset, ofreciendo una señal simple y sin registro de la intención de descarga.

Download the ZIP from the GitHub Release. GitHub records a `download_count` for every release asset, providing a simple, registration-free signal of download intent.

El número mide descargas, no instalaciones ni sesiones completadas. / It measures downloads, not installations or completed sessions.

## Contenido / Package contents

```text
cliente-dificil/
├── SKILL.md
├── README.md
└── example.md
```

## Version

1.0.0
