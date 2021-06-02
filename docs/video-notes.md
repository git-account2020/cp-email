- Listen to video
- Make a time stamp at each new point
  - Try to write them as if they were general steps
  - If its still on the same point add subpoints underneath
- add brackets if possible
- After you get stuck or after about 10 min stop and try to code it yourself based on the instructions from the time stamps
  - you will have to go back and watch the video 
- As you go back and watch the video and code fill in the missing steps in the timestamps as subpoints

## Laydown the content and Header
0:00 Make main <table>
  - Add styling
  - width:100%
  - cellspacing="0"
  - cellpadding="0"
  - border="0"
1:30 Make <tr> > <td>
  - add styling
  - width:600px;
  - align: center;
  - cellspacing="0"
  - cellpadding="0"
  - border="0"
4:10 Leaving comments
  - start of htmlemail
  - end of htmlemail
    - start of container
    - end of container
      - start of main row
      - end of main row
5:50 After creating one row copy the section and paste for as many rows you have
6:20 Close the rows until you are going to work with them
7:20 First row
  - make secoundary <table> inside the <td>
7:40 copy code for table and paste it for the new <table> (column)
  - you will be using the same code for all the tables
8:10 Edit your table style
  - class="container";
  - add styling;
  - width:50%;
  - align: center;
  - cellspacing="0"
  - cellpadding="0"
  - border="0"
- Used <td> for small text
11:50 align left and align right
  - we do this because <td> is basically a cell (column) that aligns everything vertically. So when you put tables in side them they will initially be veritcally aligned
12:00 Put <img> inside of <td>
12:40 Gradient background
  - google ultimate css gradient generator
  - get the the color for beginning of the image gradient
    - copy the color into the beginning section of the generator
  - get the the color for end of the image gradient
    - copy the color into the end section of the generator
  - Verify the gradient direction and change it if needed
  - Copy the css
13:50 Add css gradeint to the style of table 
  - Add the copied css inside one style="" attribute
  - Add it all on one line
    - no enter
    - delete comments
17:00 add text and header to a gradeint table
  - Copy the text from the design
    - text doesn't have to be the exact same text just same amount of lines and size
  - Add links
19:00 Create a new column table with menu links
  - Create a <td> for each menu <a>
22:00 Add an image to the column
  - Add it after the <table>

## Style and Header
0:00 Add fonts
0:30 Search "open sans" from google fonts
  - Use the link
  - customize it 
    - check light 300
    - regular 400
    - bold 700
    - extra bold 800
  - copy the link
1:11 Add the font <link> to <head>
1:21 Add the font-family
  - Copy the font-family from google-fonts
  - Paste it into the style for the <td> which will give it to all of the elements inside it
2:15 Setup fallbacks if person doesn't have open-sans
  - https://css-tricks.com/snippets/css/better-helvetica/
    - Don't need the light fonts
  - Add them to <td>
  - If you started your style with double quotes you will have to add the fallback fonts with single quotes
  - 'Helvetica Neue', Helvetica, Arial, 'Lucida Grande', sans-serif;"
3:50 Style the font for your  tags in the first column
  - copy and past the style from <td> and add it to the the other columns <td>
  - change header font size

5:20 Use google chrome tools to test what size looks closets
  - inpsect the element
  - go to computed tab
  - double click on font-size 
  - use up or down to change the zie until it looks like you want

5:30 Column styling
  - h1 
    - font-size= 80 px
    - margin=  0
    - font-weight: 300
    - line-height: 1
      - this brings the h1 down
  - h2
    - font-size= 30px
    - margin = 0
  - table
    - padding: 15px;  
  -button
    - .ghost-btn
    - border-radius: 3px 
    - border: 2px solid white
    - text-decoration: none;
    - color:white;
    - padding: 10px(top/bottom) 15px(left/right); 
    - text-transform: upper-case;
  -p (11:25)
    - copy style from h1
      - will edit 
    - font-size: 16px;
    - line-height:1.5 
    - font-size: 16px;
    - font-style: italic
    - padding: 20px 0px;
  -h2(14:00)

## Style the Header pt2

0:50 Add comments ()
  - beginning of left column
  - end of left column
  - beginning of right column
  - end of right column
1:05 Change the class name of the table container
  - .header-left (for left column)
  - .header-right (for right column)
2:20 Move img file into its on <td>
3:00 Styling the top Menu
  - copy the <td> styling from main container
5:00 style the menu links
  - Determine what is the color 
  - Add the color <td> styling
  - Add styling to all of the <a> tags(5:30)
  - Guess font-size
  - Add font-size
  - Guess font-weight
    - 14px
  - Add font-weight
    - 600
  - Remove text-decoration
    - text-decoration:none
  - Align the <td> center
  - Add padding to the <table>
    - 20px;
9.00 style img
  - <td>  align center
  - valign="bottom"
9.50 Push the image down
  - Make it align with left column
  - Add padding
    - paddting-top 50px;
  - Use chrome tools to test the look before making changes to html
  - Add padding the style of <td>
11:20 Change the font

## Lets do rows and layout styles

0:20 Change comments 
- Start of main row = Start of header row 
- End of main row = End of header row
1:20 Hero h3 
1:55 Edit comment name of row
3:00 Create table for first colum
- Copy inline code from left column table (3:20);
- Width="33.33%"
- Paste two more columns
5:00 For each row in the column create <tr><td></td></tr>
- do that three times 
5:30 Create table for icon
- Copy the inline code from container from left column
- Remove inline style code except for padding
6:25 Delete the other tables
6:40 Add comment to top and bottom of left column
- Start of left column
- End of left column
8:15 Insert image inside <td></td>
- img/bell_icon.png
8:30 Add text inside <td></td>
- Notify
8:50 Add the font
- Coppy font from other text
- Change the color
  - #333333
9:50 Change the background color of section
- Change color of main table
  - style="background: #fafafafa"
 13:20 Create a paragraph on a new row 
 - tr>td>p
 - Add paragraph lorem
 14:00 create <a> link on a new row
 - tr>td>a
 - copy style from previous <td>
 - edit padding 
 - edit text-transform
 15:30 Edit spacing inside icon table and class name 
 - class name = .title icon
 - change  padding = 0px
 17:30 style paragraph
 - copy the style from the previous <td> and add it to the <p>
 - remove the padding
 - remove the text-transform

 18:10 style the <a>
 - change the color 
  - use tool to determine the color from diagram
  - change the color in the style
  - text-decoration: none
18:50 create a secound column based similar to another
- copy the first column
  - start right above the first  <table> in the first column end after the last </table>
- paste it right after the previous column
- edit the comments for that column to reflect the new name
  - start of middle column
  - end of middle column
- edit any picture names
  - should just have to edit a word or two
  - remember to have a naming convention for your images
- edit any headers

20:30 Create a third column based on a similar 
- copy the first column
  - start right above the first  <table> in the first column end after the last </table>
- paste it right after the previous column
- edit the comments for that column to reflect the new name
  - start of middle column
  - end of middle column
- edit any picture names
  - should just have to edit a word or two
  - remember to have a naming convention for your images
- edit any headers

21:00 Style header
- copy the text style from inside the column <td>
- Change the font size
- Change the font weight
- Change the padding

24:00 Style paragraph that are similar
- Find the color of the paragraph from template
- add it the style of <p>
- Change the weight
- Change line height
- Copy finished styles and paste on all of the other paragraghs that need the same styling


## most advance row layout and styles
### Row with Image, header, two columns
1:20 Start a new row
  - Copy <table> previous row's column
  - Edit row comments
    - start of advanced row
    - end of advanced row
  - edit color of table <table>
    - background: white;
    - add white even if background normally white
2:10 Add image only row
  - tr>td>table>tr>td>img
    - this gives us more control of the image
  - add copied styles to that table   
3:40 Create a new row header only
- Copy the whole <tr> from the above row
- Paste it below the the previous rows <tr>
- Copy header text from template
- Delete the content inside the <td> and replace it with header content 
- Copy the style from a previous header(if possible)
  - find the prievous header
  - copy all of the style
  - add the style to current header
9:20 differnt font styles side by side
- createa span around the text that changes
- change the font-weight
  - higher the weight the bolder the text
11:40 Create column
12:40 Create a new row with two columns
- tr>td >table
- copy the all of the <table> inline code from a previous table
- inside the <table> tr> td
- Change the width based on how many columns
  - 1 column 100%
  - 2 columns 50%
  - 3 columns 33.33%
- copy the table above and paste it again for the 2nd table (column)
- inspect with chrom dev tools to make sure the tables boxes show up where they should be (even though technically nothing there)
14:00 Add paragraph
- add paragraph inside <tr><td> that you already create
- copy the code from preivous <p> if applicable
- add text from template
16:00 Add a row with  Google Play icon
- copy the whole <tr><td><p> and everything from inbetween in that we just finished and use it as a quick template for a new row
- delete the content between the <td> </td>
- add the image in place of the deleted content
- add any alignment changes to the <td> if needed
17:30 Add secound column 
- copy the code from the column you just finish and add it into a <table> right under it.
  - if the <table> was already created you can add what was needed or copy over top of it
- edit any image names
- change any alignments in the <td>
- Edit any padding issues between the two columns
- Make sure both columns columns styling is the same
## One app row layout and styles
### Create a row with image taking up the whole row
0:00 Copy inline code from another table
0:30 Edit the comment for the row to reflect the new name
1:00 Add inline code to to <table>
1:10 add <tr><td> inside the table
1:45 add <img> inside the <table>
2:00 add inline code to <table> 
- change the background color of the <table>
-  fix any padding issue between the two
- Change the class name of the <table>
  - make it similar to the name of the row with hyphen between spaces
6:15 Add 100% width to <img>
# Join Together row layout and styles
## Header, 3 columns (image, header, paragraph, link)
7:50 Copying styles you will use over and over again on a seperate sheet
- Look through the layout and see what sytles are duplicated

### column ( icon and h3  then paragraph next row)
- 1st row
  - add a table
  - add a <td> for the <img> and another for the text
  - edit the <td> inline code for each
    - copy any inline code that is duplicate from earlier in the project
    - add appropiate width for each
- 2nd row
  - copy the first row
  - paste the 2nd row below the first
  - edit changes
    - comments
    - <img>
    - <p>
    - <h2>




### Note Taking steps
- Listen to video
- Make a time stamp at each new point
  - Try to wright down what to do a general steps. Don't need specific values 
    - Find the color
    - change the weight
    - Add line height
    - Search for color name
  - If its still on the same point add subpoints underneath
- Add brackets if possible (for tags)


### Questions
  - On line 48 why put the watch on the outside of the table?
  - why doesn't chrome developer tools let me edit the my code
  - what is line-height;
  - Use table rows tr when wanting content to go down & use tables when wanting columns left-right.  You get max control over items when using tables. Awesome!!!

### Learned
- Start a new row
  - tr>td>table
  - edit comment for start and end of row
- Column == <table>
- Start a new table
  - copy the inline code from another table
  - add it the new table 
  - edit inline code
    - Change <table> class name 
      - <table class="class-name">
    - edit color of table <table>
    - background: white;
    - add white even if background normally white
    - change width="" property to matche the amount of columns
      - 1 = 100%
      - 2 = 50%
      - 3 = 33.33%
- Add tr>td inside the table
- Insie the <td> add the content for the first row inside the new column
  - <h3>
  - <img>
  - <p>
- Create a new row inside the column
  - tr>td
- Add styling to tags
  - See if the styling is duplicate from previous tags
    - if so copy that stying into the new tags
  - Make any align adjustments to the styling
    - Usually on <td>
- Fix any padding issues
- Fix any margin issues
- Add comments
  - start of column 1 (2,3 etc)
Copy the whole column including the comments
  - usually <table> to </table>
Paste it as many times as need for duplicate columns(if needed)







___________________________________________________



- User border="1" on each column table for diagnostic purposes
- Make changes in chrome dev tools
  - Inspect element
  - Computed tab
  - find what you want to change
  - click on the arrow
  - double-click on the number you are trying to change
  - use you mouse scrow to change the positon until you find what you want
  - Then make changes to code
- Center an object
  - Add align ="center" to table as an attribute
- Make sure columns (tables) side by side 
  - style with the float property
    - two columns = float:left, float:right
    - three columns = float:left, float:left, float:right
- Make a list of all the actions and combine them together to make a to do list of steps for each section
  - tables
  - columns
  - headers
  - paragagraphs
  - images
- Use <br> tags if content is shown to have a break in the template
- If the background is white throughout the template you can change the body to bacground:black to help make things standout
- Step for troubleshooting tutorial videos
  - When a user
- Move an image without affecting the spacing
- text-transform
  - capilize = capitalize each word in the text
  - Uppercase = make each word Uppercase
- Negative margin can be used to exapand a box similiar to padding
- Easily copy the sections of code. Use the arrow to condense the code then copy it
- If you have a paddding error on multiple <table> 
  - Add padding 0 so you can access the new padding
  - Start editing the new padding