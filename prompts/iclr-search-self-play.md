# ICLR 的提示词：Search Self-Play

- 归档日期：2026-09-28
- 来源：用户提供的“ICLR的提示词”截图；会议名称沿用截图标注，不代表会议官方制图规范。
- 主题：Search Self-Play（SSP），展示 proposer 搜索、验证与接纳、独立 solver 搜索，以及共享策略更新。
- 用途：科研漫画风格的方法框架图，包含布局、配色、模块标签、奖励公式和连线要求。
- 原始截图：[iclr-search-self-play.png](../assets/prompts/iclr-search-self-play.png)
- 转录说明：以下为参考图下方英文正文的 OCR 文字版，已去除分段重复并对照原图核对公式、变量及明显识别错误；参考图内部标签保留在原图中。论文归属等表述按截图保留，未独立核验。

```text
Create a polished, visually rich scientific comic method figure titled:
"Search Self-Play"
The figure explains the core training mechanism of Search Self-Play (SSP), the ICLR 2026 paper by Lu et
al.
Use a clear academic diagram structure, small cartoon research assistants, vivid coordinated colors, and
detailed technical objects. The scientific mechanism should dominate the composition. The illustration
should feel engaging and carefully drawn while remaining suitable for a machine-learning paper's method
overview.

OVERALL COMPOSITION
Use a wide landscape canvas with approximately 11:6 proportions, ideally 5632 × 3072 pixels, on a pure
white background.
Preserve this overall arrangement:
1. A substantial proposer region in the upper left.
2. A validation and acceptance region in the upper right.
3. An independent solver region directly below the validation region.
4. A continuous policy-update strip across the bottom.
Use the space beneath the proposer region for its evidence package, trajectory record, and the proposer-
reward calculation. Connect these directly to the main mechanism so this space feels purposeful and
integrated.
Keep the title centered at the top with a compact height. Use one title only, without a large subtitle,
decorative banner, or conference badge.
Align the right edges of the validation and solver regions. Align the left and right ends of the bottom
update strip with the main diagram. Maintain consistent gutters, corner radii, and label spacing.
Give the main regions clear boundaries, but vary their internal organization according to their functions.
The proposer contains a sequential search process, validation contains checks and a controlled question
path, and the solver contains aligned rollout rows.

COLOR DIRECTION: BRIGHT, DISTINCT, AND SUBSTANTIAL
Use a visibly colorful palette with meaningful colored surfaces throughout the technical content.
Page:
Pure white #FFFFFF.
Text and structural outlines:
Deep charcoal #29313D.
Proposer:
Light peach #FFE0C2.
Medium apricot #FFC48F.
Orange accents #EC9654.
Warm outline #C77943.
Validation:
Light lavender #EAE0FF.
Medium lavender #D1B9F0.
Violet accents #9265C8.
Checks and answer references:
Cream yellow #FFF0B8.
Warm yellow #FFD976.
Golden accents #D6A13C.
Solver:
Light sky blue #D7EBFF.
Medium powder blue #ADCEF6.
Blue accents #4D83C8.
Shared policy and learning:
Soft lilac #E7D8FA.
Medium violet #C6A8EA.
Deep violet #8658B3.
Rejected states:
Soft coral #FFB2B3.
Coral accents #DF727C.
Passing states:
Small mint accents #AEDCC9.
Use peach across the proposer's region and document surfaces, lavender across validation, blue across
solver elements, and lilac across the learning mechanism. Make the colored fills clearly visible at normal
viewing size.
Inside these broad regions, use a second, slightly stronger tint for important modules, tabs, answer slips,
and selected document fragments. Keep enough white interior surfaces to preserve contrast and
breathing room.
Use saturated colors selectively on arrowheads, module headings, active document edges, and small
technical symbols.
Avoid a mostly gray diagram with a few colored character icons. Do not use broad gray panel fills.
Maintain the white page around the composition.

SCIENTIFIC COMIC DRAWING STYLE
Use clean, gently hand-inked outlines with controlled variation on characters, paper sheets, magnifiers,
search icons, and small tools.
Keep technical rectangles, alignment guides, arrows, and mathematical notation precise. Use flat fills and
minimal depth cues.
Paper sheets may have small folded corners. Document stacks may have two or three slightly offset
layers. Search tools may use compact browser-window or magnifier symbols. Give these objects enough
personality to support the comic style without becoming decorative scenes.
Use two small matching human research assistants:
brown hair,
a light-blue shirt,
a friendly face,
simple rounded cartoon proportions.
Keep them approximately the same small scale as the reference composition. Each character should
occupy about 3-4% of the total canvas width, including accessories, and should never exceed 5%.
Place one assistant inside the proposer region and one inside the solver region. The proposer points
toward a question sheet. The solver holds a small magnifier near a search result.
Keep both characters subordinate to their surrounding modules. Do not add another proposer outside the
main region. The answer seed should enter through a technical input symbol, not through a duplicate
character.
A tiny question-mark tag beside the proposer and a small magnifier beside the solver are sufficient
expressive details.

TYPOGRAPHY AND INFORMATION DENSITY
Use bold, readable sans-serif typography for the title and region headings. Use a clean sans-serif for
technical labels and properly typeset mathematics for variables and equations.
Keep the title modest. Establish three clear levels:
title,
region and module headings,
technical labels.
Keep labels concise and adjacent to the objects they describe. Preserve normal letter spacing and
generous line spacing inside small modules.
Increase detail through meaningful intermediate states, document contents, tool interactions, and
input/output records. Avoid filling space with paragraphs or repeating the same symbolic tuple several
times.

REGION 1 — PROPOSER SEARCH
Heading:
"1. Proposer Search"
At the left entrance, show a small answer collection labeled:
"Answer set D"
Pull one golden reference tab from it:
"Answer seed a*"
Feed a* into the module labeled:
"Proposer"
Place the small proposer assistant beside this module. Add a compact mathematical tag:
"πθ"
The tag identifies the trainable policy shared with the solver.
Inside the proposer region, draw a detailed but compact search trajectory. Use a sequence of small
alternating reasoning and tool objects:
"Reason"
"Search"
"Observe"
"Refine query"
"Search"
"Observe"
"Form question"
The reasoning steps are model operations. Search is the external tool operation.
Represent each search call with a small query window. Represent each observation with a retrieved page.
Use short orange connectors between these objects.
Use query labels such as:
"query 1"
"query 2"
Use observation labels:
"O1"
"O2"
"..."
Show small highlighted fragments on the retrieved pages using blue, yellow, and orange line segments.
These fragments should look like selected evidence, not random decorative marks.
Use symbolic document contents rather than invented factual quotations or real web addresses.
Bracket the entire sequence once:
"Proposer trajectory τ"
At its endpoint, create two distinct outputs:
A peach question sheet labeled:
"Question q"
A layered evidence package labeled:
"Retrieved documents O"
The question sheet should have a clear title line and a few short text-line glyphs, with one or two orange-
highlighted phrases.
The evidence package should contain three visible page tabs:
"O1"
"O2"
"O3"
Use fine provenance links from the observation pages in the trajectory to their corresponding evidence
tabs.
Draw q and O as separate outputs. Route q toward the rule filter in the validation region. Route O toward
the RAG reader.
At the lower edge of the proposer region, add a compact record strip:
"Trajectory τ"
Its miniature contents should show the ordering of model outputs and returned observations. This record
will be referenced by the proposer's learning input below.

REGION 2 — VALIDATION AND ACCEPTANCE
Heading:
"2. Validation & Acceptance"
Use lavender for the region, cream yellow for checks, and blue document accents for retrieved evidence.
Organize the region into a compact rule filter, a RAG reader, a comparison node, and a question gate.

RULE FILTER
The incoming question first enters:
"Rule filter"
Inside, show four aligned checklist rows:
"Valid format"
"Nonempty / length"
"Search used"
"No answer leakage"
Attach a small golden a* reference specifically to the answer-leakage check. This reference is used to
inspect whether the question reveals the answer.
A failed rule check goes to a coral rejection branch.
A question that passes the rules continues along a visible solid line labeled:
"Held question q"
This line carries the original question toward an acceptance gate.
RAG READER
Branch a copy of q from the held-question line into:
"RAG reader"
Feed the proposer's evidence package O into the same reader through a separate port.
Add a small pale-gray document slip labeled:
"Noise"
This represents unrelated documents mixed into the verification context.
Show the RAG reader's input structure clearly:
"q + O + noise"
Directly beneath its heading, place:
"Search disabled"
Use a small crossed-out search-tool icon beside this note.
Inside the reader, show a short document-reading sequence:
document stack,
highlighted relevant fragments,
generated answer slip.
Label its output:
"Verification answer a_v"
The answer seed a* must not enter the RAG reader. Do not place text inside the reader saying that it
answers using a* or evaluates the question against a*.
The RAG component is an evaluation model separate from the shared trainable policy. Do not add a πθ tag
to it.

COMPARISON AND QUESTION GATE
Route a_v into a compact module:
"Answer match"
Bring a local golden a* reference into this comparison module.
Use two visibly separate input ports:
"a_v"
"a*"
The comparison is a semantic answer judgment.
Its result controls a small gate on the held-question line. Use a short dashed connector labeled:
"Pass / fail"
A passing comparison opens the gate. The original question exits as:
"Accepted q"
Make this identity visually unambiguous: q enters the held-question line and q exits the acceptance gate.
The verification answer a_v terminates at the comparison module. It is not forwarded to the independent
solver.
Combine failed rule checks and failed RAG comparisons into one coral terminal:
"Rejected"
Place the small annotation:
"r_P = 0"
Do not create a proposer-reward calculation directly from the validation pass signal. Validation establishes
eligibility; the difficulty reward is calculated from the independent solver's outcomes.

REGION 3 — INDEPENDENT SOLVER SEARCH
Heading:
"3. Independent Solver Search"
Use a sky-blue region with stronger blue query fields and pale blue observation cards.
Connect Accepted q from the validation gate to:
"Solver"
Label the input connection:
"Question only"
Place the second small research assistant beside this module. Add the same policy tag:
"πθ"
The solver receives the accepted question and performs its own searches. It does not receive the
proposer's evidence package O, the verification answer a_v, or the answer seed a* as its answer-
generating input.
Show three aligned representative rollout rows:
"ρ1"
"ρ2"
"ρn"
Place a vertical ellipsis between the second and final row. Add one shared bracket:
"n rollouts"
Each rollout should contain a compact sequence of distinct objects:
query window,
search-tool icon,
returned observation page,
follow-up query or reasoning node,
answer slip.
Vary the visible number of search steps slightly across rows to make the trajectories informative. Use
short, clean blue arrows and consistent object scales.
Label the final answer slips:
"a1"
"a2"
"an"
Preserve each answer separately. Do not merge all rollouts into one artificial aggregate answer.
Use pale blue and lavender highlights inside the observation pages, with small yellow evidence markers.
Keep the page contents schematic and readable.
At the right side of the rollout rows, place:
"Outcome judge"
Feed each answer a_j into this judge, together with a local golden reference a*.
The answer reference reaches the judge only after answer generation.
Show a compact output list with one row per represented rollout:
"ρ1 → r_S^1"
"ρ2 → r_S^2"
"ρn → r_S^n"
Use colored row tabs to preserve correspondence between a trajectory, its answer, and its reward.
Define the reward nearby:
"r_S^j = J(a_j, a*) ∈ {0, 1}"
Add the short explanation:
"J: semantic match"
Use symbolic reward labels rather than invented numerical results or performance percentages.

PROPOSER REWARD AND TRAINING RECORDS
Use the space beneath the proposer region for one compact, connected reward-and-record area.
Include exactly one module labeled:
"Proposer reward"
Its input comes from the group of solver rewards for the same accepted question.
Show the equation:
"r_P = 1 - mean_j(r_S^j)"
Immediately beneath it, write:
"Accepted questions only"
Keep the rejected-question annotation r_P = 0 near the rejection branch. It must not be interpreted as a
successful challenge.
Do not duplicate the Proposer reward module elsewhere.
Beside or beneath this calculation, show two compact paired-data strips:
Peach:
"Proposer data"
"(τ, r_P)"
Blue:
"Solver data"
"(ρ_j, r_S^j)"
Use small trajectory and reward-tab icons to explain these pairs visually.
These are training-input records, not an added memory system or a replay-buffer illustration.
Connect the proposer data strip to REINFORCE and the solver data strip to GRPO in the bottom update
strip.

REGION 4 — SHARED POLICY UPDATE
Heading:
"4. Policy Update"
Use one full-width, lightly lilac-tinted strip across the bottom.
Preserve a clear three-part arrangement:
Left:

"REINFORCE"
"Proposer update"
Center:
"Shared policy"
"πθ"
Right:
"GRPO"
"Solver update"
Give REINFORCE a peach fill, GRPO a blue fill, and the shared policy a more prominent lavender fill.
Feed (τ, r_P) into the REINFORCE module.
Feed (ρ_j, r_S^j) into the GRPO module.
Show that both update operations affect the same central policy. Label the GRPO step with a small "1" and
the REINFORCE step with a small "2", reflecting the algorithm's update order.
Do not imply that accepted q alone is the input to REINFORCE. Do not route answer references directly
into a policy-update module.
Use medium-weight violet update arrows terminating on the shared-policy object. Keep the arrows
narrower than the modules and leave all mathematical symbols unobstructed.
Under the shared policy, place a small:
"Next training round"
Use two short named output ports, "Proposer" and "Solver", corresponding to the πθ tags in the two role
modules above.
The RAG reader and outcome judge remain outside this trainable-policy update path.

CONNECTORS AND TECHNICAL CLARITY
Use short local connections wherever possible.
Use orange for proposer-side information, blue for solver-side information, violet for policy updates, coral
for rejection, and small mint accents for passing gates.
Use solid arrows for data and update flow.
Use dashed arrows only for validation control signals.
Place a compact two-line legend in a quiet lower corner:
"Solid: data / update"
"Dashed: gate signal"
Use repeated local a* reference tabs at the rule check and comparison nodes instead of drawing a long
answer-key wire around the whole figure.
Ensure all a* tabs refer to the same sampled answer seed. Repeated symbols are references to the same
data, not separate answer generators.
Route long-range trajectory and reward inputs using matching labeled ports when a full line would cross
another mechanism.
Every connector must terminate on an identifiable port or module edge. Avoid arrows passing through
labels, characters, document text, or unrelated regions.

FINAL DETAIL AND REVIEW
The additional richness should come from:
alternating reasoning and search steps,
distinct retrieved pages,
highlighted evidence fragments,
a visible held-question path,
separate RAG answer generation and answer comparison,
aligned solver rollouts,
per-rollout answers and rewards,
paired training records,
and the two updates to shared parameters.
Keep the small cartoon assistants at their current supporting scale. Use the stronger palette and detailed
technical objects to create visual interest.
Check the figure at reduced size: the four main regions, the question route, the acceptance gate, and the
shared-policy update should remain recognizable.
At full size, inspect all variables and arrow endpoints.
Verify the scientific boundaries:
the proposer receives a*;
the rule-based leakage check may reference a*;
the RAG reader receives q and O with search disabled;
a* enters the RAG comparison only after a_v is generated;
the independent solver receives q and searches independently;
each solver rollout retains its own answer and reward;
the proposer reward is computed from solver outcomes for accepted questions;
REINFORCE receives proposer trajectories and rewards;
GRPO receives solver trajectories and rewards;
both update the same policy.
Use a bright, colorful scientific comic finish with precise academic organization. Keep the white
background clean, the module interiors informative, the typography readable, and the main mechanism
visually stronger than the characters.
```
