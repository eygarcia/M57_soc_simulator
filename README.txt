CNSE M57 Bash Scripting for Cybersecurity — SOC Mission Simulator
Instructor / Deployment Guide

LEARNING OBJECTIVES
• Build Bash pipelines for collection, filtering, transformation, analysis, monitoring, comparison, and integrity verification.
• Apply variables, parameters, loops, redirection, grep/regex, awk, sed, join, sort, uniq, tail -f, cron, diff, SSH, Nmap-related concepts, /dev/tcp, and checksum baselines.
• Connect Bash scripting to authentication monitoring, web-log analysis, host evidence collection, service exposure monitoring, and filesystem integrity.
• Practice repeatable enterprise cybersecurity workflows rather than isolated commands.

QUESTION COVERAGE
Ch.1: redirection/file descriptors; tee -a; execute permissions
Ch.2: positional parameters; exit status; loops
Ch.3: grep options; regex alternation; auth-log filtering
Ch.4: integrity; Bash as security orchestration; reconnaissance
Ch.5: SSH/local redirection; tar; wevtutil
Ch.6: awk; join sorting; sed
Ch.7: sort + uniq -c; 401/404 anomalies; large-transfer outliers
Ch.8: tail -f; IOC pattern files; tee -a in live monitoring
Ch.9: cron; /dev/tcp; diff on scan snapshots
Ch.10: known-good baselines; sha1sum -c; diff on configuration snapshots

TECHNICAL MODERNIZATION
• The source uses egrep; grep -E is shown in modernized examples.
• sha1sum is retained because it is part of the course material; stronger hashes such as SHA-256 are generally preferred for modern production assurance.
• ifconfig/netstat remain in the course source; modern Linux commonly also uses ip/ss.

GITHUB PAGES
1. Create a GitHub repository, e.g. cnse-m57-bash-soc-simulator.
2. Upload index.html to the repository root.
3. Settings → Pages → Deploy from a branch.
4. Choose main and /(root), then Save.
5. Test the published GitHub Pages URL.

CANVAS EMBED
Use the Canvas HTML editor and replace the URL:
<iframe
  src="https://YOUR-USERNAME.github.io/YOUR-REPO/"
  width="100%"
  height="1200"
  style="border:1px solid #ccc;border-radius:12px;"
  loading="lazy"
  title="CNSE M57 Bash Scripting for Cybersecurity SOC Mission Simulator">
</iframe>

If your Canvas environment strips iframes, post the GitHub Pages URL as an external link that opens in a new tab.

RECOMMENDED CANVAS ASSIGNMENT INSTRUCTIONS
Complete all 30 missions in the CNSE M57 Bash Scripting for Cybersecurity SOC Mission Simulator.
1. Enter your name.
2. Read each scenario and inspect the terminal evidence.
3. Answer each question. Use Hint if needed.
4. Incorrect answers may be retried. Review the feedback before retrying.
5. Complete all 30 missions.
6. At the final screen, take a screenshot showing your name, score, percentage, activity title, and “Mission Complete” status.
7. Upload the screenshot to Canvas.

Accessibility: semantic HTML, keyboard navigation, visible focus, screen-reader live regions, high-contrast mode, responsive design, and prefers-reduced-motion support.

Here’s the simplest way to post your simulation to GitHub.

Go to github.com and sign in.
Click the + in the upper-right corner.
Choose New repository.
Give it a name such as:
network-device-noc-quest
Set it to Public.
Check Add a README file.
Click Create repository.

Now upload your simulation:

In the repository, click Add file → Upload files.
Upload your HTML file.
Rename it to:
index.html

Your repository should look like:

network-device-noc-quest
├── index.html
└── README.md

Then click Commit changes.

Next, publish it with GitHub Pages:

Click Settings in the repository.
In the left menu, click Pages.
Under Build and deployment:
Source: Deploy from a branch
Branch: main
Folder: /(root)
Click Save.

After a minute or two, GitHub should show a live URL similar to:

https://YOURUSERNAME.github.io/network-device-noc-quest/

Open that link in a new tab and test the simulation.

If you later update the simulation, you only need to replace or edit index.html and commit the change. The GitHub Pages URL stays the same.

For your Canvas workflow, I recommend using the GitHub Pages URL as an External URL in your Canvas Module.
