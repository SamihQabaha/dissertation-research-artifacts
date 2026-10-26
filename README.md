# Dissertation research artifacts

Prompt and output-schema artifacts supporting Appendix A of the dissertation research on specification-level security analysis of 5G NAS procedures.

## Files

| Stage / mode | Prompt | Output schema |
| --- | --- | --- |
| Stage 1 — Security Property extraction | [Prompt](prompts/prompt%20Stage%201.txt) | [Schema](schemas/schema%20for%20stage%201%20.txt) |
| Stage 2 — Mode A: SP-Free security analysis | [Prompt](prompts/prompt%20stage%202%20mode%20A.txt) | [Schema](schemas/schema%20for%20stage%202%20mode%20A.txt) |
| Stage 2 — Mode B: Referenced-SP security analysis | [Prompt](prompts/prompt%20stage%202%20mode%20B.txt) | [Schema](schemas/schema%20for%20stage%202%20mode%20B.txt) |

The six `.txt` files are preserved byte-for-byte from the supplied originals, including line endings, prompt wording, embedded JSON templates, and standalone schemas. The schema files retain their original `.txt` filenames and contain JSON.

## Configuration context

Stage 1 is Security Property extraction. The same prompt can be used to extract SPs from a reference or candidate specification by supplying the appropriate input and retrieval corpus. Stage 2 Mode A can likewise be used with an original or candidate specification. Stage 2 Mode B assesses a specification chunk against supplied reference-derived Security Properties. The archived prompts retain the concrete document versions, corpus names, and input placeholders present in the original files; configurations used in a particular experiment should be reported with that experiment.

These files are research artifacts, not findings or a catalogue of confirmed vulnerabilities. The referenced specification corpora and experiment outputs are not included.

## Integrity and citation

[SHA256SUMS.txt](SHA256SUMS.txt) records the SHA-256 digest of each original artifact. For Appendix A, link to the specific prompt and schema files. Use GitHub URLs containing a commit SHA when citing a fixed version, so the citation continues to identify the exact files even if the default branch later changes.
