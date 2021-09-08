#Crime Novel Plot Analysis with Regex

###Description

The goal of this project is to conduct a plot and protagonist/antagonist analysis of the famous crime novels. For this project, you will analyze five publicly available crime novels/stories by famous crime novelists - Sir Arthur Conan Doyle, Agatha Christie, and Mary Roberts Rinehart (the American Agatha Christie).

You can find novels at the project Gutenberg site: http://www.gutenberg.org/ (Links to an external site.).

Agatha Christie (692 Project 1) investigators will use all of the five available novels. Doyle (692 Project 2), and Rinehart (692 Project 3) investigators can choose any five, but the longer -- the better. Feel free to use any background resource for the understanding of the plot, protagonist and antagonist names, and other details. Look for spoilers, details, etc. Our goal is not to predict the crime, but to computationally analyze the structure of the plot.

To conduct the analysis, you will use Python and regular expressions. You can use spaCy and Matplotlib or other Python visualization libraries to visualize your results. Keep it as simple as you wish, or get creative. Just don't get lost in the complexity and miss completing the work.

###Analysis to be Performed

To goal of this project is to analyze the frequencies of occurrence of the protagonists and the perpetrator(s) across the novel - per chapter, and per sentence in a chapter, the mention of the crime, and other circumstances surrounding the antagonists. The ultimate objective is to use basic NLP tools to observe any patterns in plot structures across the works of one or all of the authors.

Specifically, for this project, you are to analyze and report on:

When does the detective (or a pair) occur for the first time - chapter #, the sentence(s) # in a chapter, When is the crime first mentioned - the type of the crime and the details - chapter #, the sentence(s) # in a chapter, When is the perpetrator first mentioned - chapter #, the sentence(s) # in a chapter, What are the 3 words that occur around the perpetrator on each mention (i.e., the three words preceding, and the three words following the mention of a perpetrator), When and how the detective/detectives and the perpetrators co-occur - chapter #, the sentence(s) # in a chapter, When are other suspects first introduced - chapter #, the sentence(s) # in a chapter To effectively conduct this analysis, you should find resources, and read the plot summaries of each novel, so you can make your search more effective. If plot summaries are not available, use regex to search for clues, and report how well/how fast that approach worked.

###The Deliverable and Implementation Logistics

Use only Python regular expressions to perform the analysis, and only use spaCy as a runner.

(If you wish, you can use other components from spaCy for additional analysis, if the time permits)

In your report, describe your findings in both writings, and use matplotlib or similar Python visualization tool to visually report your findings (see https://matplotlib.org/3.2.1/gallery/lines_bars_and_markers/timeline.html (Links to an external site.)).

Report everything in a 4-pages long report (maximum), excluding references. Use proper, grammatically correct, and clear academic English.

Use Overleaf report template ECE 692 F2021 Begoli NLP Projects Template (Links to an external site.), and be ready to present results from a paper in a 15 min presentation.

Submit your assignments as a link to a Google Drive that has a Google Collab file, and a PDF of a paper. Also, prepare slides for the presentation.

###Resources

Use this as a guide for how to write a good paper: https://www.froihofer.net/en/students/how-to-write-a-computer-science-paper.html (Links to an external site.).

###Due Date

Submit files on September 26th, 2021 23.00/11 pm EST, and be ready to present the results the following Monday (.September 27th)

###Project Organization

You will work on a team of three people (except for one 4-person project). There should be a single project manager for the project.

###Support and Expectations

Project managers will be responsible for communication with the instructor, and the timely delivery of the report, the code, and the presentation. I will offer help on any topic you need. This is an investigative project.
