## How to make a PDF

- Start a local server. 
	- navigate to this folder in the terminal
	- run **`python3 -m http.server 8000`**
		- leave that terminal window open. 
		- (Python should be installed on your Mac…)
- Run the page though princeXML
	- download and install PrinceXML. demo version works great, you just have a watermark.
		- `https://www.princexml.com/download/`
	- run **`prince -j http://127.0.0.1:8000 -o test.pdf`**

Pro tips:
- up-arrow key in terminal re-runs last command. so in that Prince terminal window, you can just hit UP and Return to make a new PDF if you changed anything in the document/script.
- if you leave the PDF file open in Preview.app, it will update every time you generate a PDF, if you're making adjustments and regenerating and faffing about. It's just like old-school web dev when you get to refresh the browser to see what you did!


## Test Content

- Sometimes, an email is just a way to say, “I love you.”
- People think about you much less than you either hope or fear.
- It’s often easier not to be terrible.
- Whenever you’re not sure what to say, either say nothing, or ask a question.
- Be sparing in how often you tell someone their negative feelings are wrong; it rarely helps a sad person to be told that they are also a liar.
- Related: feelings are *real*. (Thanks, Mike S.)
- Never organize anything you should discard.
- Organizing your email is like alphabetizing your recycling.