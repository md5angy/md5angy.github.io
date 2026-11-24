# md5angy.github.io — Miller Lab

Static Miller Lab homepage for apps, games and experiments by `md5angy`.

## Local preview

From this directory, run:

```text
python -m http.server 8000 --bind 127.0.0.1
```

Then open `http://127.0.0.1:8000/`.

## Manual owner action

Complete [`app-ads.txt`](app-ads.txt) at the repository root with the exact approved advertising-provider line(s). Do not invent or guess a Publisher ID.

## GitHub Pages publication

1. Push this repository to the `md5angy` GitHub account as `md5angy.github.io`.
2. Open the repository on GitHub and choose **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the default branch (normally `main`) and the `/ (root)` folder, then select **Save**.
5. Wait for the Pages deployment to complete and verify `https://md5angy.github.io/`, `https://md5angy.github.io/robots.txt` and `https://md5angy.github.io/app-ads.txt`.

The `.nojekyll` file keeps this static site free from Jekyll processing. No commit or push is performed by this task.

## Related projects

- [RepPulse website](https://md5angy.github.io/reppulse-web/) — website online; Android app coming soon.
- [Flappy AI](https://md5angy.github.io/flappy-ai/) — live browser experiment.
