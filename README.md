# The Code Dungeon User Guide

The public guide at https://codedungeon-guide.vercel.app. The pages here are generated: the text is the same as
the in-app User Guide (press B in the dungeon), from `client/src/ui/userGuideChapters.ts` in
[brainit-consulting/codedungeon](https://github.com/brainit-consulting/codedungeon). Don't edit the `.html` files by
hand. Change the chapters there, then, from that repo's folder:

    npm run guide:site -- <path to this folder>

and commit and push here. Vercel's GitHub integration publishes every push to `main`.

MIT licence, as Code Dungeon: see [LICENSE](LICENSE).
