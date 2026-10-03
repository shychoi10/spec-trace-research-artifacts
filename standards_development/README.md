# Official-source development input replay

This exposed TS 38.314 V18.0.0→V19.0.0 development family supplies 21
byte-distinct native documents (24 occurrences), 5,786 XML paragraphs, 16
literal collected metadata rows and four fixed questions. It is an input
resource for evaluating what the supplied official records support.

From the extracted directory run `python3 -B verify.py .`. Python 3.11+
standard library only; no repository, model, network, GPU or credentials are
required. The verifier replays native archive members, paragraph projections,
spreadsheet/CSV field values, input serialization and development reference
coordinates. This performs no inference and establishes no semantic accuracy.

`native_documents.json` maps source IDs to actual original files and reading
aids. `source_units.json` retains every alias and original source binding.
`source_packet.txt` is the exact complete model input, with blanks and tracked
text preserved; `prompts.json` contains its four exact message inputs.
`objects/` also contains bound archive containers and prior projection aids
for provenance. Their unselected members are not additional model inputs.
`manifest.json` maps original repository paths to packaged objects.

Two TSG cover DOC files have converted DOCX reading aids. The original DOC
remains authoritative; conversion fidelity is not certified. XML paragraph
numbers are not printed page numbers. The bounded BEFORE/AFTER text views
do not resolve structural revisions, fields, alternate content, images or
full equation geometry. Consult the native files when layout is material.

`development_reference.json` contains source-inspected assistant development
claims, separately from the prompts. It is neither blinded nor independent
semantic gold. `blank_judgements.jsonl` has no completed annotations. Actual
human judgements, model responses and measured method superiority are all
absent. This is not a completed independently labelled benchmark.

`plan.json` records the pinned local model and effective execution settings.
The model and executable are not bundled. Their original hashes and sources
are retained; provenance code retains repository paths and is not a standalone
inference runner. The only runtime repairs use the full context size as a
nonnegative `repeat_last_n` and resolve the relocated pinned shared libraries.
The historical incompatibilities are preserved under `provenance/`.

Native standard, CR and liaison documents retain their original attribution
and notices. This resource does not claim authorship or relicensing of them.
Each document's record and archive origin is retained in `source_units.json`.

- S01: [native file](objects/1a3cc2b7eea08b32a985ec01d812a8bb7b891ef7bfb7729fdcfa4f5a6f452f2c.docx); 1364 paragraphs
- S02: [native file](objects/bb046dae835a510565b352d44715d1e3f7c52f6f14c4e17fe9e53a837e7ad54a.docx); 1660 paragraphs
- S03: [native file](objects/883bf1651549b9c136f6886b742cbb9787ffb7f8945bbbde790a2a80f5f39b76.docx); 173 paragraphs
- S04: [native file](objects/092565e78620eede5bdeec8aeae166d3ae1de4206ea034fd9c8922ddceb6c06b.docx); 321 paragraphs
- S05: [native file](objects/f21a1e8183dabf56db0f06f4fbe349af682ba5edeb6f6fe0f89cb0ccf1abac38.docx); 32 paragraphs
- S06: [native file](objects/d19a6fcbae25401d52754247df49421295e4f190cb4652e3022bba265b761311.docx); 46 paragraphs
- S07: [native file](objects/cee6a5758d5e480a24da6e25f5b1f954f4caab642e37314f5078152fdc4c0cf5.docx); 28 paragraphs
- S08: [native file](objects/6f3bb67e7ca752ca7864825478a9e2e3e2e44c5597ef56348014d5a8759862db.docx); 35 paragraphs
- S09: [native file](objects/a74e1e7589be567faf4636676930017d7fb6cd034e1be3ee274fabb088f0418b.docx); 31 paragraphs
- S10: [native file](objects/9f77fda1413fcbbc7f9712b63f3f252a325047fac8ef691944c1b62a48947f77.docx); 319 paragraphs
- S11: [native file](objects/1f196d3d1d7e745af16964d6cb39976c7b566a6f6eedf57b2d89826b5f2aef4a.docx); 319 paragraphs
- S12: [native file](objects/84f3b3dc3dcc571396c4929b30d2f6cf4f393a0fb40240b48032412184e70605.docx); 319 paragraphs
- S13: [native file](objects/8c59b79cd948899711577ac02fdc4a43339c11ec102e55b9f696925226649711.docx); 321 paragraphs
- S14: [native file](objects/cc15af20f7c80bd6b24535fca06eec53198e657810c4f46ebc47606a2c5afe91.docx); 32 paragraphs
- S15: [native file](objects/845cc55a318e576f3fc5eb659fd9f76d9bc1a4d7bfbc5f12a7d735e41d6a8a0c.docx); 32 paragraphs
- S16: [native file](objects/c90cde751db3b2c42f2ac8d957752fe487c7198230f04b9164ccf1b484148c52.docx); 208 paragraphs
- S17: [native file](objects/d6f546453fa8aa64c221b6c447ed602a39349850f14931cd170926e4e4cf3537.docx); 173 paragraphs
- S18: [native file](objects/3f20adef76d6ede61e20e218c5ebe3324e5458676acfb148b3baa6ab20394134.docx); 33 paragraphs
- S19: [native file](objects/d8705308d5337ce7ff79b23bff2a82d7ff7a822ea28c66272f7c55730f431615.docx); 30 paragraphs
- S20: [native file](objects/97c5296300d3e1d39279dc19bb77d02007dd3addf726db2e8309d009f55798fc.doc); 206 paragraphs; [converted reading aid](objects/c534200f09c070bc22b85601631d3593cff1bf1801e3496ee24f75038279c115.docx)
- S21: [native file](objects/c95242b44d7001167aaea7ca6246ce2dca3ad550326bde44280ce97c1e33e647.doc); 104 paragraphs; [converted reading aid](objects/600a4109d36f9dd4fe577b67a2147d97867d8ce2d45152051ca54e9b454c58e4.docx)
