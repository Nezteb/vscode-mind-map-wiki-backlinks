# VS Code Wiki Backlinks and Mind Maps

Original idea/motivation: https://nitter.net/Nezteb/status/1648148867173715970 (though the original idea didn't include the wiki backlinks in comments)

There are many "visualize X piece of a project in code" but none where X is "docs/comments/second-brain".

Represent code/architecture as hand-built graphs that lives in a language-agnostic way alongside the code.

### Random Ideas / Questions

- How do you have code review comments/questions live alongside code in a non-intrusive way?
  - Probably a separate project entirely
  - Separate CLI tool with VS Code extension to use it?
  - Pure `git` integration (+ GitHub/GitLab connectors)
- CMD+click to follow wiki-style links (with line/row/col numbers?)
- Table view of nodes that link to/from currently viewed node, support CMD+CLICK
- Eclipse Sprotty vs Mermaid.js for rendering graphs (with comments)?

### References

- Original code flow extension:
  - https://github.com/Pjaerr/Code-Flow-Extension
    - https://github.com/Pjaerr/Code-Flow-Extension/issues/42
    - https://github.com/Pjaerr/Code-Flow-Extension/issues/45
- VS Code markdown notes (does what I want, but only for markdown files)
    - https://github.com/foambubble/foam
    - https://github.com/dendronhq/dendron 
    - https://github.com/kortina/vscode-markdown-notes
      - https://github.com/kortina/vscode-markdown-notes/issues/198
- A cool concept to consider:
  - https://github.com/anas-araid/vscode-infinite-workspace
- A similar extension for inline bookmarks, but no linking:
  - https://github.com/tintinweb/vscode-inline-bookmarks
- VS Code relative file link are apparently broken:
  - https://github.com/microsoft/vscode/issues/181435
  - https://github.com/microsoft/vscode/issues/189382
- Commercial products:
  - https://www.codesee.io/
  - https://appmap.io/

### Extension Dev

- https://code.visualstudio.com/api/get-started/your-first-extension
- https://github.com/microsoft/vscode-extension-samples
- https://www.typefox.io/blog/using-sprotty-in-vs-code-extensions/

Also see [the Yeoman generated README here](./GENERATED_README.md).
