# Social Graph : Project Assignement

To get information about what is the project is about, and have key data about the graph, please visit the website : http://dtu-graph.lyxx.fr \
To try our solution, then check out webapp : http://dtu-graph.lyxx.fr/webapp

## About this notebook

You will find explanations about the code itself in the notebook, where each functions are commented. \
Here is the global idea :
1.  Create a graph with networkx, each node is a class with attributes such as langage, level, ects.., each edge shows a compatibility between two class
2.  Get the data to feed the graph. In order to do so, we extracted the html data of the following pages, that we then hosted on our server at http://dtu-graph.lyxx.fr/data :
    * https://chrome.google.com/webstore/detail/dtu-course-analyzer/bimhgdngikcnelkhjindmdghndfmdcde?hl=en
    * https://kurser.dtu.dk/search?CourseCode=&SearchKeyword=&SchedulePlacement=E1%3BE2%3BE3%3BE4%3BE5%3BE1A%3BE2A%3BE3A%3BE4A%3BE5A%3BE1B%3BE2B%3BE3B%3BE4B%3BE5B%3BE7%3BE&CourseType=&TeachingLanguage=
3.  Make an UI with Jupyter Widgets so the user can select classes in the graph, see info about this class, and track the number of ECTS in his basket
4.  Use Voila to transform the notebook into a web application, so the UI can be executed without having to download the code.
