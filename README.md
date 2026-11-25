# daml-assignment-1
a) This repository contains data extracted from 41 letters of Quaker correspondence from 1600-1699 from Abraham correspondence vol 364. It displays the sender, receiver, date, sender location and receiver location. One item is a singular letter. 

b) I created this dataset because I thought it was interesting to see early Quaker correspondence, who was corresponding with who and where letters were going to about the religion. It could be useful for basic counting of who was sending letters, how many letters exist per decade that are recorded in the data etc.It could be used to track where certain individual were at a given time.

c) I chose to include only items that were clear correspondence, for example I excluded some marriage certs or records of wealth, these weren't relevant for the information I wanted to extract, and I included only those letters which were from 1600-1699. I chose to focus only on one decade to capture the earliest correspondence and as a suitable narrowing for the dataset.

d) I downloaded the files manually from a digital repository https://stars.library.ucf.edu/printmigrationnetwork-abrahamvol364/ last accessed on 2026-11-25.

f)   metadata.csv contains one item (a letter) per row
     check_dataset.ipynb uses pandas to count the number of items, checks that all IDs are unique, counts the number of missing values and provides a summary both for        the number of letters per decade and the number of letters per sender.
     requirements.txt lists the required software to run the programme
     .gitignore excludes irrelevant files
  
  Codebook:
  Variable            Description                                        Type                  Allowed Values/Missing Values
  ID                  Unique print ID                                    Text, Unique ID       Unique print ID, no missing values
  Source              Original link to file                              URL                   URLs no missing values
  Licence             Wording of the licence and permission for reuse    Text                  
  Sender              Name of the person who sent the letter             Text, catalogue name  Names, blank if missing
  Recipient           Name of the person who received the letter         Text, catalogue name  Names, blank if missing
  Date                Date the letter was written                        Integer, YYYY-MM-DD   Year from 1600-1699 with full date if available, blank if missing
  Sender Location     Location the letter was sent from                  Text, catalogue place Full address, county, city, country or area if available, otherwise blank
  Receiver Location   Location the letter was received                   Text, catalogue place Full address, county, city, country or area if available, otherwise blank

g) This dataset represents a selection of letters in English between the years 1600-1699 from Quakers. It can be used, again, for simple counting or location tracing. It does not include the content of the letters or letters which are not digitally archived as part of this catalogue. It should not be used to assume any relationships between individuals or what ideas were shared.

h&i) On the website it states "All users must respect the intellectual property rights of the author. Materials may be downloaded for education and research purposes provided due recognition is given to the author. Material may not be copied, distributed, displayed, altered, or used for commercial purposes, unless such use is specified." and on the works it is stated: "This Correspondence is brought to you for free and open access by the Quaker Correspondence at STARS. It has
been accepted for inclusion in Abraham Correspondence, Volume 364 by an authorized administrator of STARS. For
more information, please contact STARS@ucf.edu.". Access and download is clearly permissible, but since redistribution is not specifically mentioned I chose not to upload my data to a public repository as it seemed slightly unclear. This can be added if you think it is allowed and required. It does not contain any current personal information and not any information that is not publicly accessible and does not threaten any individual with harmful content.

Collins, I. (2026). Quaker correspondence in the Abraham collection [daml-assignment-1]. GitHub. [REPOSITORY URL]

  
