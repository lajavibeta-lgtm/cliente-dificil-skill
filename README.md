# El Cliente Difícil / The Difficult Client

**Pon a prueba tu estrategia antes de presentársela al cliente.**  
**Pressure-test your strategy before your client does.**

Una sola skill, dos idiomas. Detecta si escribes en español o inglés y realiza toda la sesión en ese idioma. También puedes pedir el idioma explícitamente.

One skill, two languages. It detects whether you write in Spanish or English and runs the entire session in that language. You can also request a language explicitly.

## Cómo funciona / How it works

El Cliente Difícil convierte Claude, Gemini u OpenAI/Codex en un cliente exigente. Elige el perfil que representa el mayor riesgo para tu propuesta —**CFO, Auditor de evidencia, Busy CMO, Operator o Political Stakeholder**— y hace hasta cinco preguntas adaptativas. Antes de comenzar, confirma por separado el perfil elegido y el nivel de presión.

The Difficult Client turns Claude, Gemini, or OpenAI/Codex into a demanding client. It selects the profile that represents the greatest risk to your proposal—**CFO, Evidence Challenger, Busy CMO, Operator, or Political Stakeholder**—and asks up to five adaptive questions. Before starting, it confirms the selected profile and pressure level separately.

### Nivel de presión / Pressure level

- 🟢 **Supportive** — constructivo y fácil de responder / constructive and easier to answer
- 🟡 **Skeptical** — directo, exige lógica y evidencia / direct, requiring logic and evidence
- 🔴 **Brutal** — máxima presión sobre afirmaciones débiles / maximum pressure on weak claims

### Diagnóstico final / Final verdict

- 🟢 **Lo que sobrevive / What survives** — las partes más sólidas
- 🟡 **Lo que el cliente cuestionará / Client will challenge** — objeciones que puedes preparar
- 🔴 **Esto podría matar la propuesta / This could kill the proposal** — riesgos que pueden impedir la aprobación
- 🛠️ **Un argumento más sólido / Stronger framing** — una mejor forma de presentar la idea
- 📊 **Nivel de preparación / Client Readiness Score** — puntuación transparente de 0 a 100

---

## 🇪🇸 Instrucciones en español

### Claude

1. Descarga el ZIP desde la sección **Releases** de este repositorio.
2. En Claude, activa **Ejecución de código y creación de archivos** desde **Configuración → Capacidades**.
3. Ve a **Personalizar → Skills**.
4. Selecciona **+ → Crear skill → Cargar una skill**.
5. Sube el ZIP y activa **El Cliente Difícil**.
6. Abre un chat, comparte tu propuesta y escribe:

> Pon a prueba esta estrategia. El cliente debe aprobar el presupuesto y duda que la idea genere resultados de negocio. Usa el modo 🔴 Brutal.

Si tu versión de la plataforma no permite cargar skills, pega el contenido de `SKILL.md` como instrucciones antes de compartir tu propuesta.

### Gemini

Usa `SKILL.md` como las instrucciones de un Gem o pégalo en una conversación antes de tu propuesta.

### OpenAI / Codex

Coloca la carpeta `cliente-dificil` en tu directorio de skills de Codex e invócala por su nombre. También puedes adjuntar o pegar `SKILL.md` en una conversación.

---

## 🇬🇧 Instructions in English

### Claude

1. Download the ZIP from this repository's **Releases** section.
2. In Claude, enable **Code execution and file creation** under **Settings → Capabilities**.
3. Go to **Customize → Skills**.
4. Select **+ → Create skill → Upload a skill**.
5. Upload the ZIP and enable **The Difficult Client**.
6. Open a chat, share your proposal, and write:

> Pressure-test this strategy. The client must approve the budget and doubts that the idea will generate business results. Use 🔴 Brutal mode.

If your platform version does not support skill uploads, paste the contents of `SKILL.md` as instructions before sharing your proposal.

### Gemini

Use `SKILL.md` as the instructions for a Gem, or paste it into a conversation before your proposal.

### OpenAI / Codex

Place the `cliente-dificil` folder in your Codex skills directory and invoke it by name. You can also attach or paste `SKILL.md` into a conversation.

## Contenido / Package contents

```text
cliente-dificil/
├── SKILL.md
├── README.md
└── example.md
```

## Version

1.0.2
