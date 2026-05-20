# Contributing

Thanks for helping keep this list up to date! 🎉

## How to add an entry

1. **Pick the right file.** Models go in `README_FOUNDATION_MODELS.md`, `README_TASK_SPECIFIC_MODELS.md`, or `README_MULTIMODAL_FUSION_MODELS.md`. Datasets go in the matching `README_DATASETS_*.md` file.
2. **Use the existing table format.** Don't introduce new columns unless absolutely necessary — pick the table whose schema best fits your entry.
3. **Include working links.** Every entry should have at least:
   - a paper link (arXiv preferred, or journal DOI), and
   - a code link (GitHub or Hugging Face) if available.
4. **Add a one-line description** in the appropriate column (size, modality, backbone, etc.).
5. **Keep alphabetical or chronological order** within each table when possible.

## Quality bar

- The model / dataset should be **published** (peer-reviewed or arXiv preprint) — no blog-post-only entries.
- Prefer **publicly available** code and weights. Gated / closed resources are accepted but should be marked as such (e.g., `(gated)` or `(closed)`).
- Avoid duplicates — search the existing tables first.

## PR checklist

- [ ] Entry added to the correct sub-README
- [ ] Paper link works
- [ ] Code / dataset link works (if applicable)
- [ ] Description is one line and accurate
- [ ] No duplicate of an existing entry

## Reporting issues

If you find a broken link, a factual error, or a duplicate, open an issue with the offending row and the corrected version.
