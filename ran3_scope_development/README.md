# RAN3 matched-source scope tracing development ablation

Six CRs form one source component under the recorded preparation rules. Three
conditions receive identical paragraph text, tracked BEFORE/AFTER views, literal
metadata, question and output format: DIRECT, original JOINT and JOINT_COVERAGE.
The added condition preserves requested supported facts during alignment and
checks facet coverage. Selection and conditions were fixed before new author
source inspection and before outputs. All five model roles were attempted once.
The source-only AI reference was frozen before predictions and withheld from
them. The final judge received anonymous candidates and could dispute reference
claims. References, predictions and judge use the same configured model family;
their correlated errors are a limitation. These are development observations,
not human semantic gold or independent statistical samples.

Run `python3 -B verify.py .` after extraction. The standard-library-only replay
checks reading XML, literal spreadsheet/CSV cells, fixed inputs and citation
coordinates without network or model calls. Original flat-field citation
diagnostics are retained alongside literal nested/top-level dictionary-path
lookups; resolving a path does not certify semantic support. The first AI
coverage counts are DIRECT 31 complete, JOINT 30 complete/1 partial and
JOINT_COVERAGE 29 complete/2 partial, with all 31 facets judged supported in
each condition. The added instruction has no observed coverage advantage here.
The bounded author readback records the three omissions without changing the
AI counts. The replay does not certify semantic support,
full rendering or legacy DOC conversion fidelity. Native selected attachments and
derived DOCX reading aids retain their distinct provenance. All 11,726 paragraphs,
52 metadata rows and 400 attachment cells are retained. Two reference archives
were not retrieved in the saved official endpoint attempts; this does not prove
their global absence. Availability rows are research preparation records.

The sources are official 3GPP specification, CR and meeting records; their
identities, hashes and source paths are retained. Source-path objects in the
manifest make replay independent of the SPECTRA checkout. No private login,
credentials or unselected archive members are included. CLI configuration was
gpt-6.1-sol/medium with fresh ephemeral turns and tools disabled. Provider
sampling defaults and exact model weight identity are uncontrolled.

Clause/version/CR-rationale organization builds on DeepSpecs:
https://aclanthology.org/2026.findings-acl.1343.pdf
Reference-aware AI adjudication builds on CR-Eval:
https://arxiv.org/abs/2507.04214v2
Their methods and human validation remain their contributions. This resource
contains our fixed development inputs, actual first answers and measured usage.
It does not certify general superiority, human time savings or expert annotation.
