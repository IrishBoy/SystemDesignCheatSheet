```dataview
TABLE rows.file.link as SubTheme  
FROM "Courses/Application Architecture"  
where file.folder != "Courses/Application Architecture"  
FLATTEN regexreplace(file.folder, ".*/", "") as Theme  
group by Theme  
SORT file.folder
```


First of all, this course is not one more "How to pass System Design interview in MAANG" or "Excel your system design interviews". This course is dedicated towards people who are new to IT or is looking forward broaden there horizons on the field of System Analysis or maybe who thinks that they lack of knowledge in IT. Most of the information in this course was taken from my personal knowledge database (well, for sure before appearing in it, it was either on some site or in one of my projects).

So, cut the crap and let start. 
Number zero, despite the fact that I call it a "course", the better name is dictionary or check-list, or whatever. Since I mainly focus not on teaching things, but on giving things that should be learned. 
Firstly, there are two ways of going through this course
- Along, going from chapter to chapter as I modelled it
- Go to the chapters that interest you the most
Secondly, Chapter [Cases](obsidian://open?vault=Laptop&file=Courses%2FApplication%20Architecture%2FCases%2FCases) may be presumed as preparation for passing System Design interview, but I would't like to make it the main target of this course.
Thirdly, it is not about writing code, it is about structuring logic, modelling architecture, sometimes unorthodox approaches and mostly about interaction between services, not inside service. That means this course is not about writing the code)
Each part will be divided into three stages
- Basic
- Average
- Expert
