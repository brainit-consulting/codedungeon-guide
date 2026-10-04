# The Code Dungeon User Guide

The public guide at https://codedungeon-guide.vercel.app. The pages here are generated: the text is the same as
the in-app User Guide (press B in the dungeon), from `client/src/ui/userGuideChapters.ts` in
[brainit-consulting/codedungeon](https://github.com/brainit-consulting/codedungeon). Don't edit the `.html` files by
hand. Change the chapters there, then, from that repo's folder:

    npm run guide:site -- <path to this folder>

and commit and push here. Vercel's GitHub integration publishes every push to `main`.

## Watch it first

| [![Introduction to Code Dungeon](images/video-intro.jpg)](https://youtu.be/RzP2SoLmC6Q) | [![Getting started with Code Dungeon](images/video-start.jpg)](https://youtu.be/Mn74ZSlh78U) |
| --- | --- |
| [**Introduction to Code Dungeon**](https://youtu.be/RzP2SoLmC6Q) (2 min 23 s): what it is and how the guild works. | [**Getting started**](https://youtu.be/Mn74ZSlh78U) (2 min 35 s): installing it and your first project. |

Both are in the [Code Dungeon playlist](https://www.youtube.com/playlist?list=PLUwGnHgif6To). The images are kept in
`images/`, which the site build leaves alone.

MIT licence, as Code Dungeon: see [LICENSE](LICENSE).
