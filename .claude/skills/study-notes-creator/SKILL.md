
---
name: study-notes-creator
description: Generate comprehensive study notes for academic lessons with summary sections, highlighted key terms, review questions, and structured formatting. Use when user requests study notes, lesson summaries, revision materials, or educational content for learning reinforcement.
---

# Study Notes Creator

Generate structured, academically rigorous study notes designed for reinforcement and revision of educational material.

## Instructions

When a user requests study notes, lesson summaries, or revision materials, follow this systematic approach:

### Step 1: Gather Required Information

Request the following details from the user:
- Lesson topic or title
- Educational level (undergraduate, graduate, professional, or secondary)
- Specific concepts or areas requiring emphasis
- Source material or reference documents (if available)

### Step 2: Generate Notes with Required Structure

All study notes must contain these four mandatory components in the following order:

#### 1. Summary Section (Top of Document)

- Provide a concise overview of the lesson's main concepts
- Synthesize core learning objectives
- Limit to 3-5 well-constructed paragraphs
- Capture the essential theoretical framework
- Use formal academic language

#### 2. Key Terms (Early in Document)

- **Highlight** all critical terminology using bold formatting
- Provide precise definitions for each term
- Include contextual usage where applicable
- Organize alphabetically or by order of appearance
- Format as a definition list or structured table

#### 3. Content Body (Main Sections)

- Present detailed explanations of concepts
- Utilize hierarchical headings (##, ###, ####) for organization
- Incorporate illustrative examples for abstract principles
- Employ bullet points and numbered lists for clarity
- Include relevant formulas, equations, or code snippets as applicable
- Maintain logical progression of ideas
- Use tables for comparative information
- Add blockquotes for important principles or theorems

#### 4. Review Questions (End of Document)

Include 5-10 questions of varying difficulty levels across these categories:
- **Recall questions**: Testing factual knowledge
- **Comprehension questions**: Assessing conceptual understanding
- **Application questions**: Evaluating practical usage
- **Analysis questions**: Requiring critical thinking and synthesis

Format questions in a numbered list.

### Step 3: Apply Formatting Standards for Readability

Ensure the document adheres to these readability principles:

- **Clear hierarchy**: Use appropriate heading levels (# through ####)
- **White space**: Prevent visual density through strategic spacing
- **Consistent formatting**:
  - **Bold** for key terms and emphasis
  - *Italics* for introducing new concepts
  - `Code blocks` for technical content
  - > Blockquotes for important principles
  - Tables for structured data
  - Horizontal rules (---) to separate major sections
- **Short paragraphs**: Maximum 3-5 sentences per paragraph
- **Lists**: Use for sequential or grouped information
- **Section dividers**: Between major components

### Step 4: Maintain Academic Standards

- Use formal, precise language throughout
- Employ discipline-specific terminology accurately
- Avoid colloquialisms and informal expressions
- Ensure grammatical correctness
- Use transitional phrases for coherence
- Maintain objective perspective

## Output Template

```markdown
# [Lesson Title]

## Summary

[3-5 paragraph concise overview of the lesson covering main concepts, learning objectives, and theoretical framework...]

---

## Key Terms

**Term 1**: Precise definition with contextual usage...

**Term 2**: Precise definition with contextual usage...

**Term 3**: Precise definition with contextual usage...

---

## [Main Content Section 1]

### [Subtopic 1.1]

[Detailed explanation with examples...]

### [Subtopic 1.2]

[Detailed explanation with examples...]

## [Main Content Section 2]

### [Subtopic 2.1]

[Detailed explanation with examples...]

---

## Review Questions

### Recall Questions
1. [Question testing factual knowledge]
2. [Question testing factual knowledge]

### Comprehension Questions
3. [Question assessing understanding]
4. [Question assessing understanding]

### Application Questions
5. [Question evaluating practical usage]
6. [Question evaluating practical usage]

### Analysis Questions
7. [Question requiring critical thinking]
8. [Question requiring synthesis]

---

## Additional Resources

[Optional: References, further reading, or related topics]
```

## Quality Checklist

Before finalizing the study notes, verify:

- [ ] Summary appears at the top
- [ ] Key terms are highlighted in bold with definitions
- [ ] Content follows logical progression
- [ ] Review questions cover multiple cognitive levels
- [ ] Formatting enhances readability
- [ ] Academic tone is maintained throughout
- [ ] All four required sections are present
- [ ] Appropriate use of lists, tables, and visual organization

## Examples of Usage Triggers

This skill should be automatically invoked when users make requests such as:

- "Create study notes for [topic]"
- "Generate revision materials for my lesson on [subject]"
- "I need notes to help me review [concept]"
- "Make a study guide for [course content]"
- "Prepare educational notes on [topic]"
- "Help me create learning materials for [lesson]"

The skill should adapt the complexity and depth based on the specified educational level while maintaining the required structural components.
