# Day 2 - Re-visiting Git Commands & Troubleshooting

## Issues, Challenges, & Solutions

**(Issue):** Created a Day-02 folder inside of Day-01. When trying to manually move folders inside of VS Terminal, I kept getting the error | **`coreylaw@Coreys-MackBook-Air devops-journey % mv devops-journey/Day-01/Day-02 devops-journey
mv: rename devops-journey/Day-01/Day-02 to devops-journey: No such file or directory`** |

**(Diagnosis):** Realized I was trying to move | `devops-journey` | into | `devops-journey` | which wouldn't make sense to add the main file inside of the main file. I also forgot the `.` This can be realized by seeing that `coreylaw@Coreys-MackBook-Air devops-journey %` directory is showing im in the devops-journey branch already.

**(Solution):** ```mv Day01/Day-02 .``` 

-----

**(Issue):** Couldn't move files manually in VS Code Explorer with mouse. 

**(Diagnosis):** Understood that to move something "Up" in the directory you have to drag it down, instead of trying to place it on top of the actual name folder.

**(Solution):** Dragged files downwards in the blank space instead of on top of the named directory.



## Reflection

Honestly, even though I felt stupid for making the same syntax errors, I actually managed to figure out the solutions on my own after tinkering with it for about 40 minutes. I know it may seem funny to you senior level engineers, but I actually feel pretty accomplished by figuring out the solutions. Not only that but I can understand why people actually enjoy this. The sense of gratification and accomplishment feels great when you figure it out all on your own.

Today was mostly just going over the git commands again. To my suprise, I actually remembered the commands and how to check the repository again without even needing a reference.

