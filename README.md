# casualphoenix.github.io

Tiny public site used by Nate's personal Android apps.

* `.well-known/assetlinks.json` — lets Android open `https://casualphoenix.github.io/shopping/...`
  links straight in **Shopping Companion** (package `com.casualphoenix.shopping`, signed with the
  same key as Nate's other apps). The fingerprint is public information, not a secret.
* `shopping/back/` — fallback page with an "Open Shopping Companion" button, shown only if a link
  opens in the browser instead of the app.
* `.nojekyll` — makes GitHub Pages publish the `.well-known` folder.
