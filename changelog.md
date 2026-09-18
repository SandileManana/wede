Secunda mighty stars fc
1. Home Page
changes made to yhe website :
-removed all internal css in the home page and converted it to separate stylesheet home.css linked by (link rel ="stylesheet")
-fixed structural errors in  home.html corrected the spellings typos,corrected the spellings of Mighthy to mighty 
-fixed the footer of the home page by removing the inline backround color style and fixed the <ul> that was sitting inside the <p>.
-added the initial colors of the club of which is red,white,black,blue and the font (Oswald for headings,Inter for body text) loaded via google fonts
-increased the hero sectionfrom small  image to full bleed image using 70vh to ensure it fills viewport height on any screen. i also changed the hero section pictures and changed the meet the squad button into styled button using btn-primary
-i slightly changed the layout of the home page by merging the next match widget and league standings into a single fixture,results and standings section with one call to action button instead of two disconnectted pieces as i did in part 1
-developed the hero section  by changing the pictures and added a appropriate picture and changed 
-changes the message in the hero to embalenhle to the world.
-expanded the news grid to contain match report,squadnews ,club news
-improved the club statistics section and gave it a structure
2.Aboutus page
-i completelty rebuild this page to make it more organized that it was
-i added a proper page title,google fonts and the base.css that uses the same header for the rest of the website and the about us css structure 
-i also added a new page banner section of which provides a new clear heading
-i expanded the club history by adding the promotion and nedbank appearce
-improved the structure with each value explained 
- i added the home ground location as google maps iframe
-i added a enquiry form that allows visitor to input name,email,reason for enquiry as a dropdown and text box

3.Fixtures& results page
-added the external css structuress of which is the base and fixture.css 
-added a page banner which describes whats happening in the page.
-i added a form section which presents the last three game results that shows the results and opponent
-designed the upcoming fixtures into a fixture-list that included 3 upcoming match days that provided the match details and ticket information
-i also added the league standings to be part of fixtures and results instead of the user having to refer back to the home page to check next opponent performance on the table 

4.News
-improved the news page by adding its css structure and the base css to match the rest of the pages and allowing the page to have its own style as well
-added the fans image in the banner to engage the fans making it about them
-also added the latest news section in this page of which uses structered news grid presenting new stories as individual cards containing  information about that story
-changed the news stories and alligned it to the current news of secunda stars

5.Teamprofile or squad
-in this page i also added the base structure and teamprofile.css to give the page its own styling 
-added a page banner to introduce the team profile
-organized players by positon to make it easier for visitor the know which is which
-changed the basic images to player cards with each card containg the player picture ,number,name and position.
-i used one default image in the player cards because of lack of indiviual pictures

6. introduction of the css structure
the css folder contains base.Css,home.css,fixtures.css,news.css,teamprofile.css
.the base.css
-provides styles that are shared in every page of the website
-contains styling for page reset,body typography,headings,links,header,buttons,footer and the general layout to make it easy for myself by not repeating styles on every page.
-i created variables club-red,club-red-dark,club-blue,bg,white,grey-text,border,max-width to make easier to change values in one place
-i also made my website responsive
-used reusable structures for news,players and coaches
-used btn and btn-primary to create usable button styling which is used in all buttons

7.images
-i added more images to improve the visual represantation

## 12. References

The following online resources were used as learning references while developing and improving the Secunda Mighty Stars FC website. The videos were used to understand web development concepts and were not copied directly into the project.

### YouTube References

1. Traversy Media. (2020). *Build a Responsive Website | HTML, CSS Grid, Flexbox & More*. YouTube.
   Available at: https://www.youtube.com/watch?v=p0bGHP-PXD4
   Accessed: 18 September 2026.

   Used for: Understanding website structure, navigation bars, CSS Grid, Flexbox, cards, forms, footers and responsive design. The tutorial covers these areas as part of building a responsive website.

2. Learn Web. (2023). CSS Flexbox Responsive Cards – Frontend Simplified. YouTube.
   Available at: https://www.youtube.com/watch?v=0m5e1V7g8kM
   Accessed: 18 September 2026.

   Used for: Understanding how to create responsive cards using HTML and CSS. This was relevant to the news cards, player cards and other content sections used on the website.

3. Coder Coder. Responsive 4-Column Layout with CSS Grid – Build a Responsive Website from Scratch. YouTube.
   Used for: Understanding CSS Grid, responsive layouts, card spacing, images, border-radius and hover effects.

4. EGATOR. How to Create a Responsive Website Using HTML and CSS – Complete Tutorial for Beginners. YouTube.
   Used for: Understanding multi-page website structure, navigation menus, Google Fonts, CSS variables, media queries and responsive layouts.

5. Brian Design. HTML, CSS, and JavaScript Website Design Tutorial – Beginner Project Fully Responsive. YouTube.
   Used for: Understanding how to organise a multi-page website, create navigation, hero sections, footers, use Google Fonts and link different HTML pages together.

How the References Were Used

The references were mainly used to improve my understanding of HTML and CSS while developing Part 2 of the project. I used them as learning material to understand concepts such as responsive layouts, navigation, cards, forms, CSS Grid, Flexbox and page structure.

The final Secunda Mighty Stars FC website was developed and adapted for the requirements of my own project. The content, football club information, page structure and design decisions were adjusted for the specific website rather than simply copying a tutorial project.
