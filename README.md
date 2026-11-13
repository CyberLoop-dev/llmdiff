<p align="center">
  <img src="assets/banner.svg" alt="llmdiff banner" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML-single%20file-22c55e?style=for-the-badge" alt="single file">
  <img src="https://img.shields.io/badge/dependencies-zero-eab308?style=for-the-badge" alt="zero deps">
  <img src="https://img.shields.io/badge/100%25-local-3b82f6?style=for-the-badge" alt="local">
  <img src="https://img.shields.io/badge/license-MIT-a78bfa?style=for-the-badge" alt="MIT">
</p>

**llmdiff** compares two LLM answers word by word. Swapped models? Tweaked your prompt? Paste both outputs and instantly see what was added, what was removed, and how similar they are.

## Use it

1. Open `index.html` in your browser. No server, no build.
2. Paste answer A and answer B.
3. Read the highlighted result: <ins>green</ins> is new, <del>red</del> is gone.

It updates live as you type. Nothing is uploaded.

## What you get

- Inline word-level diff (longest common subsequence)
- Counts of added and removed words
- A similarity score from 0 to 100%
- One-click swap of A and B
- Handles up to 3,000 words per side

## Good for

- Comparing two models on the same prompt
- Checking how a prompt tweak changed the answer
- Reviewing edits an AI made to your draft
- Spotting silent changes between two runs

## Notes

- Comparison is word-based and ignores line breaks and extra spaces, so you see wording changes rather than formatting noise.
- Similarity is `2 x shared words / total words`.

## License

MIT
