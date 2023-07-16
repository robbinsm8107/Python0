# Python_Project0
<h1>Kilograms to Pounds / Pounds to Kilograms Converter</h1>
I have taken a course on Sophia.org in preparation to start my Computer Science Degree at Western Governor's University. This is a very simple final project that I have created within the Replit.com web browser Integrated Development Environment (IDE). 
<br>
https://replit.com/@robbinsm8107/SophiaPython0

<h2>Environments and Technologies Used</h2>

- Sophia.org
- Replit.com
- Python 3.3

<h2>Operating Systems Used </h2>

- Windows 11 Operating System
- Replit.com (Web Browser IDE)

<h2>High-Level Steps</h2>
- I went through the Sophia Introduction to Python Course to gain a high-level overview of basic programming steps and use cases.
<br>
- I watched a few example project videos from Youtube to gain a better understanding of use cases. 
<br>
- I wanted to find something relatively simple, but useful to daily life (my brother competes in BJJ) and came up with this calculator.

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/AjS3QZv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is the overall, raw Python code for this project. I have created comments throughout the code to better explain what I was trying to do and why certain decisions were made within the code.
</p>
<br />
<h2>Final Testing</h2>

<p>
<img src="https://i.imgur.com/3pXCUiH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/dMW7jmh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I set this code up with a relatively simple "if / else" algorithm. If the user puts in their weight and then utilizes a lower case or upper case "K", then the algorithm will utilize the Kilograms to Pounds calculator and multiply the user's "weight" by 2.2. Whereas if the user chooses any other character sequence besides lower case or upper case "K", the algorithm will assume they mean the above weight was in pounds and will divide the original number by 2.2. 
</p>

<h2>Software Testing / Quality Assurance </h2>

<p>
The way that I tested this simple project, was that I brought my computer to my brother's house and asked him to try to "break it". Originally, I had very strict rules set up for the algorithm and we had plenty of errors at first. If you did not utilize a capital "K" or capital "L", then there would be an error occurring because those are your only two choices. My brother mentioned a great point that I overlooked; why not allow lowercase letters? So, I found functionality to force the capital letters to be used:
  "if unit.upper() == "K":"
This forced capital "K" to be used whether the client typed a lower case or upper case. Originally I did the same for "L" meaning pounds, but decided to type the code where anything but the letter "K" would assume that the client/user means that they are trying to find the pounds to kilogram conversion. 
</p>
