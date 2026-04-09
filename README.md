# Prototype Hub

Unified home for product prototypes managed in one repository.

## Structure

- `prototypes/mj7`: MJ7 prototype snapshot
- `prototypes/minimax-speech`: MiniMax speech prototype snapshot
- `prototypes/libtv-author-tag`: LibTV author tag admin prototype and source snapshot

## Branch Strategy

- `main`: shared hub, GitHub Pages entry, and all prototype directories
- `proto/mj7`: working branch for MJ7 changes
- `proto/minimax-speech`: working branch for MiniMax speech changes
- `proto/libtv-author-tag`: working branch for LibTV author tag changes

## Pages Paths

After this repository is connected to GitHub Pages:

- `/prototypes/mj7/`
- `/prototypes/minimax-speech/`
- `/prototypes/libtv-author-tag/`

## Notes

- `my-visualization-page` is intentionally left out because it is not part of the prototype set.
- `prototypes/libtv-author-tag/source` keeps the original editable source snapshot next to the published preview.
