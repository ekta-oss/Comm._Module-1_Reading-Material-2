# Reading Card: What Signs Tell Us

Everyday Workplace Communication · Module 1 · Segment 5: Reading Signs — The Wrong Room · **Stage 5.2**, in the Swift AI Academy frame.

A static website: plain HTML, JavaScript, CSS, fonts, images and audio. No server and no build step are needed to host it.
Built from `module1-segment1/` with `node scripts/build-site.mjs 5.2`. Do not edit these files by hand; change the source and rebuild.

## Publish on GitHub + Vercel

1. Put this folder in a GitHub repository (it can be the whole repository, or one folder in it) and push.
2. In Vercel choose **Add New → Project** and import the repository.
3. If this folder is not the repository root, set **Root Directory** to this folder.
4. Set **Framework Preset** to **Other**. Leave the build command and output directory empty.
5. Choose **Deploy**. Vercel gives you an `https://….vercel.app` link.

GitHub Pages also works: Settings → Pages → deploy from the branch and folder that hold `index.html`.

## Try it on your own computer

```bash
npx serve .
```

Then open the address it prints. Double-clicking `index.html` does not work, because browsers block these scripts on `file://` pages.

## Content status

How it works: the learner reads the text on the page; the questions open after they reach the end. There is no audio for the passage. Each glossary word has a speaker that plays only that word and its meaning (`media/audio/M1_S05_02_GLOSS_<word>.mp3`, interim computer voice: replace a file with a recording of the same name and push again). Each attempt is recorded in the browser as `5.2.reading-log`.

The reading passage, glossary meanings and model answers are a **draft for content review**. They are adapted from Simple English Wikipedia, ‘Sign’ and ‘Traffic sign’ (CC BY-SA 4.0), and keep the script's first and last sentences word for word.
