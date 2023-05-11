
GEEKSFORGEEKS
How to Design Homepage like Facebook using HTML and CSS ?
HTML:  HTML stands for Hyper Text Markup Language. It is used to design web pages using a markup language. HTML is the combination of Hypertext and Markup language. Hypertext defines the link between the web pages. A markup language is used to define the text document within tag which defines the structure of web pages.

CSS: Cascading Style Sheets, fondly referred to as CSS, is a simply designed language intended to simplify the process of making web pages presentable. CSS allows you to apply styles to web pages. More importantly, CSS enables you to do this independent of the HTML that makes up each web page.

Below is the source code for construction of Facebook like Homepage: 

You can see the Github link to download the complete code of this article. 
 

HTML section: File name is homepage1.html
 

<!DOCTYPE html>
<html>
  
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content=
        "width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" 
        href="new.css" media="screen" />
</head>
  
<body>
    <div class=" header1">
        <div id="name" class="header1">
            OLD MASTER
        </div>
        <div id="searcharea" class="header1">
            <input placeholder="search here...." 
                type="text" id="searchbox" />
        </div>
        <div id="profilearea" class="header1">Profile</div>
        <div id="profilearea1" class="header1">|</div>
        <div id="profilearea2" class="header1">Home</div>
    </div>
    <div class="sidenav">
        <div class="bodyn">
            <div id="side1" class="bodyn">Profile</div>
            <div id="side2" class="bodyn">edit profile</div>
            <div id="side3" class="bodyn">News feed</div>
            <div id="side4" class="bodyn">Messages</div>
            <div id="side5" class="bodyn">Events</div>
            <div id="side6" class="bodyn">PAGES</div>
            <div id="side7" class="bodyn">Pages feed</div>
            <div id="side8" class="bodyn">Like pages</div>
            <div id="side9" class="bodyn">Create page</div>
            <div id="side10" class="bodyn">Create ad</div>
            <div id="side11" class="bodyn">GROUPS</div>
            <div id="side12" class="bodyn">New groups</div>
            <div id="side13" class="bodyn">Create group</div>
            <div id="side14" class="bodyn">APPS</div>
            <div id="side15" class="bodyn">Games</div>
            <div id="side16" class="bodyn">On this day</div>
            <div id="side17" class="bodyn">Games feed</div>
            <div id="side18" class="bodyn">FRIENDS</div>
            <div id="side19" class="bodyn">Close friends</div>
            <div id="side20" class="bodyn">Family</div>
            <div id="side21" class="bodyn">INTERESTS</div>
            <div id="side22" class="bodyn">Pages and public</div>
            <div id="side23" class="bodyn">EVENTS</div>
            <div id="side24" class="bodyn">Create event</div>
        </div>
    </div>
    <div class="post00"></div>
    <div class="post10"></div>
  
    <div class="header0001"></div>
    <div class="sideboxxx"></div>
    <div class="sideboxxxx2"></div>
    <div class="post">
        <div id="column-1" class="post">
            update status | add photos/
            videos | create photo album
            <hr><br><br><br><br><br><br>
            <hr>
        </div>
        <div id="postpos" class="post">
            <input type="submit" id="buttonpost" value="post" />
        </div>
        <div id="postboxpos" class="post">
            <textarea placeholder="What's in your mind" 
                id="postbox">
            </textarea>
        </div>
    </div>
    <div class="post1">
        <img src="mini1.png" alt="image is here" 
            height="40" width="40" /><br>
        <img src="mini......png" alt="image is here" 
            height="400" width="575" /><br><br>
        <p6>Like Comment Share</p6><br>
        <hr>
        <p1>Amit Deb</p1>
        <p2> and</p2>
        <p1> 5 others</p1>
        <p2> like this</p2>
        <div id="post2text" class="post1">
            <p3>Rani Mukharji </p3>
            <p2>with </p2>
            <p1> Arup Pegu</p1>
            <p2> and</p2>
            <p1> 15 others.</p1><br>
            <p4>4 hrs.</p4>
        </div>
        <div id="commentprof2" class="post1">
            <img src="mini1.png" alt="image is here" 
                height="25" width="25" id="profpic" />
        </div>
        <div id="commentboxpos2" class="post1">
            <input type="text" placeholder="comment" 
                id="commentbox" />
        </div>
    </div>
    <div class="sidebox">
        <div id="sidebox1" class="sidebox">
            <div id="sideboxx1">YOUR PAGES</div>
            <hr><br><br>See all
            <hr>
            <div id="sideboxx2">
                This Week
            </div><br><br>See more
            <hr>
            <div id="sideboxx3">
                Recent Posts
            </div><br><br>See more
            <hr>
            <div id="sideboxx4">
                You haven't posted in this days
            </div><br><br><br>See all
        </div>
  
        <div id="post1pos" class="sidebox">
            <input type="submit" id="buttonpost1" 
                value="write a post" />
        </div>
    </div>
    <div class="sideboxxx2">
        <div id="sidebox2" class="sideboxxx2">
            <hr>
            <div id="sideboxx21">Trending</div>
            <br><br><br>See more
            <hr>
            <div id="sideboxx22">
                Suggested Pages
            </div><br><br><br>See all
            <hr>
            <div id="sideboxx23">
                People you may know
            </div><br><br><br><br>See all
        </div>
    </div>
</body>
  
</html>
 

 

CSS section: File name is new.css

Do
