BIRTHDAY SURPRISE WEBSITE — VS CODE / GITHUB / NETLIFY

WHAT IS INCLUDED
- index.html: the complete website code (HTML, CSS and JavaScript are all in this one file).
- assets/: create this folder yourself and add your three personal media files (instructions below).

1. OPEN IT IN VS CODE
1) Download and extract birthday_surprise_website.zip.
2) Open Visual Studio Code.
3) Choose File > Open Folder and select the extracted birthday_surprise_website folder.
4) Open index.html in VS Code. The website code is already in this file; you do not need to paste separate CSS or JavaScript files.

2. ADD HIS VIDEO, PHOTO AND SONG
1) In VS Code's Explorer panel, right-click the project folder and choose New Folder. Name it exactly: assets
2) Put his video inside assets and rename it exactly: his-video.mp4
3) Put his photo inside assets and rename it exactly: his-photo.jpg
4) Put the song inside assets and rename it exactly: song.mp3
Your folder should look like this:
  birthday_surprise_website/
    index.html
    README.txt
    assets/
      his-video.mp4
      his-photo.jpg
      song.mp3
Use an MP4 video, JPG photo and MP3 audio. The photo is used for the jigsaw puzzle and as the video poster.

3. PERSONALISE THE WORDS AND PASSWORD
1) In index.html, press Ctrl+F and search for: const CONFIG = {
2) Edit the values inside that CONFIG section. Change the password, hisName, yourSignOff, birthdayLetter, bingoItems and finalMessage.
3) Keep the quotation marks and commas in place. For the bingoItems list, keep the square-bracket format and each item in quotation marks.
4) Save with Ctrl+S.
The on-screen keypad is numeric; if you choose a word password, he can type it in the password box using his keyboard.

4. PREVIEW IT
You can install the free VS Code extension called Live Server, then right-click index.html and choose Open with Live Server. Or open index.html directly in a browser for a basic preview. Test the password, envelope, bingo, puzzle, video and music.

5. PUBLISH WITH NETLIFY (FREE PLAN AVAILABLE)
1) Create a GitHub account if you do not already have one.
2) Create a new private GitHub repository.
3) In VS Code, use Source Control to initialise the repository, commit the project, and publish/sync it to your GitHub repository. Alternatively, upload the project files through GitHub's website.
4) Create/sign in to Netlify and choose Add new project / Import an existing project.
5) Connect GitHub, select your private repository, and deploy. For this plain HTML site, you do not need a build command; the publish directory is the project root (often shown as .).
6) Netlify gives you a website address ending in netlify.app. You can share that address with him. Your GitHub repository can stay private while the deployed website is accessible to anyone who has the link (unless you configure extra access controls).

IMPORTANT
- The password screen is a playful entrance, not real security. Because this is a static website, the password and media files can be inspected or accessed by someone technically curious. Do not put private or sensitive information here.
- The free hosting plan and its limits can change. A free plan is not a lifetime guarantee; keep a copy of the project and media files on your own computer.
- Background music may not autoplay on some phones until he taps the Play music button.
- Keep the video compressed so the site loads quickly on mobile.
