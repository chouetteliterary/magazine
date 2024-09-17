WEBSITE MAINTENANCE

**Notes**
- All changes may take up to 24h to update on the website after comitting

Directory
1. Updating the "current issue" link on the home page
2. Toggling the "submissions closed" text
3. Adding a new issue to the magazine

**1. Updating the "current issue" link on the home page**
  Steps:
  1.  Click on the index.html file
  2.  Click on the pencil icon (top right of the code block) to edit the file
  3.  Scroll until the <!--main content of the landing page--> section
  4.  Find the line: <a class="subtitle" href="issue-01.html">CURRENT ISSUE</a>
  5.  Replace the href element with the new link
  6.  Click on commit changes (x2)

**2. Toggling the "submissions closed" text**
   Steps:
   1. Click on the submit.html file
   2. Click on the pencil icon (top right of the code block) to edit the file
   3. Scroll until the <!--main content of the landing page--> section
   4. Find the code written between <!-- If submissions closed --> and <!-- End -->
   5. Add <!-- after <!-- If submissions closed -->
   6. Add --> before <!-- End -->
   7. The code between <!-- If submissions closed --> and <!-- End --> should now be grayed out/a different colour
   8. Click on commit changes (x2)
  
**3. Adding a new issue to the magazine**
  Steps:
  1. Click on the issues folder and upload the new issue pdf via the Add file button in the upper right side and commit the change
  2. Click on the template.html file
  3. Click on the icon with two squares (top right of the code block) to copy the file contents
  4. Go back to the previous page, click + (next to the green code button), and click Create new file
  5. Paste the copied contents into the new file and rename it, making sure to add .html at the end of the filename(current format: issue-##.html)
  6. Under the <head> section (at the top of file), replace the text between <title> and </title> with ISSUE ##
  7. Scroll until the <!--main content of the landing page--> section
  8. Replace [NAME] in the <iframe> and <a> tag with the actual pdf file name of the new issue
  9. Click on commit changes (x2)
  10. Click on the archive.html file
  11. Click on the pencil icon (top right of the code block) to edit the file
  12. Scroll until the <!--main content of the landing page--> section
  13. Find the line written after <!-- To copy for other issues --> and copy and paste it after the other issues
  14. Replace the href element with the new link of the issue file we just created
  15. Replace the issue number with the desired one
  16. Click on commit changes (x2)
