# mcz-media

Large static media for Music ConnectZ, served by GitHub Pages at
https://ctkoth.github.io/mcz-media/ so the app repos stay small enough to
clone.

- `exercise-demos/` — BodieZ exercise demo videos, self-recorded by Corey
  with the rights to use them. The backend stores each as
  `/exercise-demos/<file>.mp4`; the frontend's `src/media.js` resolves that
  to this site.

Add a file here, not to the frontend's `public/`. Renaming or deleting one
breaks the demo link for whichever exercise points at it.
