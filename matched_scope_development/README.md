# Matched-source scope tracing development resource

Two source-dependent development cohorts: five TS 38.561 CRs and six TS 38.201
CRs. Both DIRECT and JOINT receive the same paragraph text, tracked text views,
question, metadata, and answer format. JOINT adds the saved alignment instruction.
The archive contains actual source reading files, original selected DOC/DOCX
attachments where recorded, text projections, processing/CR metadata, fixed
inputs, first model answers and observed usage. Unselected archive members and
private account credentials are excluded. Source paths in provenance map to the
hash-named objects in manifest.json; no SPECTRA checkout is needed.

Run `python3 -B verify.py .` after extraction. It uses only the Python standard
library and performs no network or model calls. It replays Word paragraph tokens,
tracked BEFORE/AFTER views and literal spreadsheet/CSV fields. This certifies
bounded native-text replay, not complete Word rendering or DOC conversion
fidelity. Reading aids and their recorded limitations remain explicit.

The RAN1 reference was produced from sources before either prediction and was
not supplied to the predictions. The later AI judge received anonymous answers
and could flag reference defects. All four RAN1 roles use the same configured
model family; their correlated errors are a limitation. The RAN5 comparison has
author development inspection, not that AI reference procedure. Neither cohort
is independent human semantic gold. Six/ five CRs within a source component and
31 RAN1 facets are not independent statistical samples. No general method
advantage, human time savings or expert annotations are certified here.

The CLI configured gpt-6.1-sol/medium through an existing ChatGPT login, with
fresh ephemeral turns and tools disabled. Provider sampling defaults and exact
model weight identity are uncontrolled. Every role was attempted once; failures
of earlier separate local setup are retained in the research repository.

Sources are 3GPP official specification/CR/meeting records. Their original
document identities, native-file hashes and source paths are retained. This
resource adds development inputs and measured answers; it does not claim
ownership of the standards text. Reference-aware AI evaluation builds on
CR-Eval (https://arxiv.org/abs/2507.04214v2); that work's human validation is not
part of this resource. Joint alignment develops scope/revision/evidence-role
handling on foundations including DeepSpecs
(https://aclanthology.org/2026.findings-acl.1343.pdf).
