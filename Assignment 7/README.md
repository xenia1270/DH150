# DH150 -- Assignment 07: High Fidelity Prototype -- by Jiaqi Zhou (Xenia)

## Description of project  
My research is to evaluate the design of a healthcare site -- Healthline. Healthline is a healthcare website that provides health and wellness information. By collecting qualitative and quantitative data, we are able to get insights into how well the website supports users to accomplish their goals. The research will be based on Jakob Nielsen's 10 Usability Heuristics to identify design issues on the Healthline website.The target users are people aged from 18 to 50 with wider familiarity with the online environment. After the Usability test, I was able to conduct both quantitative and qualitative studies to get insights into how people use health-related websites. These findings are useful for creating persona and prototypes to improve the site features.

Recall three features:
- Feature No.1: Professional guides

- Feature No.2: Simplicity

- Feature No.3: Accessibility

Purpose: The purpose of this high fidelity prototype is to convert the low fidelity wireframes into a high fidelity demo. With a high fidelity prototype, we are able to present our product in details and have target users validate the concepts. During the usability testing, the users can interact with the components, layouts, and colors to help us improve the product. 

Process: I first converted the idea from the low fidelity wireframes by setting up the header, footer, menu, and contents in each page. Then I add buttons and icons to increase clarity and readability. I also applied the layout grid (12 column) to ensure consistency across the page. Next, I adjusted the color of the buttons and texts by using Contrast Checker. Lastly, I added the interaction to each button and made sure they were assigned to the correct page. 
![layout grid](https://github.com/xenia1270/DH150/blob/master/Assignment%207/Layout%20grid.jpeg)


Tasks:
- Convert low fidelity prototype to high fidelity prototype
- Create the header, footer, menu, and contents
- Check the color contrast for the accessibility WCAG2.0 AA level
- Test interactions of every buttons
- Ensure legibility and readability by choosing a font style
- Add appropriate icons to communicate a concept quickly


## Graphic design
### Representative screen designs
![](https://github.com/xenia1270/DH150/blob/master/Assignment%207/Representative%20screens.jpeg)

### Description of decision making
- Color: before I applied colors to the prototype, I ran the audits to check the color code on the original website. The audits showed the background and foreground colors do not have a sufficient contrast ratio. The foreground color is iris blue (#01ABD9) and the background color is white (#FFFFFF), which results in a 2.73:1 contrast ratio. To increase the brightness between two colors, I used WebAIM to adjust the lightness of the foreground color and checked which color will give a contrast ratio larger than 4.5:1 to target the WCAG (level2, AA) recommendation. I decided to use the bahama blue (#1F5A7F) for the foreground color with white background (#FFFFFF). Some texts are in black font color (#000000), which has very high contrast with the white background. As for the original footer, the background color is light orange (#FBF5ED) and foreground colors include black (#000000), grey (#918F8F), and iris blue (#01ABD9). The color contrast between light orange and grey, light orange and iris blue are pretty low, so I decided to change the background color to seashell (FFF8F5), texts in grey are changed to black (#000000), and texts in iris blue (#01ABD9) are changed to bahama blue (#1F5A7F). 
  - Note: the names of colors are found from <a href="https://www.htmlcsscolor.com/">HTML CSS Color Picker</a>
- Images and icons: I tried to keep the original images choices like those on the articles, news, and doctor’s profile picture thumbnail. I changed the picture on the home page by including a picture of a doctor because the original home page contains too many images from different articles, which could not give users a good first impression. With an image of a doctor on the home page can convince users that lands on the website that the site is professional and trustworthy. I noticed that the healthline website does not have any icons, so I added some icons to some of the pages to engage users and communicate the ideas more effectively. 
- Typography: the original font (Proxima Nova) looks legit and readable, and I wanted to keep the original font. However, I could not find the same font in Figma. I decided to use Source Sans Pro, which is one of the most used fonts on medical websites. 

  Sources:
  - <a href="https://www.ilovewp.com/resources/medical/wordpress-for-hospitals/most-used-google-fonts-on-hospital-websites/">Most Used Google Fonts on Hospital Websites</a>
  - <a href="https://o360.com/blogs/choosing-the-right-typography-for-your-medical-website/">Choosing the Right Typography for Your Medical Website</a>
- Button corner radius: the buttons on the original website have sharp corners, which is too rigid and less distinguishable. To make buttons more standout, I changed the corner radius to 10 to keep the site’s professionalism and reduce distraction. 



## Impression test
Link to impression test: https://www.youtube.com/watch?v=Hx2xwZsz4VM

Summary of findings:
- The user's first impression was an image of two men (but actually there's only one man) and the color blue
- The user believed the color blue matched the theme of the healthcare website, and the image reflected a sense of professionalism 
- Even though the user felt the size of the image looked good to him, he could not recall the "wellness tool" section below the image during the 5-second impression test. Therefore, I'm considering whether I should adjust the size of the content in the landing page. 

## Accessibility (color-contrast) check
### Before
![color-contrast 1](https://github.com/xenia1270/DH150/blob/master/Assignment%207/Checker1.jpeg)
![color-contrast 2](https://github.com/xenia1270/DH150/blob/master/Assignment%207/Checker2.png)
![color-contrast 3](https://github.com/xenia1270/DH150/blob/master/Assignment%207/Checker3.jpeg)
![color-contrast 4](https://github.com/xenia1270/DH150/blob/master/Assignment%207/Checker4.jpeg)
![color-contrast 9](https://github.com/xenia1270/DH150/blob/master/Assignment%207/Checker9.jpeg)

### After
![color-contrast 5](https://github.com/xenia1270/DH150/blob/master/Assignment%207/Checker5.jpeg)
![color-contrast 6](https://github.com/xenia1270/DH150/blob/master/Assignment%207/Checker6.jpeg)
![color-contrast 7](https://github.com/xenia1270/DH150/blob/master/Assignment%207/Checker4.jpeg)
![color-contrast 10](https://github.com/xenia1270/DH150/blob/master/Assignment%207/Checker10.jpeg)

### Not sure whether to add to the prototype
One of the text color on the original site is vivid pink (#E0218E) when users hover over the texts or buttons before they click on them. However, I was not sure whether I should included this color in my prototype since I did not want to mislead my peers/participants. I checked the color contrast between vivid pink and white background, and the ratio is 4.39. The text color should be at least strong pink (#D61F87) to create higher contrast from the white background.
![color-contrast 11](https://github.com/xenia1270/DH150/blob/master/Assignment%207/Checker11.jpeg)
![color-contrast 12](https://github.com/xenia1270/DH150/blob/master/Assignment%207/Checker12.jpeg)

## Interactive prototype & Diagram
Link to the prototype:https://www.figma.com/proto/umZ7583ao6VNpD4n4IUHMp/Assignment-07?node-id=1%3A695&viewport=7235%2C7551%2C0.7571569085121155&scaling=min-zoom

Without interaction
![Wireframe](https://github.com/xenia1270/DH150/blob/master/Assignment%207/Wireframe.jpeg)

With interaction
![Wireflow](https://github.com/xenia1270/DH150/blob/master/Assignment%207/Wireflow.jpeg)


## Cognitive walkthrough

Quotes from remote group
- On Symptom Checker page: 
  - "I don't fully understand what this box is. Is it a menu? but it has checkboxes which makes me think I can select more than one?" 
  - "I think to follow the same pattern as the rest of the page, I would left justify the text. Also being next to the check box makes it easier to follow/make sure its the right box to check."
  - "I also am not entirely sure what the function of this is."
- On Symptom Results page: 
  - "Maybe saying "click here" is redundant? it feels like a very long block of text. Maybe the button could just say something like "Schedule a doctor appointment."" 
  - "This seems like a lot of unused white space, maybe shorten page."
- On main menu: 
  - "Does this also allow me to find an online doctor? I'm just curious."
  - "Why does clicking on tools lead me to the symptoms page?"
- On Health Topics page: 
  - "Maybe having some suggested health topics would be useful here."
  - "Is the keyboard necessary? would users not use the one on their computer or phone?"
- On Goal Tracker page: "Maybe have some indication of the date would be helpful? or what week this is being logged for."
- On Home page: 
  - "This is really nit picky but I would like a bit more pink border on this side."
  - "I think creating more of a difference in text size between the title here and the options below, and also the 'wellness tools' header and the options below it would give more of a sense of categorization upon first glance."
  
Summary of findings:
- Some of the feature on the tools' pages are confusing. For example, they did not know why the Tools page would take them to the Symptom Checkers, which was the first page of the Tools. They found that the side menu with checkboxs was unclear as they did not know whether these were one of the selections/choices or buttons to use other tools. 
- Some buttons contained too many words, so I should cut down to make it look clearer. 
- The text size of title should be adjusted to make the it more distinguishable.

## Usability Testing
Link to UT: https://www.youtube.com/watch?v=XBQid_JGuh8

## Revision(s)
Revision #1
![Revision after UT](https://github.com/xenia1270/DH150/blob/master/Assignment%207/revision1.jpeg)

Note of changes:
- Enabled View/Print PDF and Download button for users to print their medical records 
- Resized the map on the medical records page
- Changed the button shape on the confirmation page
- Specified the articles are written by professionals and have fact checked
- Allowed users to type in keywords using their keyboards
- Separated article and discussion board
- Added a pathway on the top of the article to remind users how to get back to the last page they were on
- Re-designed the goal checker page, so users can write notes if they want instead of just checking the boxes
- Added interation on the goal checker page

Revision #2 (after in class cognitive walkthrough)
https://github.com/xenia1270/DH150/blob/master/Assignment%207/revision2.jpeg

Note of changes:
- Removed the side menu on Symptom Checker page and added a page listing all the tools
  - The plan was to add a drop-down menu so that users can see what items are included when hovering over the "Tools." However, I realized that I may need to add it on every page. Instead, I decided to create a Tools page so when users click into the Tools page they can see what kind of tools are available.
- Remove the "Help" item from the menu since I realized it might be redundant
- Included some suggested topics on the Health Topics page
- Simplified the apoointment scheduling button
- Included a calendar on the Goal Tracker page
- Change in font of site title to Source Serif Pro to make it more discernible

## Reflection

The process of creating a high fidelity portfolio was smooth as a whole since I already had a pretty solid structure from low fidelity portfolio. Even though it took me a while to get familiar with Figma, it works well to visualze the information and interactive components. There were some setbacks when making decisions on colors and buttons. For example, when I made decision on changing the text and background color, I had to consider whether they have sufficient color contrast, and I will try to keep the color as close to the color on the original site as possible but with a higher contrast. Also, since the original site only has a hamburger menu and contain too many items in one navigation, I needed to redesign a horizontal site menu to help users find content easier. After I received feedbacks from my peers, I made changes on some of the buttons, and added a drop-down menu to make it look more intuitive.

----------------------------------------------------------------------------------------------------------------------------
Credits:
- https://www.olark.com/api/system_hb_chatbox_size/
- https://www.softwarepundit.com/practice-fusion
- https://patient.info/forums/discuss/browse/depression-683
- https://www.pinterest.com/pin/136937644899236124/

