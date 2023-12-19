# VS Code Wiki Backlinks and Mind Maps

[Original idea/motivation Tweet](https://nitter.net/Nezteb/status/1648148867173715970) (though the original idea didn't include the wiki backlinks in comments)

You remember [the old "this is why you shouldn't interrupt a programmer" comic](https://web.archive.org/web/20131101003403/https://heeris.id.au/2013/this-is-why-you-shouldnt-interrupt-a-programmer/)?

There are many "visualize X piece of a project in code" but none where X is "docs/comments/second-brain".

Represent code/architecture as hand-built graphs that lives in a language-agnostic way alongside the code.

### Random Ideas / Questions

- How do you have code review comments/questions live alongside code in a non-intrusive way?
  - Probably a separate project entirely
  - Separate CLI tool with VS Code extension to use it?
  - Pure `git` integration (+ GitHub/GitLab connectors)
- CMD+click to follow wiki-style links (with line/row/col numbers, or hash of line?)
- Table view of nodes that link to/from currently viewed node, support CMD+CLICK
- Eclipse Sprotty vs Mermaid.js for rendering graphs (with comments)?

### References

- Original code flow extension:
  - https://github.com/Pjaerr/Code-Flow-Extension
    - https://github.com/Pjaerr/Code-Flow-Extension/issues/42
    - https://github.com/Pjaerr/Code-Flow-Extension/issues/45
- Code Tour (does what I want, but doesn't store the "tours" as regular text/comments)
  - https://github.com/microsoft/codetour
- VS Code markdown notes (these do what I want, but only for markdown files)
    - https://github.com/foambubble/foam
      - https://github.com/foambubble/foam/issues/1307
    - https://github.com/dendronhq/dendron
      - https://github.com/dendronhq/dendron/issues/3963
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
  - https://web.archive.org/web/20210705001921/https://marketplace.visualstudio.com/items?itemName=Adaptilab.grok (gone/defunct)

### Extension Dev

- https://code.visualstudio.com/api/get-started/your-first-extension
- https://github.com/microsoft/vscode-extension-samples
- https://www.typefox.io/blog/using-sprotty-in-vs-code-extensions/

Also see [the Yeoman generated README here](./GENERATED_README.md).
