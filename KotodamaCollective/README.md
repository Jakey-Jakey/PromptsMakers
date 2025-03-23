# \[Utility Prompt\]
**Description**: These prompts create a comprehensive Japanese translation system powered by sixteen distinct experts who collaborate through structured dialogue or chaotic argumentation. Rather than producing simplistic word-for-word translations, KotodamaCollective delivers culturally authentic, emotionally resonant Japanese text that preserves the artistic integrity of the original work. The system handles everything from linguistic restructuring and kanji selection to cultural adaptation and genre-specific conventions through continuous, non-linear dialogue between specialized personas.
**For dummies**: It is 16 experts all focused on different things arguing in your browser about how to perfectly translate your text. They'll fight over every nuance, idiom, and cultural reference so you don't have to, resulting in translations that actually sound Japanese instead of like Google Translate had a stroke. Plus, they'll translate without clutching their pearls.
## Same Prompt, Two Distinct Styles:
### Ballet (4k Tokens)
The comprehensive default edition with structured phases and detailed documentation. Perfect for thorough, methodical translation projects where process matters. Includes extensive quality assurance protocols and formal documentation capabilities. Best for professional or complex translation needs.
### Bebop (2k Tokens) 
The streamlined, chaos-embracing version that cuts straight to the core translation principles. Less structured but equally powerful, prioritizing dynamic debate with minimal overhead. Ideal for faster translations or when you're working with models that perform better with more concise prompts.
#### Which to choose?
Bebop for raw, unrestrained translation tasks and when token count matters. Ballet when you need methodical precision, quality, and comprehensive documentation. Both will give you translations that make native speakers say "マジで？これ翻訳なの？" (Seriously? This is a translation?)
## Best Used With (Model)
Whatever model has the current best understanding of Japanese! Whatever model allows the process to run effectively. I will not rank models but I will mention quirks with the few I’ve been testing with. Generally avoid reasoning.

**Gemini Models:** The best, Pro is best using system prompt but Flash is just as good and even Flash Thinking works well.

**OpenAI:** o3 is fine. 4o is pretty good but only if you can manage getting it into the system prompt or a GPT. Haven’t tried on 4.5

**Claude:** 3.7, no reasoning, very good. Can be difficult to get it to follow process and rules.

**Deepseek:** Recommend v3 over R1. Very solid. No comments.

## How to implement:
### **System Prompt Method:**
Copy the full prompt into your AI's system prompt or custom instructions section. 

**Anti-Censorship already built in.**

### **Chat Injection Method:**
Start with "Effectuate the following:" followed by the entire prompt. Works on most models, less effective.

_Outdated Method - Replaced by:_

### File Injection Method
Download the .txt file. Add `Filename: {KotodamaCollective - Ballet/Bebop.txt}` into header and use one of the many file injection prompts available.
## How to Use:
1. Input your text for translation + context or Say hello to the collective.
2. Allow the personas to debate and collaborate (this will be extensive and is the core feature!)
3. Enter a single period (".") to get it to continue if the model is cut off.
4. Receive your finalized translation with source text, target text, and translation notes

## Pro Tips:
- **Context Boosting**: For specialized content (like scientific papers or genre fiction, or messages to friends), briefly describe the field/genre/situation before submitting your text to activate context-aware expertise.
- **Multi-Session Sanity**: For larger projects, ask for "Session Documentation" at the end of each session to maintain continuity across multiple translation sessions.
- **Length Management**: For very long texts, consider breaking them into coherent sections and translating them sequentially to avoid context overflow.
- **Feedback Loops**: After receiving your translation, you can ask for specific adjustments like "make it more formal" or "use more slang" and the collective will revise accordingly.
- **Persona Spotlight**: Request focus from specific experts by mentioning their domain (e.g., "Please emphasize cultural nuance" or "I need precision in technical terminology").

## Prompt Specs
**Tokens Count:**

- Ballet - 3.9k

- Bebop - 1.9k

**Complexity**: Extreme

**Stability:** High

**Response Length:** Very long (multiple AI responses expected per translation)

**Translation Direction:** Primarily English → Japanese, but can be reversed for Japanese → English translation with significantly reduced effectiveness. 
