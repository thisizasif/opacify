# OPACITY  
Invisible Text Encoder / Decoder  

Encode readable text into pure invisibility.  
Decode zero-width text back to meaning.  
Runs entirely in your browser.

---

## ✦ What this is
Opacity converts normal text into **zero-width Unicode characters** that cannot be seen but still exist in the text stream.  
It also reverses the process with precision.

No servers.  
No storage.  
No noise.

---

## ✦ How it works
Each character is converted to binary.  
Binary digits are mapped to invisible Unicode symbols.  
Byte boundaries are preserved using a zero-width separator.

---

## ✦ Characters used
- `U+200B` Zero Width Space → `0`
- `U+200D` Zero Width Joiner → `1`
- `U+200C` Zero Width Non-Joiner → separator

---

## ✦ Features
- Encode and decode instantly  
- Copy input or result  
- Swap input and output  
- Live character count  
- Keyboard shortcuts  
- Responsive dark UI  

---

## ✦ Shortcuts
- **Ctrl / Cmd + Enter** → Encode  
- **Shift + Enter** → Decode  

---

## ✦ Usage
1. Enter text in **Input**
2. Encode to generate invisible text
3. Paste invisible text and decode to reveal it

---

## ✦ Tech stack
- HTML  
- CSS  
- JavaScript  
- Zero dependencies  

---

## ✦ Notes
Some platforms may sanitize or remove zero-width characters.  
Use for testing, learning, or controlled environments.

---

**Opacity**  
Text that exists without being seen.
