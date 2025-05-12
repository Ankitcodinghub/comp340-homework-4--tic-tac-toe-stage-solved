# comp340-homework-4--tic-tac-toe-stage-solved
**TO GET THIS SOLUTION VISIT:** [COMP340 Homework 4 -Tic-Tac-Toe Stage Solved](https://www.ankitcodinghub.com/product/comp340-homework-4-tic-tac-toe-stage-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91123&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP340 Homework 4&nbsp;-Tic-Tac-Toe Stage Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
Part 0. Setup Programming Environment

<ol>
<li>Download the required file (tictactoe.rkt) from Blackboard and save it under any folder you want.</li>
<li>In DrRacket, open tictactoe.rkt.</li>
<li>Inside tictactoe.rkt, you will see a basic structure of a tic-tac-toe program with some pre- defined functions. Here are short descriptions of the pre-defined functions.
whitebox: it draws a white box. transpbox: it draws a transparent box.

pensetup: it set up a pen with desired color and width. This function is used to set up the color

and width of the line. You can input the color and width like (pensetup “red” 3) and (pensetup “black” 5)
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 1 of 5

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Part 1. O mark

In this part, you will define a function omark that draws O in the result window.

<ol>
<li>Define a function singlecircle that draws a circle using circle function. It needs to draw
a circle that satisfies the below features.

radius: 20 color: red line’s width: 3

To draw a circle satisfying the above features, you can use a circle function like (circle 20 “outline” (pensetup “red” 3))
</li>
<li>Define omark function as shown below where it overlays singlecircle on top of whitebox using overlay function.
(define (omark) (overlay (singlecircle)(whitebox)))
</li>
<li>When you call (omark) (which means that you write (omark) in the program and run it), it
should draw a single red circle in the result window as shown below.
</li>
</ol>
Part 2. X mark

In this part, you will define a function xmark that draws X in the result window.

<ol>
<li>Define a function singleline that draws a single line of X mark using a line function. It
needs to draw a line that satisfies the below features.

x of end-point: 30 y of end-point: 30 color: blue

line’s width: 3

You can set up a color and a width of a line using pensetup function like we did for a circle in step 1 of Part 1. pensetup function expression will be the last argument of line function. (line function follows a syntax (line &lt;x&gt; &lt;y&gt; &lt;pen or color&gt;).)
</li>
<li>Define a function flipsingleline that flips singleline. To flip a line image, you can use either flip-horizontal or flip-vertical function.</li>
<li>Define a function xlines that overlays singleline on top of flipsingleline. To overlay one image on top of another image, you can use overlay function as shown in step 2 of Part 1.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
Page 2 of 5

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ol start="4">
<li>Define xmark function as shown below where it overlays xlines on top of whitebox. (define (xmark) (overlay (xlines)(whitebox)))</li>
<li>When you call (xmark), it should draw a single blue X in the result window as shown below.</li>
</ol>
Part 3. Whole board with Os and Xs

In this part, you will define a function wholeboard which arranges Os and Xs vertically and horizontally as shown in the final result on the first page of this document.

If you want to arrange marks horizontally, you can use beside function. If you want to arrange marks vertically, you can use above function.

For example:

(beside (omark) (omark) (omark)) will give the below result.

(above (omark) (omark) (omark)) will give the below result.

</div>
</div>
<div class="layoutArea">
<div class="column">
You need to figure out how to define wholeboard function using beside and above functions so that you have the below result when you call (wholeboard).

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 3 of 5

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Part 4. Grid

In this part, you will define a function grid to draw a grid image.

<ol>
<li>Define a function vline that draws a single line using line function satisfying the below
requirements.

x of end-point: 0

y of end-point: 200 color: black

line’s width: 5
</li>
<li>Define a function vertline that overlays vline on top of transpbox. Since vertline will be overlayed on top of wholeboard, if you use whitebox instead of transpbox, some part of wholeboard will not be visible later.</li>
<li>Define a function vertgrid that arranges two vertlines horizontally. You can use beside function. By calling (vertgrid), you will have the below result.</li>
<li>Define a function horigrid that arranges two horizontal lines vertically. Instead of drawing two horizontal lines, you can simply rotate vertgrid by 90 degrees. (You can use (rotate 90 &lt;image&gt;) to rotate given &lt;image&gt; by 90 degrees.)</li>
<li>Define a function grid that overlays vertgrid on top of horigrid. By calling (grid), you will have the below result.</li>
</ol>
Part 5. Tic-tac-toe stage

<ol>
<li>Define a function tictactoe that overlays grid on top of wholeboard like the below.
(define (tictactoe) (overlay (grid) (wholeboard)))
</li>
<li>When you call (tictactoe), you will have the final result.</li>
<li>Call (save-image (tictactoe) “tictactoe.png”). Then you will have
‘tictactoe.png’ file in the folder where you have the tic-tac-toe program. You need to submit the png file with the Racket source code (tictactoe.rkt) on Blackboard.
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
Page 4 of 5

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Bonus Question. Modify the tic-tac-toe program in a way that you can have the below result which looks like a ‘real’ tic-tac-toe stage. You still need to submit a png file of this bonus question to get a bonus point (2 pts).

Submission Guideline

<ol>
<li>Upload tictactoe.rkt and tictactoe.png on Blackboard.</li>
<li>After you submit them, DOUBLE-CHECK whether you’ve submitted the correct files on
Blackboard.
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
Page 5 of 5

</div>
</div>
</div>
