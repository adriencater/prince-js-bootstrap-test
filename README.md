## How to make a PDF
 
- Start a local server. 
	- navigate to this folder in the terminal
	- run **`python3 -m http.server 8000`**
		- leave that terminal window open. 
		- (Python should be installed on your Mac…)

- Run the page though PrinceXML
	- open a second terminal window at this folder.
	- run **`prince -j http://127.0.0.1:8000/pdf-from-md.html -o test.pdf`**

#### If you didn't, first time:

- download and install PrinceXML. 
	- `https://www.princexml.com/download/`
	- (unlicensed version works great, you just have a watermark)

- change the first line in the `<script>` in the html file, so it points to your markdown file.

- - - -

- you can put the html and css files anywhere you need to make a PDF from a markdown file.

- this is a proof of concept, a solid implmentation would run as a node.js project and have options for differnt PDF rendering systems – but I like that this one is just simple vanilla html and css that magically does a thing.


#### Pro tips:
- up-arrow key in terminal re-runs last command. so in that Prince terminal window, you can just hit UP and Return to make a new PDF if you changed anything in the document/script. It's just like old-school web dev when you get to refresh the browser to see what you did!
- if you leave the PDF file open in Preview.app, it will update every time you generate a new PDF, if you're making adjustments and regenerating and faffing about. 

- - - -

## Test Content – Oblique Strategies

- A line has two sides
- Abandon desire
- Abandon normal instructions
- Accept advice
- Accretion
- Adding on
- Allow an easement (an easement is the abandon of a stricture)
- Always first steps
- Are there sections? <br>Consider transitions
- Ask people to work against their better judgement
- Ask your body



## Bibliography

Lorem ipsum.
