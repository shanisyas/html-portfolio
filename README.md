# html-portfolio
Learning HTML Elements 

<!DOCTYPE html> 
    <html lang=" english"> </html> 
<head> <h1> Project Website </h1> </head> 
<hr\> 


<!-- HTML Paragraph Elements -->
<body>
<h3> A Notes on Terminology </h3>
<p> Entrepreneurship is a prime initiator of all economic activities in a capitalist economy. On the definition of entrepreneurship, the word originally is derived from a French verb “Entreprendre” which means “to undertake” and Richard Cantillon is said to have first coined the phrase in his manuscript in 1730. </p>  
<p> Entrepreneurship is the process of identifying and utilising available resources and opportunities to convert (deliver) an idea into the form of a product or service to the economic market. Entrepreneurship development represents changes in a society. Economic transformation, across the globe, is a reality today. </p> 
<p> Therefore, entrepreneurs should develop skills to see and understand future, convert ideas into actions, have the determination to create something new and utilise all kinds of resources effectively. Talent (people), business, socio-political environment, and the government will pay key roles in the entrepreneurship development.</p>
<p> 
I love Chloé <br>
I love myself <br> 
</p>
</body>


<!-- The Best Movies Project -->
<br>
<br>
<h2> The Best Movies According To Vivi </h2>
<h3> My Top 3 Movies of All-Time </h3>  
<hr>
<h4> The English's Patient </h4>
<p> This is my very first favorite movie. </p>
<h4> The Pianists </h4> 
<p> A very historical movie about World War 2. </p>
<h4> Little Women </h4>
<p> This movie heals my inner-child </p> 
<br>


<!-- The List Elements -->
<br>
<h1> Vivi's Cinnamon Roll Recipe </h1>
<h2> Ingredients </h2>
<h3> For The Dough: </h3> 
<ul>
    <li> 3/4 cup of milk </li>
    <li> 1 egg plus 1 egg yolk </li> 
    <li> 3 cups of bread flour </li> 
    <li> 2 1/4 teaspoons yeast </li>
</ul>
<h3> For The Filling: </h3>
<ul>
    <li> 2/3 cup dark brown sugar </li>
    <li> 1/4 cup butter </li>
</ul>
<h2> Instructions </h2>
<ol> 
    <li> Mix the milk with the yeast, sugar and eggs </li>
    <li> Melt the butter and add to the mixture </li>
    <li> Add in the flour and mix until combined into a dough </li>
    <li> Knead the dough for 10 minutes </li> 
    <li> Transfer the dough into a large bowl and cover with eggs </li>
    <li> After the dough has doubled in size, roll it out </li>
</ol>
<br>


<!-- Nesting and Indentation -->
<br>
<h1> Nesting and Indentation </h1>
<ul>
    <li> A </li>
    <li> B </li>
        <ol> 
            <li> B1 </li>
            <li> B2 </li> 
                <ul> 
                    <li> B2a </li>
                        <ul> 
                            <li> B2aa </li> 
                            <li> B2ab </li>
                        </ul>
                    <li> B2b </li>
                    <li> B2c </li>
                </ul>
            <li> B3 </li>
                <ol> 
                    <li> B31 </li>
                    <li> B32 </li>
                </ol>
        </ol>
    <li> C </li>
</ul>
<br>


<!-- My Favorite Websites Project -->
<br>
<h1> My Top 5 Favourite Websites </h1> 
<ol start="6">
    <li> <a href="https://www.w3schools.com"> W3 Schools </a> </li>
    <li> <a href="https://www.producthunt.com"> Product Hunt </a> </li>
    <li> <a href="https://www.codedex.io"> Codedex </a> </li>
    <li> <a href="https://www.upskillist.com"> Up Skillist </a> </li>
    <li> <a href="https://www.parallels.com"> Parallels </a> </li>
    <li> <a href="https://github.com"> GitHub</a> </li>
</ol>
<br> 


<!-- Adding Image Elements -->
<br>
<h1> Image Elements </h1>
<h3> I Am A Dog Person </h3> 
<img src="https://raw.githubusercontent.com/appbrewery/webdev/main/puppy.gif" alt="A Dog Digging The Sand"/>
<br>
<br>


<!-- A Birthday Invitation Project -->
 <br>
 <br>
<h1> It's My Birthday! </h1>
<h2> On the 22th December </h2>
<img src="https://raw.githubusercontent.com/appbrewery/webdev/main/birthday-cake3.4.jpeg"
        alt="Purple Birthday Cake"/> 
<h3> What to bring: </h3>
<ul>
    <li> Ballons (I love ballons) </li>
    <li> Cake (I love eating) </li>
    <li> An Appetite (There will be lots of food) </li>
</ul>
<h3> This is where you need to go: </h3>
<a href="https://maps.app.goo.gl/6RExXWwDvTsvr4jB6"> This is my location </a>
<p> Thank You!! </p>
<br>
<br>


<!-- Absolute and Relative Paths --> 
<h1> All The Animals </h1>
<h2> Rabbit: </h2>
<img src="./rabbit.png" alt="How to add an image in the same parent folder (./) or in different folder/outside current folder (../)"/>
<h2> Cat: </h2>
<img src="./cat.png" alt="How to add an image from the same folder"/>
<h2> Dog: </h2>
<img src="./4.0 File Paths/dog.png" alt="How to add an image from the different folder"/>
<h2> Fish: </h2>
<img src="./4.0 File Paths/Folder1/fish.png" alt="How to add an image from the different folder"/>
<h2> Bird: </h2>
<img src="./4.0 File Paths/Folder1/Folder2/bird.png" alt="How to add an image from the different folder"/>
<br>
<br>
<br>
<br>
<br>
<hr>


<!-- Building Multi-Page Websites -->
<h1> Multi-Page Websites </h1>
<!-- add an image of yourself that links to the about page -->
<a href="./about.html"> <img src="./cat.png" width="300" height="250"/> </a> <br>
<!-- add a lin ot your contact me page here -->
<a href="./contact.html"> Contact Me </a>
<br>
<br>
<br>


<!-- The HTML Boilerplate -->
    <!-- a typical website's HTML code -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website Artsier</title>
</head>
<body>
    <h1>Hello World!</h1>
</body>
</html>
<br>
<br>


