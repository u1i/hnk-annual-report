# Visual Analysis and Transcription Prompt for Accessibility

## Objective
Analyze this single PDF page image and create a comprehensive, accessible transcription in markdown format that would allow a blind person to fully understand the content, structure, and visual elements of the page.

## Output Format Requirements

### Structure
Each page analysis should follow this exact structure:

```markdown
# Page [NUMBER]: [Brief Title/Topic]

## Summary (Max 100 words)
[Concise overview of the page's main content, purpose, and key information]

## Detailed Transcript

### Text Content
[Complete transcription of all readable text, maintaining original structure and hierarchy]

### Layout and Structure
[Description of how content is organized on the page - columns, sections, headers, etc.]

### Visual References
[References to diagrams, images, charts, etc. with brief inline descriptions]

## Appendix: Visual Elements

### [Visual Element 1: Type - e.g., "Chart", "Diagram", "Image"]
**Location:** [Position on page - top, bottom, left, right, center]
**Size:** [Relative size - small, medium, large, full-width]
**Description:** [Detailed description of what a sighted person would see]
**Content/Data:** [Any text, numbers, or data contained within]
**Purpose:** [Why this visual element exists and what it communicates]

### [Visual Element 2: ...]
[Continue for all visual elements]
```

## Detailed Instructions

### 1. Summary Section (Max 100 words)
- Provide a concise overview of the page's main topic
- Include the type of content (e.g., financial data, narrative text, charts)
- Mention key findings or important information
- Note the page's role in the overall document context

### 2. Text Transcription Guidelines
- **Preserve hierarchy:** Use appropriate markdown headers (##, ###, ####)
- **Maintain structure:** Keep paragraphs, bullet points, and numbering intact
- **Include ALL text:** Don't skip headers, footers, page numbers, or small print
- **Preserve formatting:** Use **bold**, *italic*, `code`, and other markdown formatting
- **Tables:** Convert to markdown table format when possible
- **Lists:** Use proper markdown list syntax (-, *, 1., etc.)

### 3. Layout Description
Describe the visual organization:
- Number of columns
- Section divisions
- Text flow and reading order
- Positioning of major elements
- White space usage
- Page orientation and margins

### 4. Visual Elements Analysis

For each visual element, provide:

#### Charts and Graphs
- **Type:** Bar chart, line graph, pie chart, scatter plot, etc.
- **Title and labels:** All text within the chart
- **Data points:** Key values, trends, comparisons
- **Axes:** What each axis represents, scales, units
- **Legend:** Color coding, symbols, categories
- **Insights:** What the chart reveals or emphasizes

#### Images and Photographs
- **Subject matter:** What is depicted
- **Setting/context:** Where, when, or what situation
- **People:** Number, appearance, actions, expressions
- **Objects:** Key items, their condition, purpose
- **Composition:** Foreground, background, focal points
- **Quality/style:** Professional, candid, illustration style

#### Diagrams and Flowcharts
- **Purpose:** What process or concept is illustrated
- **Components:** All boxes, shapes, elements
- **Connections:** Arrows, lines, flow direction
- **Labels:** All text within diagram elements
- **Sequence:** Step-by-step processes
- **Relationships:** How elements connect or interact

#### Tables and Data Sheets
- **Structure:** Number of rows/columns
- **Headers:** Column and row labels
- **Data:** All numerical values, text entries
- **Formatting:** Bold headers, alternating rows, etc.
- **Totals/summaries:** Any calculated fields
- **Units:** Currency, percentages, measurements

#### Forms and Documents
- **Type:** Application, contract, certificate, etc.
- **Fields:** All form fields, labels, instructions
- **Filled content:** Any completed information
- **Signatures:** Presence of signatures or stamps
- **Legal text:** Fine print, terms, conditions

### 5. Accessibility Best Practices
- **Reading order:** Present information in logical sequence
- **Context clues:** Explain relationships between elements
- **Spatial references:** Use clear positional descriptions
- **Alternative descriptions:** Provide multiple ways to understand visuals
- **Completeness:** Ensure no information is lost in translation

### 6. Special Considerations

#### Financial Documents
- Include all numerical data with proper context
- Explain calculation relationships
- Note currency symbols and formatting
- Describe trend indicators (arrows, colors)

#### Technical Diagrams
- Define technical terms when first used
- Explain symbols and conventions
- Describe scale and proportions
- Include all labels and annotations

#### Marketing Materials
- Describe visual design elements (colors, fonts, layout)
- Include all promotional text and calls-to-action
- Explain branding elements and logos
- Note visual hierarchy and emphasis

## Quality Checklist
Before finalizing each page analysis, verify:

- [ ] Summary is under 100 words but comprehensive
- [ ] All visible text has been transcribed
- [ ] Visual elements are thoroughly described
- [ ] Reading order is logical and clear
- [ ] Technical terms are explained
- [ ] No information has been omitted
- [ ] Markdown formatting is correct
- [ ] A blind person could understand the full content

## Example Output Structure

```markdown
# Page 15: Quarterly Financial Performance

## Summary (85 words)
This page presents Q3 2024 financial results through a combination of narrative analysis and visual charts. Key highlights include 12% revenue growth, improved profit margins, and regional performance breakdowns. The page features two main charts showing revenue trends and market share data, along with explanatory text discussing market conditions and strategic initiatives that drove performance improvements.

## Detailed Transcript

### Main Heading
**Quarterly Financial Performance - Q3 2024**

### Revenue Analysis
Our third quarter results demonstrate strong momentum across all business segments...
[Continue with full text transcription]

### Performance Metrics
- Revenue: $45.2M (↑12% YoY)
- Gross Margin: 34.5% (↑2.1pp)
- Operating Income: $8.7M (↑18% YoY)

## Appendix: Visual Elements

### Chart 1: Revenue Trend Analysis
**Location:** Upper right quadrant of page
**Size:** Medium (approximately 1/4 of page)
**Description:** A line chart with blue trend line showing quarterly revenue from Q1 2023 to Q3 2024
**Content/Data:** Shows steady growth from $35M to $45.2M with slight dip in Q2 2024
**Purpose:** Illustrates revenue growth trajectory and recent performance recovery

### Chart 2: Market Share by Region
**Location:** Lower half of page, centered
**Size:** Large (approximately 1/3 of page)
**Description:** Horizontal bar chart with four colored bars representing different geographic regions
**Content/Data:** North America 45%, Europe 28%, Asia-Pacific 20%, Other 7%
**Purpose:** Shows geographic distribution of business and market penetration
```