# mbalis-bmb.github.io

GitHub Pages user site. It exists to serve Android Digital Asset Links at the domain root:

https://mbalis-bmb.github.io/.well-known/assetlinks.json

`.nojekyll` is required: Jekyll would otherwise skip the `.well-known` directory.
The fingerprint is the SHA-256 of the Home Energy Hub debug signing certificate. Add a release certificate only after
one exists and its fingerprint has been read from the keystore or the signed APK.
