# 100 Days Of Code (2019) - Log

*Starting a new repo for 2019 so that changes will appear on my activity!*

## Day 1: January 27, 2019

**Today's Progress:** Working on the [freeCodeCamp](https://freeCodeCamp.org)
Data Visualisation section; ran through D3 lessons.

## Day 2: January 28, 2019

**Today's Progress:** Working on the [freeCodeCamp](https://freeCodeCamp.org)
Front End section; ran through React lessons.

## Day 3: January 29, 2019

**Today's Progress:** Started working through the introduction from Programming Python,
using Pythonista on iPad.

**Thoughts:** Surprised by how well Pythonista adapts - hadn't been sure that there would
be much file-system access (sure that it's sand-boxed, but even so works better than
I had expected).

## Day 4: January 30, 2019

**Today's Progress:** Working on the [freeCodeCamp](https://freeCodeCamp.org)
Font End section; ran through Redux lessons, did three of the Rosetta Code challenges.

Continued working through Programming Python examples on Pythonista.

## Day 5: January 31, 2019

**Today's Progress:** Working on the [freeCodeCamp](https://freeCodeCamp.org)
Responsive Web Design challenges, finished the new Portfolio.

**Thoughts:** Have been putting this off because of the issues over images for the Pens that are completed, but think I've finally got an approach sorted <sup>[1](#myfootnote1)</sup>. 

**Link to work:** [Portfolio](https://codepen.io/domwakeling/full/pOYeLy)

## Day 6: February 1, 2019

**Today's Progress:** Working on the [freeCodeCamp](https://freeCodeCamp.org)
Front End section; continued Redux.

## Day 7: February 2, 2019

**Today's Progress:** Working on the [freeCodeCamp](https://freeCodeCamp.org)
Front End section; finished Redux, worked through Redux/React.

Dived into the first Front End project, Quote Machine. Previously completed
this on the old syllabus, but started again and wrote in React. Used the same 
API, but used <code>fetch()</code> rather than <code>jQuery.ajax()</code>.

**Thoughts:** Had to work out how to use a readable stream from fetch to get
a JSON object, and work out how to convert character entities to Unicode
entities so that they would display properly in React.

**Link to work:** [Quote Machine](https://codepen.io/domwakeling/full/qgmpGw)

## Day 8: February 3, 2019

**Today's Progress:** Worked on [freeCodeCamp](https://freeCodeCamp.org)
Markdown Previewer as part of the Front End certificate. Previously completed
this challenge under the old syllabus, but re-wrote from scratch. Used Redux
to store a common state and pass information between the two containers
(first time I've written something in Redux for myself).

Also started working on the next project, Drum Machine, which is new. Got a
working machine, although had some problems with hosting audio (trying to use
Google Drive as a host for resources, and it hasn't worked very well for audio)
so ended up using some sound samples that are used in the example project,
which I'm not delighted about. Also failing two of the tests, which *may* be
a latency issue, but I'm getting error messages about an exception being
raised from a Promise so have to look at that again.

**Thoughts:** Hit some problems with Redux, hadn't appreciated that (for
certain parts of Redux/React) you need to have written an element/method
before calling it. Had me stumped for half an hour whilst I worked through
issues, not helped because I was making mistakes in the Redux code since it 
was my first attempt!

Need to investigate a better way to host resources - I've been using Google
Drive and a hack courtesy of [gdurl.com](https://gdurl.com) to be able to make
images accessible, but proved today that this doesn't scale. Hosts for simple
domain websites aren't much use either, so need to have a look at something
like AWS and see whether there's a *"nearly-free"* tier.

**Link to work:** [Markdown Previewer](https://codepen.io/domwakeling/full/RvVExz) :
[Drum Machine](https://codepen.io/domwakeling/full/bzRNjp)

## Day 9: February 4, 2019

**Today's Progress:** Implementing a GCSE-level Python challenge using
Pythonista on iPad.

**Thoughts:** Had hoped that there would be an interface in Pythonista
to access files exposed through the Files app. There **is** an ability
to do so at the app level, but doesn't appear to be an interface at
script level ... so you can open (and presumably copy) external files
in the app's "finder" but not call them inside a Python script. Guess
you'll be able to copy files into the app's sandbox though so that will
be good enough.

## Day 10: February 5, 2019

**Today's Progress:** Finished implementing the Python challenge in 
Pythonista using console as interface. Started implementing a graphical
interface using Pythonista's *'ui'* module.

## Day 11: February 6, 2019

**Today's Progress:** Continued working on adding a UI to Python challenge.
Splitting some of the code (particularly parts of the UI) into separate
files using classes to encapsulate logic and simplify/improve legibility of
the actual app code.

## Day 12: February 7, 2019

**Today's Progress:** Still working on the UI version of the Python
challenge. Remembered how to import from sub-folders to keep the working
folder tidier! Also refactored some of the code from the console-interface
version so that the UI version is simpler.

## Day 13: February 8, 2019

**Today's Progress:** Finally finished the UI version of the Python challenge..
On to something fresh tomorrow ...

## Day 14: February 9, 2019

**Today's Progress:** Back to the [freeCodeCamp](https:/freeCodeCamp.org)
Drum Machine project; fixed the error that was causing it to fail tests (a
promise was being interrupted when the test suite ran, solved by calling my
playAudio() method direct when a click was registered, and binding that method
to the keypad.

Moved on to the Calculator project (definitely built this one before!) - have
decided to re-implement in React from scratch ...

Also watching videos from Code Realm on deploying a project, including an 
integrated CI/CD approach.

**Link to Work:** [Drum Machine](https://codepen.io/domwakeling/full/bzRNjp)

## Day 15: February 10, 2019

**Today's Progress:** Finished working on the Calculator project (I've done this
before in multiple languages, and every time it's surprising how complicated it is
to implement something that we take for granted).

Updated Bowles website with some content and style tweaks.

Working through the [freeCodeCamp](http://freecodecamp.org) npm and Node/Express
curriculum.

**Link to Work:** [Calculator](https://codepen.io/domwakeling/full/qgxgbq)

## Day 16: February 11, 2019

**Today's Progress":** Working on Pomodoro project.

## Day 17: February 12, 2019

**Today's Progress:** Completed Pomodoro project (and the Front End certificate).
Started and completed Bar Chart project (using D3) for the Data Visualisation
Certificate.

**Link to Works:** [Pomodoro Timer](https://codepen.io/domwakeling/full/xMjZLM) :
[Bar Chart Visualisation](https://codepen.io/domwakeling/full/VgdeWN)

## Day 18: February 13, 2019

**Today's Progress:** Experimenting with [Scriptable](https://scriptable.app),
working on [CodeWars](https://www.codewars.com) challenges, and watching first
part of a [freeCodeCamp](https://freeCodeCamp.org) video series on Node.

## Day 19: February 14, 2019

**Today's Progress:** Working on [CodeWars](https://www.codewars.com) challenges.

## Day 20: February 15, 2019

**Today's Progress:** Working on [CodeWars](https://www.codewars.com) challenges.

## Day 21: February 16, 2019

**Today's Progress:** Working on [CodeWars](https://www.codewars.com) challenges.
Reading about how to write Google Chrome extensions. Working through
[freeCodeCamp](https://freecodecamp.org) QA/Testing curriculum.

## Day 22: February 17, 2019

**Today's Progress:** Working on [CodeWars](https://www.codewars.com) challenges
(aiming for, and achieving, *'3kyu'* in Javascript).

## Day 23: February 18, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com) challenges,
starting to focus on Python rather than JavaScript.

## Day 24: February 19, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com) challenges,
now entirely in Python.

**Thoughts:** Dates in Python are a bit of a pain, working with the `datetime`
module. Also, map/reduce etc are methods that **take** an array (or other list)
rather than being methods **of** such a list - which also means that in order to
generate a list **out of** one of those methods, you have to wrap it in a `list` call.
All feels quite foreign coming from a Javascript background.

## Day 25: February 20, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com) challenges.

## Day 26: February 21, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com) challenges.

## Day 27: February 22, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com) challenges, including
finishing the "Papers Please" *3kyu* challenge and an old *8kyu* Wilson Primes
challenge that always timed out or errored on recursion depth before.

**Thoughts:** A couple random items to remember:

* Python `re.match` **always** starts at head of string; use `re.search` instead
* Python has a built-in `math.factorial` method which is more efficient than anything I can write

## Day 28: February 23, 2019

**Today's Progress:** More [CodeWars](https://codewars.com) challenges, now circa 48%
through *4kyu* in Python.

## Day 29: February 24, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com) challenges, now 48% through
*3kyu* overall, 49% through *4kyu* Python and 9% through *3kyu* JavaScript.

Having run up against Monads in a CodeWars challenge and just not understanding it,
have decided to go back to [Professor Frisby](https://mostly-adequate.gitbooks.io/mostly-adequate-guide/)
and re-start. Also seems like there's quite a lot more content than the last time I looked
at it (I think it was only up to Ch6, now up to Ch12 which includes Monads and Functors).

## Day 30: February 25, 2019

**Today's Progress:** Continued reading [Professor Frisby's Mostly Adequate Guide to 
Functional Programming](https://mostly-adequate.gitbooks.io/mostly-adequate-guide/), including
working through examples/challenges. Through to end of Ch6.

## Day 31: February 26, 2019

**Today's Progress:** Continued reading [Professor Frisby's Mostly Adequate Guide to 
Functional Programming](https://mostly-adequate.gitbooks.io/mostly-adequate-guide/). Into Ch7 although
likely to need to recap again!

Also more [CodeWars](https://www.codewars.com) challenges, now 53% through *3kyu* overall,
59% through *4kyu* Python and 9% through *3kyu* JavaScript.

## Day 32: February 27, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com) challenges, now 54%
through *3kyu* overall, 65% through *4kyu* Python and 9% through *3kyu* JavaScript.

## Day 33: February 28, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com) challenges, now 58%
through *3kyu* overall, 74% through *4kyu* Python and 9% through *3kyu* JavaScript.

## Day 34: March 1, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com) challenges, now 64%
through *3kyu* overall, 91.7% through *4kyu* Python and 9% through *3kyu* JavaScript.

## Day 35: March 2, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com) challenges, achieved *3kyu*
in Python (now 67% through *3kyu* overall).

Also experimenting with text boxes in Excel using VBA (automating the addition of boxes
to a grid, trialling whether the Excel VBA grid is consistent across different versions
and platforms/OS's)

## Day 36: March 3, 2019

**Today's Progress:** Working through MongoDB and Mongoose challenges in the 
[freeCodeCamp](https://freecodecamp.org) curriculum.

## Day 37: March 4, 2019

**Today's Progress:** Updates to [LSERSA website](http://www.lsersa.org).

More [CodeWars](https://www.codewars.com) challenges.

Working out how to use UserForms in Excel VBA.

## Day 38: March 5, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com) challenges, and
more playing with Excel VBA.

## Day 39: March 6, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com) challenges.

## Day 40: March 7, 2019

**Today's Progress:** Researching maze-solving algorithms.

## Day 41: March 8, 2019

**Today's Progress:** Implementing maze-solving algorithm (using a depth-first
algorithm) plus some other [CodeWars](https://www.codewars.com) kata.

## Day 42: March 9, 2019

**Today's Progress:** More [CodeWars](https://www,codewars.com) challenges.

## Day 43: March 10, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com) challenges,
and more experimenting with Excel VBA.

## Day 44: March 11, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com) challenges.

## Day 45: March 12, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com) challenges.

## Day 46: March 13, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com) challenges.

## Day 47: March 14, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com) challenges.

## Day 48: March 15, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com) challenges.

## Day 49: March 16, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com) challenges. Update
on progress, 76.6% through *3kyu* overall, 15.1% through *3kyu* for Javascript. So
about 9% progress through *3kyu* in the last fortnight ... very slow going.

## Day 50: March 17, 2019

**Today's Progress:** A little [CodeWars](https://www.codewars.com) and a lot of
Excel VBA.

## Day 51: March 19, 2019

**Today's Progress:** Some more [CodeWars](https://www.codewars.com) after a day out ...

## Day 52: March 20, 2019

**Today's Progress:** Some painfully slow [CodeWars](https://www.codewars.com) including
irritating problems with arrays passed by reference rather than value ...

## Day 53: March 21, 2019

**Today's Progress:** Some more [CodeWars](https://www.codewars.com) and a little VBA.

## Day 54: March 22, 2019

**Today's Progress:** Some more [CodeWars](https://www.codewars.com).

## Day 55: March 24, 2019

**Today's Progress:** Excel VBA. Lesson - try to avoid writing a UI in Excel that uses
Userforms (modal dialogue boxes) - they're a pain, and almost impossible to write in the
Mac version.

## Day 56: March 25, 2019

**Today's Progress:** Excel VBA (all the way).

## Day 57: March 26, 2019

**Today's Progress:** Excel VBA again.

## Day 58: March 27, 2019

**Today's Progress:** Excel VBA again.

## Day 59: March 28, 2019

**Today's Progress:** More [CodeWars](https://www.codewars.com).

## Day 60: April 7, 2019

** Today's Progress:** So a week off thanks to some work issues and travelling 
to France. Back on the wagon again today though - spent an hour with my daughter
experimenting with HTML and CSS, and half an hour reading through some of the Apple
Human Interface Guidelines (considering dipping back into iOS again).

## Day 61: April 8, 2019

**Today's Progress:** Re-visiting an old iOS app (for Gin Rummy score-keeping)
and considering whether it's worth trying to fix the issues (and bugs) with it, or
instead to re-start from scratch.

## Day 62: April 9, 2019

**Today's Progress:** Working on LSERSA and Bowles websites.

## Day 63: April 10, 2019

**Today's Progress:** LSERSA website updates.

## Day 64: April 17, 2019

**Today's Progress:** Excel VBA work.

## Day 65: April 19, 2019

**Today's Progress:** LSERSA website updates and Excel VBA work.

## Day 66: April 21, 2019

**Today's Progress:** Experimenting with SVG animations.

## Day 67: April 22, 2019

**Today's Progress:** Continuing to experiment with SVG animations, starting to
build a watchface simulation.

**Link to work:** [CodePen](https://codepen.io/domwakeling/full/GLGdEY)

---

**Footnotes**

<a name="myfootnote1">1</a>: For when I forget: use Grab (SHIFT + CMD + 4) to
capture image from the portfolio view; crop in PhotoShop (will end at 371x292);
set guides at 0, 5, 10 & 15px from each edge; path to the (0,10) guide marks,
then 5px beziers; path to selection; invert selection; erase corners; delete
path; save as PNG; load to Google Drive; make shareable and use
[gdurl.com](https://gdurl.com) to get a link. Simples ...
