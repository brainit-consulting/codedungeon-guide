# The Code Dungeon User Guide

The public guide at https://codedungeon-guide.vercel.app. The pages here are generated: the text is the same as
the in-app User Guide (press B in the dungeon), from `client/src/ui/userGuideChapters.ts` in the private
`brainit-consulting/codedungeon` repo. Don't edit the `.html` files by hand. Change the chapters there, then:

    npm run guide:site -- H:\codedungeon-guide

and commit and push here. Vercel's GitHub integration publishes every push to `main`.
