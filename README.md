# AI Photo Editing Skill Library

A curated library of Markdown-based **photo editing skill files** for AI agents.

Each `.md` file in this repository works like a reusable creative direction document.  
You can give one of these files to an AI image editor or AI agent together with a photo, and the agent should follow the instructions inside the Markdown file to transform the image into a specific visual style.

This library is designed for:
- portrait transformation
- campaign-style image generation
- editorial photo editing
- graphic design direction
- consistent AI-generated visuals
- repeatable style systems

---

## What Is a Skill File?

A skill file is a Markdown document that explains:

- the role the AI should take
- the visual style to follow
- photography rules
- lighting direction
- color treatment
- retouching style
- composition rules
- what to preserve
- what to remove
- what not to do

Instead of writing a new prompt every time, you can reuse these `.md` files as a style system.

---

## How to Use

1. Choose the skill file that matches the style you want.
2. Upload or provide the portrait/photo you want to edit.
3. Give both the image and the Markdown file to your AI image editor or AI agent.
4. Ask the AI to follow the skill file exactly.
5. Answer any required style questions inside the skill file.
6. Generate or edit the final image.

---

## Example Prompt

You can use a prompt like this:

```text
Use the attached Markdown skill file as your full creative direction.

Analyze the uploaded portrait and transform it according to the style rules in the skill file.

Preserve the identity of the person, but apply the photography style, lighting, color system, background cleanup, retouching, and composition rules described in the Markdown file.

Do not copy the reference image directly. Use the style system to create a new original portrait.
```

---

## Recommended Repository Structure

```text
ai-photo-editing-skill-library/
│
├── README.md
│
├── portrait-styles/
│   └── editorial-portrait-style-transformer.md
│
├── product-styles/
│   └── product-campaign-style.md
│
├── poster-styles/
│   └── campaign-poster-style.md
│
└── examples/
    ├── input/
    └── output/
```

---

## Current Skill Files

### Editorial Portrait Style Transformer

Transforms any portrait into a luxury monochromatic editorial fashion campaign image.

Best for:
- profile portraits
- podcast thumbnails
- LinkedIn visuals
- personal branding images
- fashion-style AI portraits
- premium campaign posters

Key style features:
- sharp saturated colors
- monochromatic background
- sculptural beauty lighting
- luxury retouching
- clean portrait isolation
- minimal fashion styling
- editorial face gesture
- removal of background objects

---

## Using the Color Options

Some skill files may ask the user to choose a visual direction before generating the final image.

Example:

```text
How bold and color-driven should the final portrait feel?

A — Soft Editorial
B — Balanced Fashion
C — Sharp Campaign
D — Ultra Hyperpop
```

The AI agent should not generate the image before the user selects one option.

This helps keep the output controlled, repeatable, and aligned with the intended style.

---

## Best Practice for AI Agents

When using these files, the AI agent should:

- read the full Markdown file first
- preserve the person’s identity when editing portraits
- remove unnecessary objects and clutter
- follow the style rules strictly
- ask required questions before generating
- avoid copying reference images directly
- create a new image using the same visual language
- check the final output against the quality checklist inside the skill file

---

## What These Files Are Not

These files are not normal image prompts.

They are more like:
- art direction systems
- creative rulesets
- style transformation guides
- reusable AI editing instructions

They are meant to help an AI agent behave more like a professional photographer, retoucher, and graphic designer.

---

## Suggested Workflow

```text
1. Pick a skill file
2. Upload your image
3. Tell the AI to follow the skill file
4. Select any required style options
5. Generate the image
6. Review the output
7. Refine using the checklist inside the skill file
```

---

## Example Command for an AI Agent

```text
Act as an expert image editor and graphic designer.

Use the file:
portrait-styles/editorial-portrait-style-transformer.md

Apply it to the uploaded portrait.

Follow every rule in the file, especially:
- preserve identity
- ask the required color intensity question first
- remove all objects beside the person
- keep the background minimal
- use editorial face gestures
- apply the described lighting and retouching style
```


## Author

Created by KIMO as a reusable AI photo editing and visual direction skill library.
