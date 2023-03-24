# Lesson 7 Project
The client from your previous lesson was impressed by your work and has hired you again. Within the next few weeks, they will be working with you closely to create a website for their new computer company.

They have worked with you previously to create a template, now they have provided you with instructions on how to style the page. They plan to use the same style and structure for all pages in their web site, with stylistic changes to each web page so the content on the page appears unique but the structure of the web page is uniform across the entire web site.

It is imperative for this lesson that you preview your template page in VS Studio Code so that you can see your changes in real time. The preview panel in VS Code will automatically update your website every time you save your page in VS Code, therefore you should save after each change you make.

## Project Prep
1. If you haven't done so already, clone the repo to your computer within your course folder.
2. Open the repo within VS Code. You can open this `readme.md` file within VS Code to view the project directions there. 

   > **TIP:** Right click on the file and choose the `Open Preview` option.
3. If there are files and folders present other than this `readme.md` file, take some time to familiarize yourself with the files within the repo so you know where they are located. This will help you when asked to use them within the project directions.

   > **TIP:** Before beginning any work on the project, read through all the steps to understand what you will be doing.

4. Using the Explorer Pane in VS Code, create a subfolder in your Lesson 7 course folder called: **images**.

    > **TIP:** See [How To: Create a Subfolder in VS Code](https://riosalado.coursearc.com/index.php?cID=14714#vssubfolder) if you need help creating a subfolder.
0. Move the image file included in the repo to your **images** subfolder.

<br>

## Adjust the Template

1. Open the **template.html** file and update the following:
   1. Within the HTML comment, add your section number and the lesson number.
   2. Within the HEAD, add your first and last name as the author.
   3. Within the footer, add your MEID to the copyright and update the year, if necessary.
2. Add an unordered list to the navigation element.
   1. Add five list items and add a placeholder link to each list item so that you have a total of five links.
   2. Change the display text to the links to display five pages:
      1. Home
      2. Contact
      3. Computer Information
      4. Services
      5. Accessibility
   3. Do not change the target page for each link, as you'll be adding working links as you move on.

## Example Project
![Screenshot of Example Project without CSS](https://raw.githubusercontent.com/rsc-cis133DA-in-v12/CourseResources/main/L7-example1.png)

## Style the Template

For the next steps you will need to apply appropriate CSS declaration blocks and selectors to style the page according to the directions. For any CSS property values not specifically defined for you, you will need to determine the value on your own. 

Use this as your opportunity to experiment with padding, margins etc. to adjust the look and feel of the web page!

1. Add an internal style sheet to the appropriate section.
2. Add a CSS comment that displays: **Header Styles**
3. Style the body to:
   1. Specify the text font as a set of sans-serif styled fonts.
   2. Set the default font-size to 100%.
4. Style the header to:
   1. Apply a background image using the image provided to you.

   > **TIP:** The URL is relative to the location of the style sheet, not the web page. Review [Lesson 6: Background Images](https://learnatrio.com/3RPtZZD) for more information.
   2. Set the background so it does not repeat
   3. Center position the background
   4. Adjust the background size to covers the entire element.
   5. Apply a top and bottom padding.
   6. Remove all margins.
5. Style the first-level heading to:
   1. Specify the text font as a set of serif styled fonts.
   2. Center align the text.
   3. Set the text color to white using a color method of your choosing.
   4. Add a top and bottom padding.
   5. Remove all margins.
6. Style the unordered list within the navigation element to:

   > **TIP:** Create an appropriate selector that targets only the unordered list within the navigation element. If you do not, any future lists you add to your page will be given the same styles you be applied above instead of only styling the navigation bar.
   1. Remove the bullets from the list.
   2. Add a background color of your choosing to the full width of the navigation bar.
   3. Define the top and bottom padding to the same value and remove the left and right padding.

   > **TIP:** Remember this value, you'll use it again shortly!
   4. Remove all margins.
7. Style the list items within the navigation element to: 
   1. Display side-by-side (horizontally). Keep the padding you applied in the previous step.
8. Style the links within the navigation element to:
   1. Set the text color to white using a color method of your choosing.
   2. Remove the underline below each link.
   3. Define the padding using the value you used for the unordered list, use the same value for all four sides.

   > **TIP:** Notice if you don't use the same values what happens to your navigation bar - elements will overlap, giving your navigation and unfinished appearance.
9. Style the hover state of the navigation links to:
   1. Add a background color of your choosing.
10. Add a CSS comment that displays: **Main Styles**
11. Style the main element to:
   1. Add a background color of your choosing.
   2. Define the padding on all four sides to the same value.
12. Add a CSS comment that displays: **Footer Styles**
13. Style the footer to:
   1. Add a background color of your choosing.
   2. Set the text color to white using a color method of your choosing.
   3. Define the padding on all four sides to the same value.
   4. Center align the text.

 ## Example Project
![Screenshot of Example Project with CSS](https://raw.githubusercontent.com/rsc-cis133DA-in-v12/CourseResources/main/L7-example2.png)


## Submit the Project
Before you submit your project:
1. Save your files and apply any final commits to your work.
2. Push (i.e., sync) the repo on your computer with GitHub to ensure all files are uploaded for your instructor to see.
3. Verify that all files appear on GitHub.

   > **TIP:** You can view any of your repos by going to the GitHub organization for the course - [RSC-computer-technology](https://github.com/rsc-computer-technology). You can bookmark the page for future reference. 
4. Open the Pull Requests tab within GitHub (or using the GitHub Extension within VS Code).
5. In the comment field, 
   1. Type in your instructor's username with an `@` before. See the course announcements for their username to use. 
   2. Put a note to your instructor that the assignment is ready to grade.
6. Click on the `Comment` button to finalize and submit your assignment to GitHub for review.
7. Lastly, submit the Project to your **Gradebook** using the steps within **Assessing Your Learning** in Lesson 7.
