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
interface using Pythonista's *'ui'* module

---

**Footnotes**

<a name="myfootnote1">1</a>: For when I forget: use Grab (SHIFT + CMD + 4) to
capture image from the portfolio view; crop in PhotoShop (will end at 371x292);
set guides at 0, 5, 10 & 15px from each edge; path to the (0,10) guide marks,
then 5px beziers; path to selection; invert selection; erase corners; delete
path; save as PNG; load to Google Drive; make shareable and use
[gdurl.com](https://gdurl.com) to get a link. Simples ...