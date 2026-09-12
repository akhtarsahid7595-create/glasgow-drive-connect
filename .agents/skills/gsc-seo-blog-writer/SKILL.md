---
name: gsc-seo-blog-writer
description: >-
  Creates highly optimized, human-sounding SEO blog posts based on Google Search Console (GSC) query data.
  Performs competitor research, avoids AI-slop writing, and generates UI/UX matching the existing website's vibe.
---

# GSC-Driven SEO Blog Writer & UI Designer

This skill is designed to create high-quality, human-sounding SEO blog posts based on real Google Search Console (GSC) queries, complete with competitor research and a UI/UX that perfectly matches the existing Glasgow Drive Connect website.

## Trigger

Activate this skill when the user asks to write a blog post based on GSC queries, requests an SEO optimized blog, or wants to create content matching the current website's vibe without "AI slop" or cheap designs.

## Workflow

Follow these steps exactly in order:

### 1. GSC Query Analysis
- Search the workspace for GSC export files (e.g., `download.csv`, `.xlsx` files related to Performance on Search).
- Extract the top underperforming or high-opportunity queries (high impressions, low clicks, or relevant long-tail keywords).
- Select the best keyword target(s) for the new blog post.

### 2. Competitor Research
- Perform a web search (`search_web` tool) for the selected target keyword(s).
- Analyze the top 3-5 ranking competitor pages.
- Identify their content structure, word count, key headings, and missing information (content gaps).
- Your blog must be better, more comprehensive, and more helpful than the competitors.

### 3. Human-Sounding Content Generation (NO AI SLOP)
- **Voice & Tone:** Write like a real, experienced driving instructor in Glasgow. Use local terminology where appropriate. Be conversational but professional.
- **Banned "AI Slop" Phrases:** NEVER use words like "delve into," "tapestry," "bustling," "navigating the complexities," "realm," "testament," "unleash," or "elevate."
- **Keywords:** Integrate the primary and secondary GSC queries naturally. DO NOT keyword stuff. Ensure readability is the top priority.
- **Structure:** Use clear H2 and H3 headings, short paragraphs, bullet points, and actionable advice.

### 4. UI/UX and Design Vibe Matching
- Analyze the existing website's vibe by reading `styles.css` and `index.html`. 
- Take note of the exact colors, fonts, button styles, padding, and layout structures used on the main site.
- **No Cheap AI Design:** DO NOT generate or use cheap, generic, or "creepy" AI icons/illustrations. Stick to high-quality, professional, realistic imagery or clean, minimalist SVG icons that match the current aesthetic.
- If you need to generate images, ensure the prompt explicitly asks for "realistic, professional photography, no distorted faces, no cheap vector art."
- Code the blog post page as an HTML file (e.g., `blog-[topic].html`) that links to the existing `styles.css` and reuses existing header/footer components so it feels like a native part of the site.

### 5. Final Review
- Verify that the generated HTML looks premium and not like a generic template.
- Ensure the copy reads naturally and passes the "human test."
- Present the final blog post file and the competitor research summary to the user.
