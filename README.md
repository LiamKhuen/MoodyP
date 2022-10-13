# MoodyP

Created by Eduardo Perez && Liam Khuen

[(PDF Documentation)](https://github.com/LiamKhuen/MoodyP/files/9769739/MoodyP-Doc.pdf)



<h2>Why moodyP?</h2>

<p>
    Welcome! At the <i>MOODY FOUNDATION</i><sup>©</sup>, we believe that sometimes coding can be a little <i>too</i> simple (easy) 
    sometimes. What happened to the days of unreliable punch cards and those little math machines that broke all the f****** time?
</p>


<h2>1.1.1 WAIT SO WHAT IS moodyP...?</h2>

<p>
    <i>moodyP</i> is a very-angsty programming language (some people in industry call it a “VAP-language”).
    A nice way to think of <i>moodyP</i> is to liken it to a nice broth-y soup:
</p>

<p align=center style='text-align:center'>“Let me not be accounted for the taste of my soupiness,</p>
<p align=center style='text-align:center'>but for the appearance of my broth</p>
<p align=center style='text-align:center'>and whether or not it will give me</p>
<p align=center style='text-align:center'>food poisoning</p>
<p align=center style='text-align:center'>-unknown</p>

<p>
    Oh, yes, the old <i>soup</i> metaphor! <i>moodyP</i> essentially takes all the power and graft of other popular scripting 
    languages and very tightly packages their strength (strengths?) into a delicious bouillon cube of gooey goodness that, much 
    like a person, may or may not obey your every command. See? Cool!
</p>

<p>
    More on this later
</p>

    
<h2>1.1.2 THIS IS ANNOYING AND I WONT LIKE LEAR–</h2>

<p>
    WOAH WOAH there, cowboy! Why, you don’t even know any of the syntax or other specially scrumptious aspects of the MOODY FOUNDATION’s 
    pride and joy of a language? Just settle on down and maybe have a smoke. Or not. We at the <i>MOODY FOUNDATION</i><sup>©</sup>, like, don’t really care 
    what you do with your body, man. Just chill out and ride the wave &#128520;
</p>


<h2>1.1.3 THE MEAT OF THE SOUP</h2>

<p align=center>
  <img src='https://user-images.githubusercontent.com/19754429/195481410-f08e6922-3a81-464d-9b55-2a5a6a014221.png' />
</p>
  
<p>
    moody() is a “class”. In the traditional world of computing, a class is an abstract concept (that miners have been 
    digging at for nearly 170 years whilst subsequently trying to find a more suitable name for this darn idea) that defines 
    a structure which represents a container of <i>things</i>. What kind of things? Well:
</p>

<ul>
    <li><i>Var(s)</i> which store data</li>
    <li><i>Function(s)/procedure(s)</i> which do things with that data</li>
    <li><i>Other stuff that we can talk about later since the two previous things are mostly used anyway</i></li>
</ul>

<p>
    Nah, just kiddin’. Classes actually can do quite a lot. For example…
</p>


<h2>1.1.4 FOR EXAMPLE</h2>

<p>
    Let’s say you’ve got a nice, small dog. Now, this dog never growls, it never bites, but sometimes it likes to walk and eat.
</p>

<p align=center>
  <img src='https://user-images.githubusercontent.com/19754429/195483064-2875edd9-2490-4a3e-8c73-ebeb8f247daf.png' />
</p>

<p>
    Since this dog sometimes likes to eat a bit, it will have a tiny little program in its avocado-sized brain that tells it to do so:
</p>

<p align=center>
  <img src='https://user-images.githubusercontent.com/19754429/195483183-e1411844-9249-421e-8a77-d168ae0767b9.png' />
</p>

<p>
    Nice! Now you’ve got a normal dog. Yep, just a normal dog with a brain that can only tell it to do one thing
</p>

<p>
    Cool, so what we just created was something called a <i>subroutine</i>. Spell it with me now: S-U-…eh, sounds like you’ve got it. 
</p>


<h2>1.1.5 WAIT WHAT’S THAT ONE THING BEFORE THE “EAT” PART</h2>

<p>
    Looks like we’ve got an observer over here! Yes, right before the <b>name</b> of a Function/Subroutine/Method (yes, these are all 
    names used interchangeably and yes they all mean the same thing) you must describe what the hell it is first.
</p>


<h2>1.1.6 COOL, I KNOW EVERYTHING ABOUT MOODYP!</h2>

<p>
    Lol, no. Not so fast. You have to know about a bunch of other stuff too. Stuff like <i>Functions</i>
    which are similar to <i>Procedures</i> except that they are supposed to bring something back after doing
    stuff.
</p>

<p align=center>
  <img src='https://user-images.githubusercontent.com/19754429/195485477-cd56f6f8-70d8-4339-8b48-a636d941bc0d.png' />
</p>

<p>
    What’s that you say? <i>params? Return_Motion?</i> Alas, this is where the fun begins! You see, <i>moodyP</i> allows you, the
    soup-maker to create <i>Procedures</i> or <i>Functions</i> that take in certain inputs. Let’s say your dog eats only the finest 
    rubbery boots (a prized item in the economy of <i>moodyP-landia</i>).
</p>

<p align=center>
  <img src='https://user-images.githubusercontent.com/19754429/195488689-8cf881b1-d537-4acb-b874-9ecc713b01bd.png' />
</p>

<p>
    <b>If</b> all goes well within the little <i>Function</i> we wrote, the action of your dog eating <i>food</i>
    (a <i>“RubberBoot”</i> type of thing) shall yield you something called <i>Return_Motion</i> whatever that does.
</p>


<h2>1.1.7 SHOOT NOW WE GOTTA WORRY ABOUT FLOW</h2>

<p>
    Why yes, we are dealing with logic, after all.
</p>

<p align=center>
  <img src='https://user-images.githubusercontent.com/19754429/195505834-eebada89-a255-49c8-80a6-7c81052548b1.png' />
</p>

<p>
    <b>else</b> sets an additional check for the data coming into the <i>Function</i>. Keep in mind, that you MUST use
    <b>elsif</b> before using an <b>else</b> check if you want to make more than two conditional tests for the data coming 
    into the function. In this case, if the <i>Eat Function</i> does not receive the necessary input after a third test, 
    the <b><i>Dog</i></b> will perform the actions described in <b><i>Bye</i></b>.
</p>

<h2>1.1.8 MATH, TOO</h2>

<p>
    <i>moodyP</i> loves math. As a matter of fact, most programming languages do. Everyone knows
    (we hope!) how to add, subtract, multiply, and divide. Here’s how you do it in <i>our</i> language:
</p>

<p align=center>
  <img src='https://user-images.githubusercontent.com/19754429/195506036-22a892f1-3403-4906-bb52-29906dc6258f.png' />
</p>


<h2>1.1.9 PEMDAS PEMDAS PEMDAS PEMDAS</h2>

<p>
    No, <i>moodyP</i> may not have any broads in Atlanta, but it sure does have support for parenthetical statements!
</p>

<p align=center>
  <img src='https://user-images.githubusercontent.com/19754429/195506193-53ce6252-782d-4ebe-90ae-171159692095.png' />
</p>


<h2>1.2.0 ERRORS AND ERRORS GALORE</h2>

<p>
    Let’s get this out of the way right now: you will get a ton of errors while you program using <i>moodyP</i>. You will try 
    and try and pray and pray but the truth is your code will not or ever work. Well, sometimes it will. Mostly it won't. 
</p>

<p>
    <i>moodyP</i> handles errors with simplicity and finesse. That is, it has a very <i>rudimentary</i> error
    reporting system built-in. “Well, hot dog!”, you scream in excitement. Let’s say you try to be a bad little 
    programmer and try to utilize an <i>INVALID</i> character in your code. Well, <i>moodyP</i>, being moody and 
    all, will scream and kick and yell internally but will tell you this:
</p>

<p align=center>
  <img src='https://user-images.githubusercontent.com/19754429/195506302-0cf97a49-b8a2-4896-b7a0-8bde9cc102e8.png' />
</p>

<p>
    That line is that error on? Who knows! You see, half the fun of programming is learning how to suffer. 
</p>


<h2>1.2.1 THE CRUX OF THE LANGUAGE</h2>

<p>
    Okay, so remember when we spoke earlier about wanting to come back to a time in which computers were unpredictable?
    Well, that’s the whole point of <i>moodyP</i>. In fact, the <i>interpreter</i> (basically, the thing that runs the 
    show in the background; you don't really have to know how this stuff works) only runs when it <b>feels</b> like running.
</p>


<h2>1.2.2 MOOD LEVELS</h2>

<p>
    Much as in the religion of <i>Scientology</i>, the <i>moodyP</i> programming language has certain layers of status. 
    At runtime (a fancy word for when “stuff happens”), the interpreter decides upon a specific mood from a set. Just like 
    a petulant child, the program will either happily scurry off with your code or curse your name under its breath for all eternity.
</p>

<p align=center>
  <img src='https://user-images.githubusercontent.com/19754429/195506393-37326247-eadc-43ff-a46e-08071d7fde86.png' />
</p>


<h2>1.2.3 SO, WHAT’S NEXT?</h2>

<p>
    Wew, wasn’t that just a bundle of fun? We here at the <i>MOODY FOUNDATION</i><sup>©</sup> would like to ensure that the BUCK DOES NOT STOP HERE. 
    There will be an attempt made to ensure that the greatest in operations can be made with this new type of VAP-langauge in the future, 
    so stay tuned and gather your closest friends. You’re gonna need ‘em.
</p>


<h2>1.2.4 ACKNOWLEDGMENTS AND OTHER COOL STUFF</h2>

<p>
    The totally-not-made-up <i>MOODY FOUNDATION</i><sup>©</sup> would like to thank Professor Bilal Shibaro for being 
    so cool so as to allow us to create such a monster. No, he did not force us to make this. 
</p>

<p align=center>
    listOfKeywords:
</p>

<p align=center>
  <img src='https://user-images.githubusercontent.com/19754429/195506474-ed407201-50d4-4d49-adcc-2a9b481af323.png' />
</p>

<p align=center>
    <sub>
        LEGAL: Please keep in mind that this is a school project and that if it seems professional in any way 
        shape or form it was done so coincidentally and that none of the above should be taken seriously what soever.
    </sub>
</p>
