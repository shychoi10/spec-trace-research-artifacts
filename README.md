# SPEC-TRACE development artifacts

Saved artifacts for tracing evidence across a 3GPP formal summary and its
email deliberation. This resource contains fourteen development questions
from one exposed source family, the exact local model inputs and responses,
and a blank source-grounded answer-review interface.

The questions distinguish feature introduction, mandatory/optional choices,
technical conditions, document handling, quoted history, and source completeness.
The resource supports inspection and mechanical replay of the recorded experiment.
Independent human answer labels and a method-comparison result are still absent.

| File | Contents | Use |
|---|---|---|
| `spectra_lineage_direct_control.tar.gz` | 70 files: 1,506 derived text units, 14 frozen prompts/token lists, original requests/responses/checks, code/protocol identities, and a development review snapshot | Replay the saved input/output, citation and cost checks |
| `direct_answer_review.zip` | 4 files: an offline browser interface, the original answers and source passages, 35 blank requested-component judgments, and a manifest | Review the answers against selected passages or the allowed source scope |
| `checksums.sha256` | SHA-256 of both archives | Verify the downloaded bytes |
| `resource.json` | Archive identities and bounded resource description | Inspect the published snapshot |

## Replay the saved experiment

Python 3.11 or later, using the standard library:

```sh
sha256sum -c checksums.sha256
tar -xzf spectra_lineage_direct_control.tar.gz
cd spectra_lineage_direct_control
python3 -B replay.py verify --bundle .
```

The command checks the packaged bytes and all fourteen input/request/response
bindings, consumed token IDs, recorded generation settings, literal quotations,
claim citation indices, and request costs. It reproduces the original citation
errors as well as successful checks. A replay PASS means faithful reproduction
of the saved artifacts. It does not establish that the generated answers are
correct, and it does not run fresh model inference or retrieval.

The experiment used Qwen3-8B Q4_K_M with a pinned llama.cpp runtime. Model and
runtime identities are retained in the archive. Weights and runtime binaries
are outside this resource. `provenance/` records the original producer and
protocol; those repository-dependent producers are not the standalone replay
command. The archive contains a historical review-ledger snapshot of 26 records.
Later development results are outside this snapshot.

## Review the original answers

Unzip `direct_answer_review.zip` and open `index.html` in a browser. The interface
loads locally, shows each saved answer and its selected source passages, and
can also show the full question-allowed text scope. Enter a reviewer identity
and record coverage, source support, reasons, and evidence anchors. Download
the resulting JSON when done. The supplied form has 35 blank requested components;
no reviewer answers or previous assistant verdicts are supplied in this interface.

Reviewers should disclose previous source/model-answer exposure. Reviewing an
answer after seeing it differs from writing a source-only reference beforehand.
No independent human review or three-condition blinded comparison is reported.

## Sources and interpretation

The derived text units come from 32 development email bodies (M00–M31) and formal
summary R4-2207053, associated with the 3GPP RAN4 102-e FR2 HST discussion. Source
identifiers, available sender/time metadata, ordinary/deleted text channels,
selected occurrence IDs, and native paragraph/cell positions are retained.
The emails are archive text with masking preserved; this resource does not
reconstruct masked addresses. The formal record and participant contributions
remain attributable to their original sources, rather than to the resource authors.

These questions were developed after source exposure. They share a source family
and are not fourteen independent samples or an independent evaluation split.
The review-ledger snapshot contains assistant development interpretations; it is
not human ground truth. Exact strings and valid IDs do not establish a claim's
speaker, condition, decision role, or semantic support. A quoted or copied statement
is not evidence of another independent supporter or a causal effect on a decision.

The archives were prepared before publication. Their embedded `public_upload=false`
fields preserve that earlier preparation state; publication and anonymous-download
verification are recorded separately. Reserved source families and ongoing candidate
extraction/comparison outputs are outside this snapshot. No DOI, external use,
independent semantic accuracy, or method superiority is asserted.

Third-party source records retain their original rights and attribution. This
resource does not assign a new license to third-party records or model weights.
