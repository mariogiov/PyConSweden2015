# Introduction

## 0. Brief introduction to genomics

Bioinformatics is an interdisciplinary field that aims to develop and improve methods
to retrieve, store, organize, and analyze biological data. It encompasses an wide
range of research areas, which makes it difficult to precisely define.

In genomics, the necessity of understanding the DNA structure has driven the development
of Bioinformatics. Nowadays, 3-day-long sequencing experiments on a single machine using
the newest sequencing technologies can generate as much data as entire genome centers did just
a few years ago. This translates into an exponential growth of the information available, which
prompted the **need** for well-designed and written software to manage and analyze this
data.

Compare DNA and other concepts to programming!

1. The DNA is byte code but instead of 0s and 1s we have As, Cs, Ts, and Gs.

2. So what do they encode? Combining a string of bases can produce a gene. A gene
   encodes a protein (the same you eat to build muscles), often an enzyme. Enzymes
   usually have one very specific task to carry out in the body.

3. Genes are further grouped into longer stretches of DNA strands called chromosomes
   which make up the software for your body.

4. Lastly this code is run inside the cell which is the hardware that understands what
   to make of the code. Basically you can "boot up" a cell with whatever DNA source
   code you want.

### How is the data generated?
...

### How is it clinically useful?
The genome is your genes: your DNA. It's the inheritable code that determines
fundamentally how you will develop. When the code is passed down from parents to child,
the entire code is copied and mixed manually. This process introduces bugs (mutations), most of
which are perfectly benign. But in the rare case that a mutation causes disease,
we are interested in finding and learning more about how.


## 1. What makes Python uniquely capable of handling NGS data?
[Why python?](http://www.nature.com/news/programming-pick-up-python-1.16833)

Python is a very versatile and easy to use language. It is famous for having a very
quick learning curve:

![Python XKCD](/assets/python.png?raw=True)

This eases the introduction to programming for people not accusomted to it:
molecular biologists or life scientists in general. The fact that it is so widely
used also gives new programmers a lot of extra help in the form of forums, tutorials,
conferences, etc.

A strong feature in the life sciences is how easy it is to work with files and strings in
Python, since _every_ scientific computing program needs to work with input files, as
basically they work with results from lab experiments that come in a large range of
different formats. Perfect for gluing tools together.

Python is a general purpose yet simple language for beginners, which is probably also a reason
it is so prevalent in bioinformatics. In fact, Python has at near monopoly in Science
([ref][monopoly]). There's a large open-source community (numpy, pandas) which ties very
well into the academia-heavy field. A downside is that many groups are still
transitioning to using Git and unit testing, for example.

Reverse the question: what if Python didn't exist?
  - Where would that have left us?
  - It's an impossible question but it's sort of scary to imagine that reality... Perl...
  - I think at least we are better off with our current situation!

## 2. Who are these two guys?
Spanish vs. Swedish, CS vs. Biology, DevOps vs. Design

### Guillermo Carrasco
My name is Guillermo Carrasco and I am a software engineer infiltrated between biologists :)

To be honest, I ended up in Life Sciences by pure chance. A couple of years ago I was
looking for a part time job to pay my engineering studies in Spain, and I saw a system
administration job advertisement at the Molecular Biology Institute of Barcelona. After
applying and being hired, I started working with people that were so passionate
about what they were doing that they were willing to learn how to code by themselves
in order to achieve what they were looking for. I've always admired that so much -- it took
me 5 years of university!

I decided to do my MSc. Thesis abroad and this is how I ended up at the Science For Life
Laboratory, where my interest in life science has been growing and growing, always
motivated by the strong open source and collaborative environment that is growing
among scientists.

Nowadays I spend my day helping researchers with data management and software development.

### Robin Andeer
My name is Robin Andeer and I develop tools to solve medical mysteries at SciLifeLab.

Many scientists spend a lot of time doing research. When it comes time to analyze your
data you often realize that no one has built something to meet your specific research-y
needs.

So you start to inch your way to becoming a programmer to accomplish your goals. All of
a sudden you notice you are really more of a developer than a researcher. Your mindset
has changed and you find these new technical problems very interesting in their own right.

It's very motivating to still have the medical/research goals in the background, but
still. This was at least my own experience. I started in the lab in school, and now
sit in front of a computer all day - and couldn't be happier to be on the other side
of the glass walls.

I believe this story resonates with many "scientific" programmers. Some of the most
influential developers in the field are ex-researchers that initially taught
themselves to code. Brad Chapman, Aaron Quinlan, etc. [insert GH streak] Do you think he
has time for lab work anymore? Hehe. Now *they* are pushing the envelope when it comes
to building scientific software.


[monopoly]: http://news.kynosarges.org/2015/04/05/programming-languages-in-2014/
