MKTG1025 Help: deployment package
=================================

Four files. They are published together on GitHub Pages and shown inside a Canvas page with an iframe.
Canvas cannot run the page itself (RMIT's Canvas does not render uploaded HTML files, and it strips scripts
from pages), so the page lives on GitHub Pages and Canvas shows it in a frame.

First time (about five minutes)
1. Sign in at github.com (create a free account if you do not have one).
2. New repository: name it mktg1025-help, Public, no template, Create repository.
3. On the empty repository page choose "uploading an existing file", drag in all four files, Commit changes.
4. Settings, Pages, Build and deployment: Source "Deploy from a branch", Branch "main", folder "/ (root)", Save.
5. Wait a minute, refresh Settings, Pages, and GitHub shows the address: https://YOURNAME.github.io/mktg1025-help/
6. Open that address on your phone. The home screen should load with the search bar and the three doors.

Canvas page
1. Open the Canvas page (or create one, for example "Help with your assessments") and click Edit.
2. Switch the editor to HTML view (the </> icon at the bottom right of the editor).
3. Paste the code below, change YOURNAME to your GitHub user name, Save.

<iframe src="https://YOURNAME.github.io/mktg1025-help/" width="100%" height="720" style="border:0" title="MKTG1025 Help"></iframe>

To open the frame on the Assessment 2 section list, end the address with #a2; Assessment 3, #a3; the Assessment 1
questions, #a1. So on the Assessment 2 page: src="https://YOURNAME.github.io/mktg1025-help/#a2"

If Canvas keeps the frame at a fixed height instead of fitting it to the content, students scroll inside the frame.
Raise the height to 900 if that happens.

Updating the content
Edit MKTG1025_Help_Answer_Bank.xlsx, save the Answers, Sections and Links sheets as CSV UTF-8 with the names
answers.csv, sections.csv and links.csv, then in the repository choose Add file, Upload files, drag the changed
CSV files in, Commit changes. GitHub Pages republishes within a minute or two. index.html changes only when the
interface changes.

Linking to one page (staff)
Add the ID to the address: https://YOURNAME.github.io/mktg1025-help/#A2-06 or #A3-S02. Students do not see IDs.
