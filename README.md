# rust_md_editor
An editor for markdown written in rust based off Kibi and mdcat. Similar to marktext.

Basic plan:
* Type in text
* Once markdown syntax is detected, immediately converts to rendered markdown
* E.g, convert *example* to italic and remove * in user view, but they're still actually there so they can edit them.
* Autofill stuff like bullet points and have some easy means to paste in images and insert tables
* So what I need to do is basically take Kibi as is, but format the buffer before its rendered to screen.
