# Jitsi Rooms Test

A small browser-based test page for Jitsi meeting rooms.

## Run locally
```bash
git clone https://github.com/Gurnoor1-dev/Jitsi-Rooms-Test.git
cd Jitsi-Rooms-Test
python -m http.server 8000
```

Open `http://localhost:8000` in a browser. You can also open `index.html` directly, though serving the files locally more closely resembles deployment.

## Deploy from a terminal
Install the Vercel CLI and deploy the static project:

```bash
npm install -g vercel
vercel
vercel --prod
```

## Deploy on Vercel
1. Import this repository into Vercel.
2. Choose the Other/static framework preset if prompted.
3. Leave the build command empty and use the repository root as the output directory, unless a build step is added later.
4. Deploy and test meeting creation/joining on the production URL.

## Notes
Jitsi access depends on the configured Jitsi server and its browser permissions. Do not put private meeting credentials or service secrets in client-side HTML or JavaScript.