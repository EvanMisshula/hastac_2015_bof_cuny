# What is CUNY?

-   The City University of New York
    -   The US's largest municipal University System
        -   22 campuses
        -   274,000 students
        -   Founded in 1847 as the Free Academy

# Who are the players?

-   *Steven Brier* tenured professor in History and Urban
    Education. Co-founder of MA in Digital Humanities, the New Media Lab
    and Certificate program in Interactive Technology and Pedogogy and
    the New Media Lab.
-   *Matt Gold* is Associate Professor of English and Digital Humanities
    at the Graduate Center of the City University of New York (CUNY). At
    the Graduate Center, he holds teaching appointments in the
    Ph.D. Program in English, the M.A. in Liberal Studies Program
    (MALS), and the doctoral certificate programs in Interactive
    Technology and Pedagogy and American Studies. He serves as Advisor
    to the Provost for Digital Initiatives, Executive Officer of MALS,
    Director of the CUNY Academic Commons, Co-Director of the CUNY
    Digital Humanities Initiative, Director of the GC Digital
    Scholarship Lab, and Director of the GC Digital Fellows Program.
-   *Cathy Davidson*, a distinguished scholar of the history of
    technology and recently appointed to the National Humanities Council
    by President Obama, is a leading innovator of new ideas and methods
    for learning and professional development—in school, in the
    workplace, and in everyday life.

# Demographic Profile of CUNY Students

## Income

-   47% of CUNY undergraduates come from a household with less than $25K
    annual household income.

-   Only 23% of CUNY undergraduates come from a household with more than
    $17.5K per capita income.

## Work

-   78% of CUNY undergraduates work to pay living expenses

-   37% of CUNY undergraduates do not have broadband access at home

## Social Capital

-   43% of CUNY undergraduates have parents whose highest degree is high
    school or less

-   88% live with family

## Problematic focus

-   58% of undergraduates spend more than 10 hours a week attending classes

-   Only 27% of students spend more than 10 hours studying outside of class

-   70% of CUNY undergraduates spend no time participating in school activities

-   Six year graduation rate 47.6% ([cunyInstitutionalResearch](http://www.cuny.edu/irdatabook/rpts2_AY_current/RTGI_0007_FT_FTFR_BACC_TOT_UNIV.rpt.pdf))

## Demographic take away

Many CUNY students are from families that are struggling, financially
-   do not have private, quiet places to study
-   cannot access rich internet content at home
-   are pressed for time

# Funding for Graduate Students

-   Provost's Digital Innovation Grants
-   GC Digital Fellows
-   Macauley Instructional Technology Fellows
-   GC Social Media Fellows
-   Futures Initiatives Fellows
-   GC Center for the Humanities Fellows
-   GC Videography Fellows

## Scholarly communication

-   blog [Academic Commons](https://commons.gc.cuny.edu/) (2009)
-   Free project [CBOX](http://commonsinabox.org/) (13,700 downloads)

## Digital On Ramp

-   [DHBox](http://dhbox.org/) (2014 NEH Startup grant winner)
-   Social Paper (2015 NEH Startup grant winner)

### Statistics

-   [R language](http://www.r-project.org/)

### Network Analysis

-   [NetworkX](https://networkx.github.io/) (python)
-   [Statnet](http://www.statnet.org/)-SNA (R)

### Text Analysis

-   [NLTK](http://www.nltk.org/)
-   Topic Modelling (R [Mallet](https://github.com/mimno/RMallet))

### Mapping

-   D3js, leafletJS
-   TileMill
-   QGiS

### Actitivism

-   PGP Privacy
-   ToR

### Structured Collaboration

-   Git, vcs, subversion

### Data visualization

-   R ggplot
-   D3 interactive vizualization

### Reproducible research

-   docker, virtual box, org-mode, IPython, Sweave, Knitr

# Topics

## Projects on the campuses

## Difference between Free and Open Source

## Problems in Free Software Community diversity

## Computer Science is not always a leader on Free Software

> At the other end, "IP communists" object to copyright protection and
> software patents, and even argue that software should be free. It is
> regrettable, I believe, that the open access (OA) movement found
> itself in the IP communist camp.

Moshe P. Vardi, Editor-in-Chief of Communication of ACM

## Equipment as a barrier to adoption

-   lab spaces
-   student laptops (economic gating)

## Maintenance problems

-   necessity for admin rights
-   computer labs are unusable

## partial solutions

# Reproducible research

Reproducible research is the idea that scientific claims are published:
-   with their data
-   software code used to analyze them

# Clarebout's principal

> An article about computational result is advertising, not
> scholarship. The actual scholarship is the full software environment,
> code and data, that produced the result.

Claerbout and Karrenbach, Proceedings of the 62nd Annual International Meeting of the Society of Exploration Geophysics. 1992

# Tie code to figure

> When we publish articles containing figures which were generated
> by computer, we also publish the complete software environment
> which generates the figures

Buckheit & Donoho, Wavelab and Reproducible Research, 1995.

# Overview

-   scope of the problem
-   definitions
-   current practice
-   tools
-   changes to improve reproducibility and differentiate research

# Is *#Reproducibility* a problem?

## Cancer research

-   In 2012, an Amgen team tried to reproduce important resutls
-   pre-clinical targets for cancer
-   47 out of 53 medical research papers
-   were irreproducible

(<http://www.nature.com/nature/journal/v483/n7391/full/483531a.html>)

## Psychology

-   Researchers explained in a 2006 study that, of 249 data sets from
    American Psychology Association (APA) empirical articles, 73% of
    contacted authors did not respond with their data over a 6-month
    period.
-   <http://www.ncbi.nlm.nih.gov/pubmed/17032082>

## Psychology II

![img](./images/Screen Shot 2014-11-02 at 10.53.23 PM.png)

-   Ioannidis, *Why science is not necessarily self-correcting* 2012

## Economics

### **Reinhart & Rogoff** *Growth in a time of debt*, NBER, 2009

-   High debt-to-gdp and low gdp growth are associated
-   Made their calculations in Excel
-   Substantial popular impact on autsterity politics

-   Grad student finds an error in the coding

-   Herndon, Ash and Pollin publish a rebuttal

### Advice from a statistician

![img](./images/Screen Shot 2014-11-03 at 12.07.36 AM.png)

## Computer Science

Christian Collberg (<http://reproducibility.cs.arizona.edu/v1/tr.pdf>) looked 
at the papers in eight conferences and five ACM journals.  They were able 
to reproduce 102 out 613 papers 24.9%

## History of reproducible research

### Mathematics

-   First proofs Greeks (ca. 400 B.C.E.)
    -   Pythagoras (569–500 B.C.E.) proofs
    -   Euclid of Alexandria (325 B.C.E.–265 B.C.E.) axioms and definitions
    -   Eudoxus (408 B.C.E–355 B.C.E.) theorems
    -   William of Occam (1288 C.E.–1348 C.E.) fewest steps

### Advances in mathematics and proof

-   Jean Baptiste Joseph Fourier (1768–1830) 
    -   expansion of an arbitrary function into a trigonometric series
-   Evariste Galois (1812–1832) and Augustin Louis-Cauchy (1789–1857) 
    -   abstract algebra by inventing group theory.
-   Bernhard Riemann (1826–1866) 
    -   differential geometry, complex variable theory
-   Augustin-Louis Cauchy
    -   partial differential equations
-   Carl Jacobi (1804–1851), Ernst Kummer (1810–1893), Niels Henrick Abel (1802–1829)
    -   number theory
-   Joseph Louis Lagrange (1736–1813), Cauchy 
    -   calculus of variations, classical mechanics, the implicit function theorem
-   Karl Weierstrass (1815–1897) 
    -   real and complex analysis with numerous examples and proofs

### Anti-replicatants

-   Gauss
    -   inscrutible style
-   Bourbaki
    -   Rejection of intuition of any kind

### Gauss

> No self-respecting architect leaves the scaffolding in place after completing the building.

attributed to Carl Friedrich Gauss (1777 C.E. - 1855 C.E.) in defense of his inscrutible style

### Twentieth Century Contributions

> A proof is any completely convincing argument.

Everret Bishop, inventor of *Constructive Analysis*
E. Bishop, *Foundations of Constructive Analysis*, McGraw-Hill, New York, 1967.

## Experiments

-   Robert Grosseteste (c. 1175 C.E. –  1253 C.E.)
    -   reasoned from universal to particular prediction
    -   *Posterior Analytics*
-   Roger Bacon, (c. 1214 C.E. – 1294 C.E.)
    -   observation, hypothesis, experimentation, and the need for independent verification.
-   Galileo (1564 C.E. - 1642 C.E.),manufactured multiple *copies* of his telescopes
-   Pasteur added *Materials and Methods* section to articles

# Modern leaders of reproducibility I

-   Knuth (1984) "literate programming"
    -   <http://comjnl.oxfordjournals.org/content/27/2/97.short>
-   Stallman (1984) FREE software
    -   <https://www.gnu.org/philosophy/free-sw.html>
-   Lessig, Abelson and Eldred (2001) Creative Commons
    -   <https://creativecommons.org>
-   Torvalds (2005) git
    -   <http://git-scm.com/book/en/v2/Getting-Started-A-Short-History-of-Git>

# Modern leaders of reproducibility II

-   Iodonnis (2005)
    -   most published research is False
    -   25 million papers between 1996 - 2011
    -   85% of research assets are wasted
    
    <http://www.plosmedicine.org/article/info%3Adoi%2F10.1371%2Fjournal.pmed.0020124>
-   Stodden (2007)
    The Legal Framework for Reproducible Scientific Research: Licensing and Copyright
    -   <http://researchcompendia.org>
    -   <http://www.runmycode.org>
    -   <http://scitation.aip.org/content/aip/journal/cise/11/1/10.1109/MCSE.2009.19>

# Tools for computational reproduciblity

-   (Stodden, April 2014)
    -   <http://web.stanford.edu/~vcs/Talks.html>
-   (Marwick, March 2013)
    -   <http://rpubs.com/benmarwick/csss-rr>

## Dissememination platforms

-   [ResearchCompendia.org](http://researchcompendia.org/) (already published articles)
-   [MLOSS.org ](http://mloss.org/software/) (machine learning)
-   [thedatahub.org](http://datahub.io/) (data sets)
-   [Open Science Framework](https://osf.io/) (planning to publishing)
-   [Madagascar](http://www.ahay.org/wiki/Main_Page) (multi-dimensional analysis)
-   [nanoHUB.org](http://nanohub.org/) (nano-techonology simulation platform)
-   [runmycode.org](http://www.runmycode.org/) (code and data)

## Research Environments

-   [VisTrails](http://www.vistrails.org/index.php/Main_Page#VisTrails_Overview) (python libraries and \LaTex)
-   [Kepler-project](https://kepler-project.org/) (R and C wrappers though built in Java)
-   [Galaxy](https://usegalaxy.org/) (biomedical data analysis)
-   [GenePattern](http://www.broadinstitute.org/cancer/software/genepattern/) (gene analysis framework)
-   [Sumatra](http://neuralensemble.org/sumatra/) (electronic notebook for simulations)
-   [Taverna](http://www.taverna.org.uk/introduction/) (workflow management and R)
-   [CDE](http://www.pgbovine.net/cde.html) (portable linux apps with data and dependencies)

## Embedded Publishing

-   [Jupyter](http://jupyter.org/) (2014, multi-language interactive environment)
-   [IPython](http://ipython.org/) (Perez and Granger, 2007, python interactive environment)
-   [Verifiable Computational Research](http://vcr.stanford.edu/) (Stanford University, matlab plugin)
-   [Collage](https://collage.elsevier.com/) (Elsevier)
-   [share](http://is.ieis.tue.nl/staff/pvgorp/share/) (University of Eindhoven, linux containers)
-   [Sweave](https://www.stat.uni-muenchen.de/~leisch/Sweave/) (Leisch 2002, R)
-   [knitr](http://yihui.name/knitr/) (Xie, 2013, R)
-   [Org-mode](http://orgmode.org/) (Schulte, 2012, multi-language)

## Org-mode solves three problems

(Kitchin, *Emacs, Org-mode + python reproducible research*, 2013)
<http://www.youtube.com/watch?v=1-dUkyn_fZA>

-   documents computation workflow
-   integrates text, math and code
-   produce or modifies a figure

## Org mode and Emacs

-   Emacs is written in a full programming language
-   understands LaTeX, markdown, language modes (R, Python, C, C++ and Java etc.)
-   can interact with OS
    -   execute code
    -   read the standard output
    -   read the standard error (and insert into the buffer)

## Org-mode

-   note taking
-   TODO lists
-   differentiates between text, code and data
-   code executes in the buffer
-   enables links to files, urls
-   \#+INCLUDE allows files to be broken into reusable pieces
-   exports available LaTeX, html, reveal.js etc.
