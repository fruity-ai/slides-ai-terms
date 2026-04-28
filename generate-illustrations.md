# Image Generation Prompts — AI Terminology Slides

Use these prompts with an image generator (DALL-E, Midjourney, etc.).
All images should be **1024x576** (16:9) to match the slide layout.

Copy each prompt as-is. The style reference is consistent across all prompts.

---

## Style reference (prepend to each prompt if the tool supports style refs)

> Pixel art, 16-bit retro gaming aesthetic, warm cozy lighting, detailed dithering, side-view perspective, dark navy/purple background on left half and warm indoor scene on right half, nostalgic but modern subject matter

---

## 1. AI — `ai-illustration.png`

```
Pixel art 16-bit retro style, split composition. Left side: a glowing tree diagram showing branches labeled "vision", "language", "robotics" growing from a trunk labeled "AI", dark navy background with green/cyan glow. Right side: a friendly robot and a human sitting across from each other at a wooden desk in a cozy office, warm lamp light, bookshelves in background. Detailed pixel dithering, nostalgic 16-bit gaming aesthetic. 1024x576 resolution, no text.
```

## 2. LLM — `llm-illustration.png`

```
Pixel art 16-bit retro style, split composition. Left side: a glowing brain made of flowing streams of tiny text characters and words, connected by neural pathways with pulsing light, dark navy background. Right side: a retro computer monitor showing cascading text being generated word by word, a character watching in awe, cozy room with warm lighting and plants. Detailed pixel dithering, nostalgic 16-bit gaming aesthetic. 1024x576 resolution, no text.
```

## 3. Token — `token-illustration.png`

```
Pixel art 16-bit retro style, split composition. Left side: a sentence being sliced into colorful puzzle pieces by a laser on a conveyor belt, each piece glowing a different color, dark navy background with mechanical gears. Right side: a character at a desk with a magnifying glass examining individual puzzle pieces, a counter display showing numbers ticking up, cozy room with warm lighting. Detailed pixel dithering, nostalgic 16-bit gaming aesthetic. 1024x576 resolution, no text.
```

## 4. Prompt — `prompt-illustration.png`

```
Pixel art 16-bit retro style, split composition. Left side: a character carefully writing a detailed scroll/letter with multiple sections highlighted in different colors (green for instructions, yellow for context, blue for examples), dark navy background. Right side: a glowing mailbox shaped like a robot head receiving the letter, with sparkles coming out showing a perfect response being generated, cozy room with warm lighting. Detailed pixel dithering, nostalgic 16-bit gaming aesthetic. 1024x576 resolution, no text.
```

## 5. Hallucination — `hallucination-illustration.png`

```
Pixel art 16-bit retro style, split composition. Left side: a confident retro computer presenting a book on a pedestal with a spotlight, but the book is glitching and pixelating, showing it's not real, dark navy background with warning symbols. Right side: a character at a desk fact-checking with real books and documents, a green checkmark appearing over verified items and red X over fake ones, cozy room with warm lighting. Detailed pixel dithering, nostalgic 16-bit gaming aesthetic. 1024x576 resolution, no text.
```

## 6. Agent — `agent-illustration.png`

```
Pixel art 16-bit retro style, split composition. Left side: a character at a command center with multiple glowing screens showing a task list, a planning board with connected nodes, and tool icons on the wall, dark navy background with purple accent lighting. Right side: the same character now executing tasks autonomously - sending messages, reading files, updating systems - all happening simultaneously, cozy room with warm lighting and organized desk. Detailed pixel dithering, nostalgic 16-bit gaming aesthetic. 1024x576 resolution, no text.
```

## 7. RAG — `rag-illustration.png`

```
Pixel art 16-bit retro style, split composition. Left side: a character pulling glowing documents from a large retro filing cabinet, the documents floating through a beam of light into a computer, dark navy background with cyan/green data streams. Right side: the computer screen showing a perfect answer being assembled from the retrieved document fragments like a jigsaw puzzle, cozy room with warm lighting and stacked books. Detailed pixel dithering, nostalgic 16-bit gaming aesthetic. 1024x576 resolution, no text.
```

## 8. Tool — `tool-illustration.png`

```
Pixel art 16-bit retro style, split composition. Left side: a glowing workbench with digital tools hanging on hooks - a magnifying glass, wrench, envelope, globe, database cylinder - each tool pulsing with its own color, dark navy background. Right side: a robot character selecting and using one tool at a time from the workbench to complete tasks on a retro computer, cozy workshop with warm lighting and organized shelves. Detailed pixel dithering, nostalgic 16-bit gaming aesthetic. 1024x576 resolution, no text.
```

## 9. Skills — `skills-illustration.png`

```
Pixel art 16-bit retro style, split composition. Left side: a character wearing multiple hats stacked on their head (detective hat, chef hat, hard hat, graduation cap), each representing a different skill, surrounded by floating tool icons, dark navy background with star particles. Right side: the same character now transformed into a specialist at a desk, using a specific combination of tools expertly to complete a complex task, cozy office with warm lighting and certificates on wall. Detailed pixel dithering, nostalgic 16-bit gaming aesthetic. 1024x576 resolution, no text.
```

## 10. MCP — `mcp-illustration.png`

```
Pixel art 16-bit retro style, split composition. Left side: a universal USB-like hub in the center with many different colored cables (red, blue, green, yellow, purple) all connecting into it from different devices and services around the edges, dark navy background with glowing connection lines. Right side: a character plugging in a new cable to the hub and instantly seeing a new tool appear on their retro computer screen, cozy room with warm lighting and organized cable management. Detailed pixel dithering, nostalgic 16-bit gaming aesthetic. 1024x576 resolution, no text.
```

## 11. API — `api-illustration.png`

```
Pixel art 16-bit retro style, split composition. Left side: a restaurant kitchen scene with a chef (the server/system) preparing dishes behind a counter, a waiter (the API) carrying a menu and tray, dark navy background with warm kitchen glow. Right side: a customer (the user/app) sitting at a table receiving a perfectly plated dish from the waiter, not seeing the kitchen at all, cozy restaurant with warm lighting and decorative plants. Detailed pixel dithering, nostalgic 16-bit gaming aesthetic. 1024x576 resolution, no text.
```

---

## File naming convention

Save all generated images in this folder with the filenames above:
```
ai-terms/
  ai-illustration.png
  llm-illustration.png
  token-illustration.png
  prompt-illustration.png
  hallucination-illustration.png
  agent-illustration.png
  rag-illustration.png
  tool-illustration.png
  skills-illustration.png
  mcp-illustration.png
  api-illustration.png
  cli-illustration.png          (already exists)
```

## Integration

Once generated, the slides already have image support (see CLI slide for reference pattern). Each image replaces the right-column callout card.
