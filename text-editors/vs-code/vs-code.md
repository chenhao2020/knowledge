# [VS Code](https://github.com/Microsoft/vscode)

My favorite editor that I use to write code in. I use [many extensions](vs-code-extensions.md) for it.

My config for it can be found [here](https://github.com/nikitavoloboev/dotfiles/blob/master/vscode/settings.json).

I use VS Code [GitHub theme](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme) with [JetBrains Mono](https://www.jetbrains.com/lp/mono/) font. Here is how it looks:

I switch between GitHub Light and GitHub Dark themes as I change between macOS appearances.

![](https://i.imgur.com/ZZTGK1A.png)

> GitHub Light

![](https://i.imgur.com/rd4Ve3X.png)

> GitHub Dark

## Notes

- [VS Code is architected in a way where extensions are not eagerly activated by default. Each extension can declare a list of activation events, such as e.g. opening a file of a certain language, invoking a specific command, starting debugging, etc.](https://news.ycombinator.com/item?id=16940419)
- `Developer: Show Running Extensions` command -> Shows currently running extensions. Is good for profiling.
- [VS Code has excellent integrated node debugging. It integrates seamlessly with the entire tool ecosystem (eg I use ts-node-dev for autoreloading + typescript support, and the VS Code debugger Just Works). And because it's inside the editor, ndb features like the ability to put breakpoints in a file before it is required are irrelevant. It's all at your fingertips, just put a breakpoint right where you're coding, hit F5 to attach the debugger to your devserver and step through the code.](https://news.ycombinator.com/item?id=17581521)
- To hide non useful `Outline` section in sidebar, just open the context menu on the outline section's header and select the "Hide" action.
- [Can use "\*" in the advanced search options in @code to search for similar subfolders across multiple parent folders.](https://twitter.com/SteveGodderidge/status/1285978384049348609)

## Links

- [VS Code Docs](https://code.visualstudio.com/docs)
- [Introductory Videos](https://code.visualstudio.com/docs/getstarted/introvideos)
- [Visual Studio Live Share Docs & Feedback](https://github.com/MicrosoftDocs/live-share)
- [code-server](https://github.com/codercom/code-server) - Run VS Code on a remote server.
- [sshcode](https://github.com/codercom/sshcode) - CLI to automatically install and run code-server over SSH.
- [Vim to Code](https://github.com/asantos00/vim-to-code) - Comprehensive (almost) list of resources, tutorials, and inspiration for migrating to Visual Studio code from Vim.
- [VSCode Keyboard Shortcuts For Productivity (2019)](https://www.youtube.com/watch?v=Xa5EU-qAv-I)
- [VS Code Recipes](https://github.com/microsoft/vscode-recipes) - Collection of recipes for using VS Code with particular technologies.
- [Snippet Generator](https://snippet-generator.app/) - Generate snippets for VSCode/SublimeText. ([Code](https://github.com/pawelgrzybek/snippet-generator))
- [VS Code Tips](https://www.youtube.com/channel/UCyYh-eAr74avLwOyPa1dDNg/videos)
- [code-server](https://github.com/cdr/code-server) - Run VS Code on a remote server.
- [sshcode](https://github.com/cdr/sshcode) - CLI to automatically install and run code-server over SSH.
- [sail](https://github.com/cdr/sail) - Instant, pre-configured VS Code development environments.
- [StackBlitz](https://stackblitz.com/) - Online IDE powered by Visual Studio Code. ([Code](https://github.com/stackblitz/core))
- [The best Parts of Visual Studio Code are proprietary (2020)](https://underjord.io/the-best-parts-of-visual-studio-code-are-proprietary.html) ([HN](https://news.ycombinator.com/item?id=24047638))
