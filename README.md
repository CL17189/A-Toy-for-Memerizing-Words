# A-Toy-for-Memerizing-Words
It is a toy for memerizing words in some English Exams like IELTS, GRE. But it is just half completed and only has basic functions because i am not so good at WEB designing. :D
## Where does it come from 
Well, i was inspired by the way of memorizing new words shown in this video:[Use chatGPT to learn new words](https://www.bilibili.com/video/BV18d4y1p7M4/?spm_id_from=333.880.my_history.page.click&vd_source=cb83cd707ed0a05e87e9bcd5c1ee544a) Similarly, according to my personal experience, i believe memorize-and-read really works. Every time it just like rooting in my mind if i see or memorize a word in books or soemwhere and meet it again few days later. Gre exam is really hard in its words and it takes me a lot of time and effort. So i made such a toy to help me.

## What in the words list
And the words list include some difficult words in GRE exam. I just summarized it by myself. Therefore, not all the words of GRE are included. It has Five columes which are Word, Part, (Chinese) Meaning, Date, Link. So, maybe it just suits for Chinese speakers. 
## About .ipynb
It sends 20 words in the list to models every time and receives a passage that was created by chatGPT using those words. This python file is to tranform passages into txt files and record their name in excel(Link column)
## About .html
In this file, we generate a random integer to decide which 20-words are turned to be selected and shown in the left-side table. In the right part of the page, we will show you related passage.
## Drawbacks
The designing of the whole page is necesarily needed to be improved. We want to make it more colorful and dynamic. 
And just as the saying goes in the video, new words in the passage should be tagged with their chinese meaning. I haven't done that because of the davincci model. I fail to enable it to speak chinese(lol)  :D
