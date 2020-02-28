RESUME PARSER

In this work, I have done a resume parser based on regex techniques.
It can find email id, phone number, skill set, educational qualification and experiences.

For finding email id and phone number, the programs uses pattern matching.

For skill set finding, we have a the set of all skills in valid_skill.txt file. The program compares each word in the resume and looks whether that word is there are not in valid_skill.txt

For finding education qualification, it is again based on keyword matching. Keywords should be mentioned in education.txt.

Experience are usually mentioned with dates in the fromat of Jan 2019 to Nov 2019 and some other format. The program looks for such formats and extract experience.

Further works:
1) We can do Name Entity Recognition for recognizing names, experience and skills from the resume.

2) Given a set of job description, we have to extract resumes matching the description.