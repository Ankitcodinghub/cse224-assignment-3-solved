# cse224-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CSE224 Assignment 3 Solved](https://www.ankitcodinghub.com/product/cse224-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95957&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE224 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this assignment, you’re going to create a bash script that will play High-Low against a user. Specifically:

<ul>
<li>the user will type the name of your script (“hl”) and hit ENTER</li>
<li>the program will print a welcome message, tell the user about playing high-low, and
tell them which keys to use during gameplay; then ask the user to think of a

number between 1 and 100 (inclusive), and to hit any key when they’re ready
</li>
<li>the user thinks of a number, and then hits any key</li>
<li>the program will make a guess and tell the user what the guess is.</li>
<li>if the program’s guess was correct, the user hits the ‘c’ key, and the game is over.
Tell the user how many guesses it took, thank the user for playing, and exit (alternatively, you may insult the user for picking such an easy number, describe how brilliant the program is, and so on) Otherwise:
</li>
<li>if the program’s guess was too high (large), the user hits the ‘h’ key</li>
<li>if the program’s guess was too low (small), the user hits the ‘l’ key</li>
<li>the program makes another guess, tells the user what the guess is, and the game
continues.

Additionally, if the user runs highlow with an argument, then the player can pick a number between 1 and whatever the argument is. for example, if they say

hl 1000

then the user may guess a number between 1 and 1000. If an argument is given, you

may assume it is a positive integer, and ignore any additional arguments.

DETAILS:
</li>
</ul>
<ul>
<li>This must be written as a bash script</li>
<li>you must comment your code, including in the beginning your name, class name,
date, and a description of what the program does. Also comment the code itself
</li>
<li>don’t require the user to hit ENTER after typing h l or c: your script should look for
a single keystroke and then continue
</li>
<li>We’ll go over the algorithm in class for playing high-low</li>
<li>your program should detect cheating. For example, if 51 is high and 50 is low, the
user must be cheating (or they made a mistake in answering). Detect this type of

situation, inform the user, and exit the game.
</li>
<li>name the script hl and push to a GITLab repo named “HL” by the due date.
BE SURE OF THE FOLLOWING:
</li>
</ul>
<ul>
<li>the user is picking a number, and the program is trying to guess it (not the other
way around)
</li>
<li>‘h’ means the program’s guess was too high, ‘l’ means too low. If the user is thinking
of the number 10 and the program guesses 50, that’s high (‘h’). If the program

guesses 2, that’s low (‘l’)
</li>
<li>the program begins by asking the user to think of a number, and having them hit
any key when they’ve got a number in mind. It then immediately begins playing the

game by making its first guess.
</li>
<li>If the user hits anything other than h, l or c, you should print a one-line message
reminding the user which keys they can use.
</li>
<li>Feel free to have other students test your game for you!</li>
</ul>
</div>
</div>
</div>
