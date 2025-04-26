# comp9044-lab-8-solved
**TO GET THIS SOLUTION VISIT:** [COMP9044 Lab 8 Solved](https://www.ankitcodinghub.com/product/comp9044-lab-8-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;86731&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP9044 Lab 8 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
Before the lab you should re-read the relevant lecture slides and their accompanying examples.

Create a new directory for this lab called lab08, change to this directory, and fetch the provided code for this week by running these commands:

$ <strong>mkdir lab08</strong>

$ <strong>cd lab08</strong>

$ <strong>2041 fetch lab08</strong>

Or, if you’re not working on CSE, you can download the provided code as a <a href="https://cgi.cse.unsw.edu.au/~cs2041/20T2/lab/08/provided.zip">zip</a> <a href="https://cgi.cse.unsw.edu.au/~cs2041/20T2/lab/08/provided.zip">file</a> or a <a href="https://cgi.cse.unsw.edu.au/~cs2041/20T2/lab/08/provided.tar">tar</a> <a href="https://cgi.cse.unsw.edu.au/~cs2041/20T2/lab/08/provided.tar">file</a>.

Write a Shell script courses.sh which given a course prefix, e.g. COMP, prints all the course code and name for all UNSW shell_courses with that prefix offered this year on the Kensington Campus. For example:

$ <strong>./courses.sh VISN</strong>

VISN1101 Seeing the World: Perspectives from Vision Science VISN1111 Geometrical and Physical Optics

VISN1221 Visual Optics

VISN2111 Ocular Anatomy and Physiology

VISN2211 Organisation and Function of the Visual System

VISN3111 Development and Aging of the Visual System

VISN4016 Vision Science Honours

<strong>./courses.sh COMP|tail</strong>

COMP9511 Human Computer Interaction

COMP9517 Computer Vision

COMP9596 Research Project

COMP9801 Extended Design and Analysis of Algorithms COMP9814 Extended Artificial Intelligence

COMP9844 Extended Neural Networks and Deep Learning

COMP9900 Information Technology Project

COMP9991 Research Project A

COMP9992 Research Project B

COMP9993 Research Project C

Your program must be POSIX compatible Shell. You can assume anything that works with the version of /bin/dash on CSE systems is POSIX compatible.

You are not permitted to use other languages such as Perl, Python, C, …

You are permitted to use programs such as egrep, sed, sort, uniq.

Hints:

The information you need for course code prefix COMP can be found in this web page:

<a href="http://www.timetable.unsw.edu.au/current/COMPKENS.html">http://www.timetable.unsw.edu.au/current/COMPKENS.htm</a><a href="http://www.timetable.unsw.edu.au/current/COMPKENS.html"><sub>l</sub></a><a href="http://www.timetable.unsw.edu.au/current/COMPKENS.html">.</a> You can assume this is the case for all prefixes.

The command curl will download a URL and print it to standard output.

<table width="961">
<tbody>
<tr>
<td width="961">$ <strong>curl –location –silent http://www.timetable.unsw.edu.au/current/COMPKENS.html|head</strong>

&lt;title&gt;Class Search by Teaching Period&lt;/title&gt;

&lt;link rel=”stylesheet” type=”text/css” href=”../layout/2020/myunsw.css”&gt; &lt;head&gt;

&lt;meta http-equiv=”Content-Type” content=”text/html; charset=iso-8859-1″&gt;

&nbsp;

&lt;table width=”100%” cellspacing=”0″ cellpadding=”0″&gt;

&lt;form name=”googleForm” method=”GET” action=”http://www.google.com/u/theuniversityofnewsouthwales” target=”_blank”&gt;

&lt;tr&gt;

&lt;td width=”30%” style=”height:120px; border-bottom:10px solid #FFCC00; background-color:#fff;”&gt;&lt;a href=”http://www.unsw.edu.au” target=”_blank”&gt;&lt;img border=”0″ src=”/images-timetable/banner2020.jpg” alt=”The

University of New South Wales” width=”836″ height=”179″ style=”float:left; margin-left:20px; margin-top:25px;”&gt;

&lt;/a&gt;&lt;/td&gt;

&lt;td width=”70%” style=”height:120px; border-bottom:10px solid #FFCC00; background-color:#fff; vertical-align:bottom; ” align=”right”&gt;

$
</td>
</tr>
</tbody>
</table>
In a script it is best run as curl –silent so it doesn’t print extra information on standard error.

The –location is required so curl will follow a HTTP redirect from the URL.

The wget -q -O- could also be used.

You may find uniq’s -w option useful when removing duplicate courses.

When you think your program is working, you can use autotest to run some simple automated tests:

$ <strong>2041 autotest shell_courses</strong>

When you are finished working on this exercise, you must submit your work by running give:

$ <strong>give cs2041 lab08_shell_courses courses.sh</strong>

before Tuesday 28 July 18 00 to obtain the marks for this lab exercise.

Write a Perl script courses.pl which given a course prefix, e.g. COMP, prints all the course code and name for all UNSW courses with that prefix offered this year on the Kensington Campus. For example:

<strong>./courses.pl VISN</strong>

VISN1101 Seeing the World: Perspectives from Vision Science VISN1111 Geometrical and Physical Optics

VISN1221 Visual Optics

VISN2111 Ocular Anatomy and Physiology

VISN2211 Organisation and Function of the Visual System

VISN3111 Development and Aging of the Visual System

VISN4016 Vision Science Honours

<strong>./courses.pl COMP|tail</strong>

COMP9511 Human Computer Interaction

COMP9517 Computer Vision

COMP9596 Research Project

COMP9801 Extended Design and Analysis of Algorithms COMP9814 Extended Artificial Intelligence

COMP9844 Extended Neural Networks and Deep Learning

COMP9900 Information Technology Project

COMP9991 Research Project A

COMP9992 Research Project B

COMP9993 Research Project C

Your answer must be Perl only.

You may not run external programs, e.g. via system or backquotes.

Hints:

The information you need for course code prefix COMP can be found in this web page: <a href="http://www.timetable.unsw.edu.au/current/COMPKENS.html">http://www.timetable.unsw.edu.au/current/COMPKENS.htm</a><a href="http://www.timetable.unsw.edu.au/current/COMPKENS.html"><sub>l</sub></a><a href="http://www.timetable.unsw.edu.au/current/COMPKENS.html">.</a> You can assume this is the case for all prefixes.

The Perl module LWP::Simple provides a very simple way to get a web page, e.g:

You will need to remove duplicate entries for some courses.

When you think your program is working, you can use autotest to run some simple automated tests:

$ <strong>2041 autotest perl_courses</strong>

When you are finished working on this exercise, you must submit your work by running give:

$ <strong>give cs2041 lab08_perl_courses courses.pl</strong>

before Tuesday 28 July 18 00 to obtain the marks for this lab exercise.

Write a Perl script timetable.pl which given course codes prints an ASCII timetable of their lecture times for this year in the format shown in the example below.

<table width="961">
<tbody>
<tr>
<td width="961">$ <strong>./timetable.pl COMP2041 MATH2400 MATH2859</strong>

Mon&nbsp;&nbsp; Tue&nbsp;&nbsp; Wed&nbsp;&nbsp; Thu&nbsp;&nbsp; Fri

09:00&nbsp;&nbsp;&nbsp;&nbsp; L&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

10:00&nbsp;&nbsp;&nbsp;&nbsp; L&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

11:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L&nbsp;&nbsp;&nbsp;&nbsp; L

12:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L 13:00

14:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

15:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

16:00

17:00

18:00

19:00

20:00

$ <strong>./timetable.pl COMP9044 COMP6771 GSOE9820</strong>

Mon&nbsp;&nbsp; Tue&nbsp;&nbsp; Wed&nbsp;&nbsp; Thu&nbsp;&nbsp; Fri 09:00

10:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

11:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

12:00

13:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

14:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L&nbsp;&nbsp;&nbsp;&nbsp; L

15:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

16:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

17:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

18:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

19:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

20:00
</td>
</tr>
</tbody>
</table>
You can assume that a course’s lecture times will be found in a web page equivalent to: <a href="http://timetable.unsw.edu.au/current/COMP2041.html">http</a><a href="http://timetable.unsw.edu.au/current/COMP2041.html">://</a><a href="http://timetable.unsw.edu.au/current/COMP2041.html">timetable</a><a href="http://timetable.unsw.edu.au/current/COMP2041.html">.</a><a href="http://timetable.unsw.edu.au/current/COMP2041.html">unsw</a><a href="http://timetable.unsw.edu.au/current/COMP2041.html">.</a><a href="http://timetable.unsw.edu.au/current/COMP2041.html">edu</a><a href="http://timetable.unsw.edu.au/current/COMP2041.html">.</a><a href="http://timetable.unsw.edu.au/current/COMP2041.html">au</a><a href="http://timetable.unsw.edu.au/current/COMP2041.html">/</a><a href="http://timetable.unsw.edu.au/current/COMP2041.html">current</a><a href="http://timetable.unsw.edu.au/current/COMP2041.html">/</a><a href="http://timetable.unsw.edu.au/current/COMP2041.html">MATH</a><a href="http://timetable.unsw.edu.au/current/COMP2041.html">1131.</a><a href="http://timetable.unsw.edu.au/current/COMP2041.html">html</a>.

Hint: if you find it difficult to use a regex to extract the line containing the lecture description, split the page into line match a previous line, then skip a certain number of lines.

You assume there are no lectures on weekends, and no lectures before 09 00 or after 21 00 Your answer must be Perl only.

You may not run external programs, e.g. via system or backquotes.

If a course is running in multiple terms print all the terms.

If th&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; lti l&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; t&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; i t ll th&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; t&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; f&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; l

If there are multiple streams print all the streams, for example:

$ <strong>./timetable.pl COMP1511</strong>

Mon&nbsp;&nbsp; Tue&nbsp;&nbsp; Wed&nbsp;&nbsp; Thu&nbsp;&nbsp; Fri

09:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

10:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

11:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

12:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

13:00

14:00

15:00

16:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

17:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

18:00

19:00

20:00

$ <strong>./timetable.pl MATH1131</strong>

Mon&nbsp;&nbsp; Tue&nbsp;&nbsp; Wed&nbsp;&nbsp; Thu&nbsp;&nbsp; Fri

09:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

10:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

11:00

12:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

13:00&nbsp;&nbsp;&nbsp;&nbsp; L&nbsp;&nbsp;&nbsp;&nbsp; L&nbsp;&nbsp;&nbsp;&nbsp; L

14:00&nbsp;&nbsp;&nbsp;&nbsp; L&nbsp;&nbsp;&nbsp;&nbsp; L&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L&nbsp;&nbsp;&nbsp;&nbsp; L

15:00&nbsp;&nbsp;&nbsp;&nbsp; L&nbsp;&nbsp;&nbsp;&nbsp; L&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L&nbsp;&nbsp;&nbsp;&nbsp; L

16:00&nbsp;&nbsp;&nbsp;&nbsp; L&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L&nbsp;&nbsp;&nbsp;&nbsp; L 17:00&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; L

18:00

19:00

20:00

Note the correct output in all the above examples will change when next term’s lectures are added to the timetable.

When you think your program is working, you can use autotest to run some simple automated tests:

$ <strong>2041 autotest timetable</strong>

When you are finished working on this exercise, you must submit your work by running give:

$ <strong>give cs2041 lab08_timetable timetable.pl</strong>

before Tuesday 28 July 18 00 to obtain the marks for this lab exercise.

When you are finished each exercises make sure you submit your work by running give.

You can run give multiple times. Only your last submission will be marked.

Don’t submit any exercises you haven’t attempted.

If you are working at home, you may find it more convenient to upload your work via <a href="https://cgi.cse.unsw.edu.au/~give/Student/give.php">g</a><a href="https://cgi.cse.unsw.edu.au/~give/Student/give.php">ive</a><a href="https://cgi.cse.unsw.edu.au/~give/Student/give.php">‘</a><a href="https://cgi.cse.unsw.edu.au/~give/Student/give.php">s</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/give.php">web</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/give.php">interface</a><a href="https://cgi.cse.unsw.edu.au/~give/Student/give.php">.</a>

Remember you have until Tuesday 28 July 18 00 to submit your work.

You cannot obtain marks by e-mailing your code to tutors or lecturers.

You check the files you have submitted <a href="https://cgi.cse.unsw.edu.au/~cs2041/20T2/student/">here</a>.

Automarking will be run by the lecturer several days after the submission deadline, using test cases different to those autotest runs for you. (Hint: do your own testing as well as running autotest.)

<a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">After</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">automarking</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">is</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">run</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">by</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">the</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">lecturer</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">you</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">can</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">view</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">y</a><a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">our</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">results</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">here</a><a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">.</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">The</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">resulting</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">mark</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">will</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">also</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">be</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">available</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">via</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">g</a><a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">ive</a><a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">‘</a><a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">s</a> <a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">web interface</a><a href="https://cgi.cse.unsw.edu.au/~give/Student/sturec.php">.</a>
