# Git-Practice-Abdalrahman-Obeidat
</br>
<h1>Theoretical Questions</h1>
<h2>1. What is the difference between Git and GitHub?</h2>
<h3>Git</h3>
<p>
  <strong>Git </strong>strong>is a Version Control System used by developers, individuals, and companies to track changes made to code and projects over time.
  I can use Git offline, locally on my personal computer, and all changes I make are saved on my device.
  In companies, Git helps teams work efficiently—every team member can work on their assigned task or part of the project independently, without waiting for others    to finish.
  Once I complete my part, I can upload (push) my changes to the project’s Git repository, whether it’s hosted on GitHub or an internal company server. At that        point, all our work gets merged into one shared project.
  Git keeps a full history of changes, including:
  <ul>
    <li>Who made the change</li>
    <li>When it was made</li>
    <li>What exactly was changed</li>
  </ul>
  As long as I’m working locally, I don’t need an internet connection.
  However, when I want to push my changes to share them with the team, I need to be connected—either to the internet (for GitHub) or to the internal company network   (for a private server).
  And yes, if I don’t want to use GitHub or any external platform, I can still push my code to a private Git server hosted by the company, and Git will work just as   well without relying on public services.
</p>

<h3>GitHub</h3>
<p>
  <strong>GitHub</strong> is a web-based platform designed to host software projects that use Git
  Simply put, GitHub is not Git, but it’s a tool that makes using Git easier and more collaborative online.
  GitHub allows companies and individuals to upload their work, collaborate as a team, share code, review each other’s work, track issues, and document everything   in a visual and organized way.
  It provides a graphical user interface, detailed information about each commit, and makes it easier for teams to organize and merge their work.
  It also offers options for :
  <ul>
    <li>Public Repositories</li>
    <li>Private Repositories</li>
  </ul>
</p>
<h2>2. Explain the difference between `git pull` and `git fetch`.</h2>
<h3>Git Fetch</h3>
<p>
<strong>Git fetch</strong> retrieves the commits that your teammates have pushed to the remote (GitHub),and stores them locally in special remote-tracking branches, such as origin/main.
It does not merge those changes directly into your current working branch.
In other words, it brings in the updates and keeps them locally, without modifying your existing code.
You can use git fetch if you want to review the new changes first and compare them with your current work.
If everything looks good, you can run<strong> git merge origin/ branch-name </strong>to merge the updates into your local branch.
</p>
<h3>Git Pull</h3>
<p>
<strong>git pull = git fetch + git merge</strong></br>
 It fetches the changes from the remote (like GitHub) and immediately merges them into the local branch you're currently working on.
The updates are not applied to the remote branch, but rather to your local branch,
such as main on your machine.
</p>

<h2>3. What is the purpose of `.gitignore` file?</h2>
<h3>.gitignore</h3>
<p>
<strong>.gitignore</strong> is a plain text file used within a project where you list specific file names, file extensions, or folders that you want Git to ignore and not track or upload to the server (like GitHub or a company repository).
It's typically used in the following cases:
   <ul>
    <li>When the files are sensitive, such as files containing passwords or credentials.</li>
    <li>When the files are specific to your local machine and shouldn't be shared with the team, such as editor settings.</li>
    <li>When the files are temporary or generated automatically, like build outputs or logs, which don’t need to be stored in Git.</li>
  </ul>
  <strong>Additional Notes:</strong>
  Git won’t ignore files that were already tracked before you added them to .gitignore. To stop tracking them, you can use:
  <strong> git rm --cached filename</strong>
</p>

<h2>4. Describe the steps to contribute to an open-source project on GitHub.</h2>

<ol>
  <li>
    <h4>Fork</h4>
    <p>You take a copy of the open-source project and add it to your own GitHub account, so you can work on it freely without making           any direct changes to the original project.</p>
  </li>
  <li>
    <h4>Clone</h4>
    <p>You download a copy of the project (the one you forked) to your personal computer so you can work on it.</p>
  </li>
  <li>
    <h4>Branch</h4>
    <p>The purpose of creating a new branch is that instead of working directly on the main branch that the whole team relies on, you          create a separate branch for the changes you plan to make, so your work is more organized and easier to review and merge later.</p>
  </li>
  <li>
    <h4>Modify the code</h4>
    <ul>
      <li>Add a new feature</li>
      <li>Fix a bug</li>
    </ul>
  </li>
  <li>
    <h4>Commit</h4>
    <p>Save all the changes you have added or modified along with a descriptive explanation of what was done.</p>
  </li>
  <li>
    <h4>Push</h4>
    <p>Upload the changes to the server or GitHub.</p>
  </li>
  <li>
    <h4>Pull Request</h4>
    <p>Request the team leader or the person responsible for the main project to review the changes you made, and if everything is fine, they merge them into the main project.</p>
  </li>
  <li>
    <h4>Waiting for the review of the changes</h4>
    <p>In case changes are requested on your work or it gets rejected.</p>
  </li>
</ol>

,ا3


