# AI Prompt Template for Generating English Learning Articles

## Instructions for AI Agent

You are tasked with creating comprehensive English language learning articles following the exact structure and style of the French learning blog (FrenshBlog). Generate educational content about English grammar, vocabulary, pronunciation, and language skills.

---

## Article Structure Template

### 1. HTML Document Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>[Article Title] - EnglishBlog</title>
</head>
<body>
    <header>
        <h1>[Main Title]</h1>
        <p>Published on <time datetime="YYYY-MM-DD">[Date]</time></p>
        <p><em>[Subtitle/Description]</em></p>
        <p><strong>Level: A1-C2 (All levels)</strong> or specify specific level range</p>
    </header>

    <main>
        <article>
            <!-- Table of Contents -->
            <!-- Main Content Sections -->
            <!-- Conclusion -->
            <!-- Resources Section -->
        </article>
    </main>

    <footer>
        <p>© 2024 EnglishBlog - Learn English A1 to C2</p>
        <p><a href="[related-article].html">← See also: [Related Topic]</a></p>
    </footer>
</body>
</html>
```

---

## Content Structure Guidelines

### A. Header Section
- **Title**: Clear, descriptive title about the English topic
- **Publication Date**: Use format "Published on [Date]"
- **Subtitle**: Brief, engaging description (italicized)
- **Level Indicator**: CEFR levels (A1-C2) - specify if article targets specific levels

### B. Table of Contents (Plan)
- Always include a styled table of contents box at the beginning
- Use ordered list with anchor links to sections
- Style: Blue border (#4a90e2), light blue background (#f8f9ff), rounded corners (12px)

### C. Main Content Sections

Each article should include:

1. **Definition Section** (`#definition`)
   - "What is [topic]?"
   - Clear, concise explanation
   - Include a "In brief" box (green border #28a745, light green background #f0fff4)

2. **Importance Section** (`#importance`)
   - "Why learn [topic]?" or "Why is this important?"
   - List of advantages/benefits
   - Use blue box (#007bff) with bullet points

3. **Main Content Sections** (varies by topic)
   - Break down into logical subsections
   - Use h2 for main sections, h3 for subsections
   - Include practical examples

4. **Learning Strategies Section** (if applicable)
   - "How to learn [topic]?" or "Strategies for..."
   - Practical tips and methods
   - Use blue box (#4a90e2) with strategies

5. **Examples Section** (if applicable)
   - Real-world examples
   - Use styled boxes with different colors for variety

6. **Exercises Section** (optional but recommended)
   - Practical exercises with solutions
   - Use different colored boxes for each exercise

### D. Conclusion Section
- Summary box with key takeaways
- Style: Light blue background (#e7f3ff), left border (#2196f3)
- Use bullet points for "Essential points to remember"

### E. Resources Section
- Final box listing available resources
- Include emojis for visual interest (📚, 🎯, 💡, etc.)
- Style: Blue border (#4a90e2), light blue background (#f8f9ff)

---

## Styling Guidelines

### Color Scheme for Information Boxes

1. **Main/Plan Box**: 
   - Border: `#4a90e2` (blue)
   - Background: `#f8f9ff` (light blue)
   - Border-radius: `12px`

2. **Positive Information/In Brief**:
   - Border: `#28a745` (green)
   - Background: `#f0fff4` (light green)
   - Border-radius: `8px`

3. **Advantages/Lists**:
   - Border: `#007bff` (blue)
   - Background: `#e7f3ff` (light blue)
   - Border-radius: `8px`

4. **Examples/Warnings**:
   - Border: `#ffc107` (yellow)
   - Background: `#fffbf0` (light yellow)
   - Border-radius: `8px`

5. **Important Notes**:
   - Border: `#dc3545` (red)
   - Background: `#fff5f5` (light red)
   - Border-radius: `8px`

6. **Neutral Information**:
   - Border: `#6b7280` (gray)
   - Background: `#f9fafb` (light gray)
   - Border-radius: `8px`

### Inline CSS Format

```html
<div style="border: 2px solid #4a90e2; padding: 20px; margin: 20px 0; background-color: #f8f9ff; border-radius: 12px;">
    <h2 style="margin-top: 0; color: #2c3e50; font-size: 1.5em;">[Title]</h2>
    <!-- Content -->
</div>
```

---

## Content Style Guidelines

### Writing Tone
- **Educational and supportive**: Encourage learning, not intimidate
- **Clear and structured**: Use headings, lists, and boxes for organization
- **Practical**: Include real examples and actionable advice
- **Progressive**: Acknowledge different CEFR levels when relevant

### Language Features
- Use **bold** for key terms and important concepts
- Use *italics* for emphasis and examples
- Include **practical examples** in every section
- Use **bullet points** for lists (advantages, strategies, tips)
- Include **tables** for structured information (conjugations, comparisons, etc.)

### Examples Format
- Always provide English examples
- Use simple sentences for beginner topics
- Use more complex examples for advanced topics
- Include context when helpful

### CEFR Level Considerations
- **A1-A2**: Simple explanations, basic vocabulary, lots of examples
- **B1-B2**: More detailed explanations, intermediate vocabulary, practical applications
- **C1-C2**: Advanced concepts, nuanced explanations, sophisticated examples

---

## Topic-Specific Guidelines

### Grammar Articles
- Explain rules clearly
- Provide conjugation tables when relevant
- Include common mistakes to avoid
- Show usage in context
- Include exercises

### Vocabulary Articles
- Organize by themes or categories
- Distinguish between active and passive vocabulary
- Provide learning strategies
- Include memory techniques
- Show word families and synonyms

### Pronunciation Articles
- Focus on English sounds and phonetics
- Include IPA notation when helpful
- Provide practice exercises
- Address common pronunciation challenges
- Include audio references (mention where to find)

### Skill-Based Articles (Speaking, Writing, Reading, Listening)
- Break down into components
- Provide practical strategies
- Include practice activities
- Address common challenges
- Offer progression tips

---

## Example Article Topics for English

### Grammar Topics
- English Grammar Overview
- Parts of Speech in English
- English Verb Tenses
- Modal Verbs in English
- Articles (a, an, the)
- Prepositions in English
- Conditionals in English
- Passive Voice
- Reported Speech
- Phrasal Verbs

### Vocabulary Topics
- English Vocabulary Building
- Common English Verbs
- Business English Vocabulary
- Academic English Vocabulary
- English Idioms and Expressions
- Phrasal Verbs Vocabulary
- English Word Formation

### Skills Topics
- English Speaking Skills
- English Writing Skills
- English Reading Comprehension
- English Listening Skills
- English Conversation Skills
- English Presentation Skills

### Pronunciation Topics
- English Pronunciation Guide
- English Phonetics
- English Intonation and Stress
- Common Pronunciation Mistakes

---

## Quality Checklist

Before finalizing an article, ensure:

- [ ] HTML structure is correct and semantic
- [ ] Table of contents with working anchor links
- [ ] All sections are properly styled with appropriate color boxes
- [ ] Examples are relevant and clear
- [ ] CEFR level is specified
- [ ] Conclusion summarizes key points
- [ ] Resources section is included
- [ ] Footer with related links
- [ ] Content is accurate and educational
- [ ] Writing is clear and accessible
- [ ] No spelling or grammar errors
- [ ] Examples use proper English

---

## Sample Prompt for AI Agent

**Example**: "Create an article about 'English Verb Tenses' following the FrenshBlog structure. Include: definition, importance, all major tenses (present, past, future), usage examples, common mistakes, and exercises. Target levels B1-B2. Use the exact HTML structure and styling from the template."

---

## Notes

- **Language**: All content should be in English
- **Target Audience**: English learners (non-native speakers)
- **Difficulty**: Adapt to specified CEFR levels
- **Format**: HTML files ready for web publication
- **Consistency**: Maintain the same structure and style across all articles
- **Branding**: Use "EnglishBlog" instead of "FrenshBlog"
- **Cultural Context**: Focus on English (can specify British or American English when relevant)

---

## Additional Instructions

1. **Adapt French concepts to English equivalents**:
   - French verb groups → English verb patterns (regular/irregular)
   - French tenses → English tenses (12 tenses)
   - French grammar rules → English grammar rules
   - French pronunciation → English pronunciation

2. **Maintain educational value**:
   - Each article should be comprehensive but not overwhelming
   - Break complex topics into digestible sections
   - Use progressive difficulty when appropriate

3. **Include practical elements**:
   - Real-world examples
   - Common mistakes sections
   - Practice exercises
   - Learning tips

4. **Ensure accuracy**:
   - Verify grammar rules
   - Check examples for correctness
   - Use standard English (specify British or American when relevant)

---

**End of Template**

