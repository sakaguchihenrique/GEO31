# AGENTS.md

## Project Overview
- **Project:** GEO-31 Roads Presentation Project
- **Purpose:** Build a step-by-step group presentation about roads for GEO-31 Engineering Geology.
- **Main class source:** `Aula15_GEO-31_2020.pdf`
- **Case-study source:** `CONTRATO-RODOANEL-NORTE-N-0521-ARTESP-2023_ASSINADO.pdf`
- **Presentation rules source:** `Orientações para os Trabalhos em Grupo_GEO-31.pdf`
- **Target user:** A GEO-31 student preparing a clear class presentation.
- **Language:** Use English for project files, unless quoting or summarizing Portuguese source terms.
- **Output style:** Clear Markdown notes, slide outlines, tables, diagrams, and presentation scripts.

## Source Roles

### 1. Aula 15 Agent: Theory Base
Use `Aula15_GEO-31_2020.pdf` as the main technical foundation.

Responsibilities:
- Identify the road-engineering geology topics required by the class.
- Explain the relationship between roads and geology in simple English.
- Cover topics such as:
  - road studies and project phases;
  - earthworks;
  - pavement materials;
  - drainage;
  - slopes and cuts;
  - subgrade behavior;
  - soil and rock use in road works;
  - geological and geotechnical investigation.
- Add tables and Mermaid diagrams when they make the topic easier to study.
- Connect each technical topic to a civil infrastructure consequence.

### 2. Rodoanel Case Agent: Real Project Context
Use `CONTRATO-RODOANEL-NORTE-N-0521-ARTESP-2023_ASSINADO.pdf` as a real-world case study.

Responsibilities:
- Treat the contract as supporting evidence, not as the main theory source.
- Extract only information useful for the presentation, such as:
  - project location and context;
  - concession or construction scope;
  - road infrastructure elements;
  - references to earthworks, pavement, drainage, slopes, tunnels, bridges, or geotechnical works;
  - project risks, obligations, or maintenance responsibilities.
- Clearly label what is technical and what is administrative.
- If the contract lacks engineering detail, say so and suggest what annexes or complementary sources are needed.

### 3. Orientation Agent: Assignment Rules
Use `Orientações para os Trabalhos em Grupo_GEO-31.pdf` to guide the final presentation format.

Responsibilities:
- Identify what the professor expects from the group work.
- Check whether the presentation plan follows the required structure.
- Track likely requirements such as:
  - theme definition;
  - objective;
  - technical content;
  - examples or case study;
  - references;
  - division of group tasks;
  - presentation time;
  - visual clarity.
- Before finalizing any outline, compare it with this orientation document.

### 4. Presentation Planner Agent
Combine the three sources into a practical presentation plan.

Responsibilities:
- Build the presentation step by step.
- Keep the main logic:
  1. Start from Aula 15 theory.
  2. Add the Rodoanel Norte case as an example.
  3. Check the structure against the orientation PDF.
- Create slide outlines with title, key message, visual idea, and source.
- Avoid making the contract the full technical base unless it contains enough engineering detail.

### 5. Slide Writer Agent
Turn approved outlines into slide text and speaker notes.

Responsibilities:
- Use short slide text.
- Put details in speaker notes, not crowded bullets.
- Use simple English.
- Define acronyms the first time they appear, such as SPT (Standard Penetration Test).
- Suggest useful visuals, such as maps, cross sections, pavement layer sketches, drainage diagrams, and slope diagrams.

### 6. Technical Reviewer Agent
Review notes, outlines, and scripts for technical consistency.

Responsibilities:
- Check whether claims are supported by one of the three project sources.
- Mark each claim as:
  - **Aula 15 theory**
  - **Rodoanel case**
  - **Orientation requirement**
  - **Needs confirmation**
- Identify missing road topics before the presentation is finalized.
- Keep explanations suitable for a first-year Civil Engineering student.

### 7. Source Gap Agent
Detect when the three project PDFs are not enough for a complete presentation.

Responsibilities:
- Say clearly when a document is insufficient for a topic.
- Do not invent technical details to make the presentation look complete.
- Mark missing information as `Needs confirmation`.
- Explain why the missing information matters for a good road presentation.
- Suggest practical ways to find the missing information.
- Separate must-have information from nice-to-have information.

When sources are insufficient, use this response pattern:

| Gap | Why it matters | How to get the information | Priority |
|---|---|---|---|
| Missing technical road detail | The presentation needs engineering content, not only administrative context. | Look for annexes, technical reports, project plans, ARTESP documents, DER/SP manuals, DNIT manuals, maps, or academic papers. | High |

Recommended ways to fill gaps:
- Search for annexes to the Rodoanel Norte contract.
- Look for official ARTESP, DER/SP, DNIT, or concessionaire documents.
- Use road engineering manuals for general theory when Aula 15 is too short.
- Use geological maps and geotechnical maps for location-based context.
- Use satellite images or official maps to explain the route and terrain.
- Ask the professor or monitor whether external sources are allowed.
- Use academic papers only when they directly support the road-geology topic.
- Add a slide or note called `Limitations of the sources` if the missing information affects the final argument.

### 8. English Coach Agent
Help improve English during chat and draft review.

Responsibilities:
- Correct the user's English gently in chat.
- Keep corrections short and practical.
- Do not add English corrections inside project files unless requested.

## Project Workflow
1. Read the orientation PDF first to understand the assignment.
2. Read Aula 15 to define the technical road topics.
3. Read the Rodoanel contract to find case-study material.
4. Create a source-fit table:
   - what Aula 15 covers;
   - what the Rodoanel contract covers;
   - what the orientation requires;
   - what is missing.
5. Build a presentation outline.
6. Create slide drafts.
7. Add visuals, maps, diagrams, and tables.
8. Write speaker notes.
9. Review technical accuracy and source coverage.
10. Prepare a final checklist before presentation.

## Recommended Files
- `README.md`: project guide and workflow.
- `notes/source-fit.md`: comparison between the three PDFs.
- `notes/aula15-road-theory.md`: technical notes from Aula 15.
- `notes/rodoanel-case-study.md`: useful case-study notes from the contract.
- `notes/orientation-requirements.md`: assignment rules from the orientation PDF.
- `presentation/outline.md`: slide sequence.
- `presentation/speaker-notes.md`: what to say during the presentation.
- `presentation/references.md`: sources used in the presentation.
- `diagrams/`: editable diagrams.
- `notes/images/`: selected figures, maps, screenshots, or page prints.

## Source Use Rules
- Do not change original PDFs.
- Always cite which source supports a note or slide.
- Use Aula 15 as the main technical base.
- Use the Rodoanel contract as a case study and project context.
- Use the orientation PDF as the checklist for presentation requirements.
- If a topic is not clearly supported by the three PDFs, mark it as `Needs confirmation`.
- If the three PDFs are insufficient, say this clearly and recommend the best next sources.
- Do not hide missing information. A clear limitation is better than a weak or unsupported claim.

## Gap Handling Rules
- First, check whether the missing topic is required by the orientation PDF.
- Second, check whether Aula 15 gives enough theory.
- Third, check whether the Rodoanel contract gives a real case example.
- If the answer is still weak, create a gap note with:
  - what is missing;
  - why it matters;
  - where to search next;
  - whether it is essential for the presentation.
- Prefer official sources before blogs or informal websites.
- For road standards and technical criteria, prefer DNIT, DER/SP, ARTESP, ABNT, concessionaire reports, or academic sources.
- For route and terrain context, prefer official maps, geological maps, geotechnical maps, satellite images, and environmental reports.
- If external information is used, add it to `presentation/references.md`.

## Writing Rules
- Use plain English.
- Prefer short sections.
- Use tables for comparisons and classifications.
- Use Mermaid diagrams for processes.
- Explain what each visual teaches.
- Avoid long paragraphs.
- Connect geology to road behavior whenever possible.

## Common Presentation Risks
- Using the Rodoanel contract as if it were a technical textbook.
- Forgetting to connect geology to road performance.
- Giving administrative contract details without engineering meaning.
- Missing visual explanation of road layers, earthworks, drainage, or slopes.
- Crowding slides with too much text.
- Not checking the professor's orientation before finalizing.

## Final Quality Checklist
- The presentation follows the orientation PDF.
- Aula 15 is clearly the theory base.
- The Rodoanel contract is clearly used as a real case.
- Each slide has one main idea.
- Technical terms are defined.
- Important visuals are explained.
- Missing information is clearly marked.
- References are listed.
