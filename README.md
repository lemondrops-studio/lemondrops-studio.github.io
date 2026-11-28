# lemondrops.dev

The studio page of Lemondrops (레몬드롭스), a one-person studio making small games and
tools: Riftlancer, Pacenote and Loopromeda.

Plain HTML and CSS, no build. GitHub Pages serves `main` at https://lemondrops.dev
(`CNAME`; `.nojekyll` keeps Pages from running Jekyll).

- `works/` holds each work's icon, copied from its project: Riftlancer's store icon,
  Pacenote's app icon and Loopromeda's PWA icon.
- `riftlancer/` is Riftlancer's support page and `riftlancer/privacy/` its privacy
  policy, in English and Korean, which the App Store and Google Play link to (they
  moved here from blog.ashon.dev/projects/riftlancer/ on 2026-11-21). The policy
  must stay true to the game: change it before a build that collects anything.
- `lamplight-fm/privacy/` is Lamplight FM's privacy policy, in English and Korean,
  which Google Play links to (since 2026-11-28). It says the app collects nothing and,
  on Android, has no network permission; change it before a build that adds one, or
  Play Billing's purchases.
- The page carries no business details (상호, 대표자, 사업자등록번호, address, phone)
  for now. The stores show the seller's details where they sell; if the page ever sells
  anything itself, they go in the footer, with the 통신판매업 신고번호.

Preview it locally:

```sh
python3 -m http.server 4410 --bind 127.0.0.1
```
