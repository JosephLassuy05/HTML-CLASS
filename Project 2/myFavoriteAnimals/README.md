# Learn By Doing: Creating hyperlinks

Creating Hyperlinks

In this exercise, you will create several hyperlinks. Make sure you have watched all the videos and read all the documents Online Activities before doing this assignment.

1. Create a folder

On the desktop (or other location which you easily access), create a folder called "myFavoriteAnimals". This folder will be the grand-daddy folder that contains all other documents and folders.

2. Create a subfolder

Navigate to myFavoriteAnimals folder, create a folder named "myFavoriteCats". This folder is also called the child folder of myFavoriteAnimals folder.

3. Create an HTML file

Using a text editor, create a file and named it as myCuteAnimals.html. Save this file to myFavoriteAnimals folder. Now you have one html file and one folder in the myFavoriteAnimals folder.

4. Create contents

Now we need to put some contents in myCuteAnimals.html. Enter all the necessary tags, start with the doctype tag <!DOCTYPE html>, and include the <html> tags, the head tags, the title tags inside the head tags, and the body tags. Inside the body tags, make a <h1> and </h1> tag pair, enter the words "My Cute Animals" between the opening and closing tags, finally save the file. 

5. Create hyperlinks

You will create several types of hyperlinks in myCuteAnimals.html. One type of hyperlink is called absolute link. An absolute hyperlink is one that has the complete url address with the format http://hostname.domainName.rootDomain/documentName. Follow the steps below:

a. Create a plain absolute link 

Below the h1 tags pair, create a hyperlink using the follow address (without the beginning and ending double quotes):
"https://www.google.com/search?q=beautiful+animals&tbm=isch&ved=2ahUKEwjUt9zin6PuAhUNSKwKHW01Cg4Q2-cCegQIABAA&oq=beautiful+animals&gs_lcp=CgNpbWcQDFAAWABg0L4gaABwAHgAgAEAiAEAkgEAmAEAqgELZ3dzLXdpei1pbWc&sclient=img&ei=DlMEYNT4Go2QsQXt6qhw&bih=406&biw=853&rlz=1C1CHBF_enUS876US876">"

Use "My Cute Animals" as the link text. The link text is what the user sees.
Hint: <a href="https://www.google....."> My Cute Animals </a>

This is your first hyperlink in myCuteAnimals.html. Save the file, and view it with a browser. You can do that by right click on the file, select "Open with" and choose a browser to open.

b. Create an absolute link with the target and title attributes

After you have opened myCuteAnimals.html with a browser. Click on the only link there. Did you notice that the original page is replaced by a google page? What if we want to keep the original page, and a new window for the target page? We are going to make a link like that next.

Insert a line break after the previous hyperlink to start a new line.
Create a link with the target attribute to be new window (set the target attribute to "_blank"), use https://www.discover-the-world.com/blog/20-of-the-worlds-best-wildlife-holidays as address and "Wild Animals" as the link text, include a tooltip using the title attribute that shows the tip "Beautiful Wild Animals". The format is <a href="http://.." target="_blank" title ="Tip">link text</a>.

Now, you have 2 links created in myCuteAnimals.html. Open the file with a browser that make sure the second link open the target page (the Discover of the World ) in a new window, and the original page does not disappear. 

c. Create a relative link

So far, the two links you made linked to pages in servers on the Internet somewhere. The pages are not local to the computer that houses the page myCuteAnimals.html. For pages that are local to the computer, we could use relative link. There are 4 situations: 1. The target page is in the same folder as the source page (the page that has the hyperlinks), 2. The target page is in a subfolder, 3. The target page is in a parent folder,  4. The target page is the same page. We will look at each situation.

1. Target and source pages are in the same folder.

To link to a page in the same folder, simply use the file name.

Still working with myCuteAnimals.html, create a third hyperlink to another file that does not exist yet. We are going to call this file BigCuteAnimals.html and it is going to be in the myFavoriteAnimals folder. Use "My Cute Big Animals" as link text. The format is <a href="filename.html"> link text </a>.

By now, you have 3 links, one is a relative link and the other two are absolute links. The relative link points to a file that has not been created yet. Your job now is to create the BigCuteAnimals.html, and place it the myFavoriteAnimals folder. In this html file, put some text like "This is the Cute Big Animals page".

Now, your myFavoriteAnimals folder has 2 files, myCuteAnimals.html and BigCuteAnimals.html and one folder myFavoriteCats.

It is time to check the relative link. Open myCuteAnimals.html with a browser. If you click on the relative link, the BigCuteAnimals.html should appear. If you want the BigCuteAnimals.html to appear in a new window, you would have to include the "target=_blank" attribute inside the <a...> tag. 

2. Relative link to a document in a subfolder. 

To link to a page in a subfolder, include the name of the subfolder in the href attribute value. 

If you follow the previous instructions closely, myFavoriteAnimals folder should have a subfolder called myFavoriteCats (If yours does not have one, create one now). Use your text editor to create a HTML document called myCuteCats.html and save it in myFavoriteCats.  

So far you have the myFavoriteAnimals folder, in which you have a subfolder called myFavoriteCats. In myFavoriteCats folder, you have a file called myCuteCats.html.

Open myCuteAnimals.html in myFavoriteAnimals folder and create a relative link to myCuteCats.html in myFavorite folder. Use "My Cute Cats " as link text. In this relative link you have to include myFavoriteCats folder name in the href attribute of the hyperlink. eg. <a href="myFavoriteCats/myCuteCats.html">

By now you have placed a relative link in myCuteAnimals.html to myCuteCats.html, which is in the myFavoriteCats folder. 

3. The target file is in a parent folder.

To link to a file in a parent folder, you have to move out of the current folder, that way you are into the parent folder. The trick is to use the command "../" which means "go out of the current folder and into the parent folder. If you write "../../", the command will move to grand parent folder and so on.

To create a good navigation for a web site, you should always have a link that links to the main page. In here we want to have a hyperlink in myCuteCats.html, which is in myFavoriteCats folder, that links to myCuteAnimals.html, which is in myFavoriteAnimals folder. Therefore, in myCuteCats.html, create a relative link that links to myCuteAnimals.html. Use the link text "Go back to the main page". 

General Hint: Determine the relative location of the source and target file. If the target file is in the parent folder, the format would be <a href="../Filename.html"> Go back to the main page </a>
The "../" part says - go to the parent folder. You can have "../../", here you would go to the grandparent folder.

4. Link to the same page, but a different part of the document.

To do so, you need to hash tag the source, and name the target.

Before we create such a link, copy and place the following img tag (will be covered later) after the last relative link in myCuteAnimals.html. 
<img src="https://qph.cf2.quoracdn.net/main-qimg-805c1319833c0743cd8d614577a7b5e7">

This image is used to provide space to show the effects of named link tags. 

Source

Working with myCuteAnimals.html, at the bottom of the document, after the img tag, create a "source" link to the target which does not exist yet. The users will see the link text "Go to the top" (hint: using <a href="#goToTop"> Go to the top </a>). 
When users click on the link, the document should scroll to the top near the phrase "My favorite cars" which we will make it the target link. You may not see the effect if you do not have enough contents in the page.

Target

How does it know where in the top it will go to? You will need to mark a place using a named link. This is the target tag. Now add a target tag near the phrase "My favorite hyperlinks" at the top of myCuteAnimals.html. It should look something like <a name="goToTop"></a><h1> My favorite Cars </h1>. You will not see it as a link, but it marks the location for the source link.  The name attribute tells you it is a target link. 

Test and make sure all the links work properly before submission.

6. Submit your work

The myFavoriteAnimals folder should contain myCuteAnimals.html, BigCuteAnimals.html, and myFavoriteCats folder. The folder, myFavoriteCates should contain myCuteCats.html. If all look good, zip the myFavoriteAnimals folder and submit it to HTML II dropbox.

Always zip your submissions. I will not be able to read your files correctly if they are not compressed.

7. Take the quiz

Take the HTML II Quiz at Assessments -> Quizzes.