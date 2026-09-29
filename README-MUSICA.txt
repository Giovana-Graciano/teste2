MUSIC BOX — DEPLOYMENT NOTE

The Music Box tracks are embedded directly in create.html as data:audio/mpeg.
Generated friend cards embed their selected audio in the JSON.

Therefore the audio/ and audio_mp3/ folders are NOT required for this version.

For GitHub Pages, upload the CONTENTS of this folder to the repository root:
index.html, create.html, script.js, style.css, admin.html, love-file.json, etc.
Do not upload this ZIP itself as the website.

A friend's own audio file is embedded in the generated card JSON, so it also
does not need a separate audio folder.
