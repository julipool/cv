# Publishing this as your GitHub resume repo

1. Create a new repository at https://github.com/new named `resume` (so it lives at `github.com/julipool/resume`) — public, no template.
2. From this folder, run:
   ```bash
   git init
   git add README.md
   git commit -m "Add resume"
   git branch -M main
   git remote add origin https://github.com/julipool/resume.git
   git push -u origin main
   ```
3. GitHub renders `README.md` automatically on the repo's homepage — no extra setup needed.
4. Optional: pin this repo on your GitHub profile (Profile → Customize your pins) so it's the first thing visitors see.
5. Optional: if you'd rather this appear directly on your GitHub *profile page* (not just a repo), create a repo named exactly `julipool` (matching your username) with this same README — GitHub treats that one specially and shows it at the top of your profile.
