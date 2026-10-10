FORCE CUBE - upload kit

1. Make a NEW empty GitHub repository (Public).
2. Unzip this file. Click "uploading an existing file" and drag in EVERYTHING inside:
   the src folder, the .github folder, and the .txt files. Commit.
3. If the repo has no .github folder afterwards: open the Actions tab -> "set up a workflow yourself",
   paste the text from WORKFLOW-paste-if-github-folder-missing.txt, commit.
4. Wait for the build (10-15 min first time). Download "forcecube-jar" from the finished run.
   Put the jar in .minecraft/mods with Forge 1.12.2.

The build downloads the official Cleanroom 1.12.2 template at build time, so nothing else is needed.
