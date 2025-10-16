


## Local development

```bash
# clone the repository
$ git clone https://github.com/tanx-lab/tanx-lab.github.io.git

# cd in the project directory
$ cd tanx-lab.github.io

# Start local dev server
$ hugo -D server
```

## Add a new team member
Fork the above repository into your github account. Clone and create a new local branch from your forked repository. You need to replace `YourGitHubUserName` with your actual username.
```bash
# clone the repository
$ git clone --recursive https://github.com/YourGitHubUserName/tanx-lab.github.io.git

# cd in the project directory
$ cd tanx-lab.github.io

# create a local branch
git checkout -b newmember
```

Create a new directory `nameLastname` in `content/authors`.
Add your member entry to `content/authors/nameLastname/_index.md`. You can look at other folders such as  ``content/authors/jifutan` for example.
Example entry:
```
---
# Display name
title: Nelson Bighetti

# Is this the primary user of the site?
superuser: false

# Role/position
role: Professor of Artificial Intelligence

# Organizations/Affiliations
organizations:
- name: Stanford University
  url: ""

# Short bio (displayed in user profile at end of posts)
bio: My research interests include distributed robotics, mobile computing and programmable matter.

interests:
- Artificial Intelligence
- Computational Linguistics
- Information Retrieval

education:
  courses:
  - course: PhD in Artificial Intelligence
    institution: Stanford University
    year: 2012
  - course: MEng in Artificial Intelligence
    institution: Massachusetts Institute of Technology
    year: 2009
  - course: BSc in Artificial Intelligence
    institution: Massachusetts Institute of Technology
    year: 2008

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
- icon: envelope
  icon_pack: fas
  link: 'mailto:test@example.org'
- icon: twitter
  icon_pack: fab
  link: https://twitter.com/GeorgeCushen
- icon: google-scholar
  icon_pack: ai
  link: https://scholar.google.co.uk/citations?user=sIwtMXoAAAAJ
- icon: github
  icon_pack: fab
  link: https://github.com/gcushen
# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
# - icon: cv
#   icon_pack: ai
#   link: files/cv.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ""

# Highlight the author in author lists? (true/false)
highlight_name: false

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups:
- Students
---

Nelson Bighetti is a professor of artificial intelligence at the Stanford AI Lab. His research interests include distributed robotics, mobile computing and programmable matter. He leads the Robotic Neurobiology group, which develops self-reconfiguring robots, systems of self-organizing robots, and mobile sensor networks.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed neque elit, tristique placerat feugiat ac, facilisis vitae arcu. Proin eget egestas augue. Praesent ut sem nec arcu pellentesque aliquet. Duis dapibus diam vel metus tempus vulputate.
```

Please save the file as `_index.md`.

Add your headshot to `content/authors/nameLastname` and save it as `avatar.jpg`.

Push upstream:
```bash
$ git push origin newmember
```

And open a Pull Request through the menu on your **forked** repository `tanx-lab.github.io` on github. 