# ViewForge site

Public pages of ViewForge, served with GitHub Pages:

- `index.html` - home page (Google OAuth consent screen: application home page)
- `privacy.html` - privacy policy (Google OAuth consent screen: privacy policy link)
- `connect.html` - the redirect page of creator invites: it explains the invite, sends the creator to the
  Google sign-in, and shows the code that the creator sends back to the agency

The source lives in the `site/` folder of the private ViewForge repository; this public repository is a
copy. The pages load no external scripts, fonts or trackers. The code on `connect.html` only works together
with the PKCE verifier and the client secret, which never leave the agency's ViewForge.
