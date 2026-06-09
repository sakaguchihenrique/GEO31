# GEO-31 Roads Presentation Project

This project helps build a GEO-31 group presentation about roads using three main documents:

1. `Aula15_GEO-31_2020.pdf` - main theory source for roads and engineering geology.
2. `CONTRATO-RODOANEL-NORTE-N-0521-ARTESP-2023_ASSINADO.pdf` - real project case study about Rodoanel Norte.
3. `Orientações para os Trabalhos em Grupo_GEO-31.pdf` - professor's orientation for the group work.

## Main Idea

Use **Aula 15** to explain the technical road concepts. Use the **Rodoanel Norte contract** to show a real infrastructure example. Use the **orientation PDF** to make sure the presentation follows the assignment rules.

The contract should not replace Aula 15. It is mainly a case-study document unless it contains detailed engineering annexes.

## When the Sources Are Not Enough

These three PDFs may not contain everything needed for a strong final presentation. When that happens, do not guess.

Use this rule:

**If a topic is important but the PDFs do not support it well, mark it as missing and explain how to find it.**

Good ways to fill missing information:

| Missing need | Where to look next | Why it helps |
|---|---|---|
| Detailed road design or construction criteria | DNIT manuals, DER/SP manuals, ABNT standards | Gives technical rules and terminology. |
| Rodoanel Norte engineering details | Contract annexes, ARTESP documents, concessionaire reports | Gives project-specific information. |
| Geology along the route | Geological maps, geotechnical maps, CPRM/SGB sources, environmental studies | Connects the road to soil, rock, relief, and risk. |
| Terrain and route context | Official maps, satellite images, project maps | Helps create clear visuals. |
| Case-study evidence | Academic papers, technical reports, environmental impact studies | Supports claims with real examples. |
| Assignment doubts | Professor, monitor, or orientation PDF | Confirms what is allowed and expected. |

Use a `Needs confirmation` label when information is missing, uncertain, or not directly supported by the three PDFs.

## Step-by-Step Workflow

### Step 1 - Understand the Assignment
Read `Orientações para os Trabalhos em Grupo_GEO-31.pdf`.

Create:
- `notes/orientation-requirements.md`

Focus on:
- expected presentation structure;
- time limit;
- required topics;
- evaluation criteria;
- references;
- group division.

### Step 2 - Study the Class Theory
Read `Aula15_GEO-31_2020.pdf`.

Create:
- `notes/aula15-road-theory.md`

Focus on:
- road studies;
- earthworks;
- pavement;
- drainage;
- slopes;
- soil and rock materials;
- geological and geotechnical investigation;
- risks for road construction and operation.

### Step 3 - Read the Rodoanel Case
Read `CONTRATO-RODOANEL-NORTE-N-0521-ARTESP-2023_ASSINADO.pdf`.

Create:
- `notes/rodoanel-case-study.md`

Look for:
- project location;
- road infrastructure scope;
- earthworks;
- pavement;
- drainage;
- tunnels, bridges, cuts, embankments, or slopes;
- construction and maintenance responsibilities;
- environmental or geotechnical risks.

If the contract is mostly administrative, mark the missing technical details clearly.

### Step 4 - Compare the Sources
Create:
- `notes/source-fit.md`

Use this table:

| Topic | Aula 15 | Rodoanel Contract | Orientation PDF | Status | If insufficient, search next |
|---|---|---|---|---|---|
| Road project phases | Main theory | Case context if mentioned | Check if required | To review | DNIT or DER/SP road project manuals |
| Earthworks | Main theory | Look for contract scope | Check if required | To review | Earthwork specifications, project annexes |
| Pavement | Main theory | Look for pavement obligations | Check if required | To review | DNIT pavement manuals, concession reports |
| Drainage | Main theory | Look for drainage works | Check if required | To review | Drainage manuals, project plans, environmental studies |
| Slopes and cuts | Main theory | Look for stabilization or maintenance | Check if required | To review | Geotechnical reports, geological maps, slope stability references |
| Geotechnical investigation | Main theory | Look for investigation requirements | Check if required | To review | SPT reports, boring logs, environmental or engineering annexes |
| Real case example | Support theory | Main case | Check if required | To review | ARTESP, concessionaire, or environmental documents |

### Step 5 - Build the Presentation Outline
Create:
- `presentation/outline.md`

Suggested slide sequence:

| Slide | Title | Main Message | Main Source | Visual Idea |
|---|---|---|---|---|
| 1 | Roads and Engineering Geology | Geology controls road performance and risks. | Aula 15 | Road in terrain photo or map |
| 2 | Why Roads Need Geology | Soil, rock, water, and relief affect design. | Aula 15 | Cause-effect diagram |
| 3 | Road Project Phases | Road studies move from planning to construction and operation. | Aula 15 | Flow diagram |
| 4 | Earthworks | Cuts and embankments depend on material behavior. | Aula 15 | Cut and fill sketch |
| 5 | Pavement and Subgrade | Pavement performance depends on the ground below it. | Aula 15 | Pavement layer diagram |
| 6 | Drainage | Water is one of the main causes of road problems. | Aula 15 | Drainage path diagram |
| 7 | Slopes and Stability | Road cuts and embankments can fail if geological conditions are unfavorable. | Aula 15 | Slope failure sketch |
| 8 | Rodoanel Norte Case | The contract gives a real infrastructure context. | Rodoanel contract | Location map |
| 9 | Case Connection to Aula 15 | Link contract elements to road geology topics. | Aula 15 + Rodoanel | Comparison table |
| 10 | Main Lessons | Good road projects need geology, drainage, materials control, and risk management. | All sources | Summary diagram |
| 11 | References | List all sources used. | All sources | Clean reference list |

### Step 6 - Draft Speaker Notes
Create:
- `presentation/speaker-notes.md`

For each slide, write:
- what to say;
- which source supports it;
- one example;
- one possible visual explanation.

### Step 7 - Review Before Finalizing
Check:
- Does the presentation follow the orientation PDF?
- Is Aula 15 the main technical source?
- Is the Rodoanel contract used as a real case study?
- Are technical terms explained?
- Are the slides visual and not crowded?
- Are missing details marked as missing instead of guessed?
- Are the missing details followed by advice on where to find them?

### Step 8 - Fill the Most Important Gaps
Create a short gap list before writing the final slides.

Use this format:

| Missing information | Why it matters | Suggested source | Priority |
|---|---|---|---|
| To review | To review | To review | High / Medium / Low |

Only search for extra sources when the missing information improves the presentation. Do not add sources only to make the bibliography longer.

## Suggested Project Structure

```text
.
├── AGENTS.md
├── README.md
├── Aula15_GEO-31_2020.pdf
├── CONTRATO-RODOANEL-NORTE-N-0521-ARTESP-2023_ASSINADO.pdf
├── Orientações para os Trabalhos em Grupo_GEO-31.pdf
├── notes/
│   ├── orientation-requirements.md
│   ├── aula15-road-theory.md
│   ├── rodoanel-case-study.md
│   └── source-fit.md
├── presentation/
│   ├── outline.md
│   ├── speaker-notes.md
│   └── references.md
├── diagrams/
└── notes/images/
```

## Useful Framing for the Presentation

Possible title:

**Roads and Engineering Geology: Lessons from Aula 15 and the Rodoanel Norte Case**

Possible central question:

**How do geological conditions affect the design, construction, and maintenance of roads?**

Possible thesis:

**A road is not only a pavement surface. It is an engineering system controlled by soil, rock, water, relief, and geological risk.**

## First Tasks

1. Create `notes/orientation-requirements.md`.
2. Create `notes/aula15-road-theory.md`.
3. Create `notes/rodoanel-case-study.md`.
4. Create `notes/source-fit.md`.
5. Create `notes/source-gaps.md`.
6. Create `presentation/outline.md`.

## English Note

A more natural way to say your project idea:

> I am starting a new GEO-31 project. The assignment is a presentation about roads. I will use the Rodoanel Norte contract as a case-study document, Aula 15 as the main technical source, and the group-work orientation PDF to guide the presentation structure.
