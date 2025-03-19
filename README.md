# occupation-solver
Find Your Best Match ANZSCO Occupations in Just a Few Clicks！

Occupation Solver is a free, downloadable GUI program written in Python. By answering up to 24 multiple-choice questions, this program will help to match your working experience to one or more occupations defined in ANZSCO v1.3, which can be useful for your Australian visa application. The program supports both English and (simplified) Chinese languages.

You need a Windows operating system to run the program. Simply download the .exe file [here](https://github.com/indeed-stupid/occupation-solver/releases/tag/Occupation_Solver_v1.0.0) and run it. If your firewall is blocking the program, please allow it through.

***What is ANZSCO?***

ANZSCO stands for the Australian and New Zealand Standard Classification of Occupations. Most Australian working visas have corresponding occupation eligibility criteria, requiring applicants to have qualified working experience in specific occupations as defined in ANZSCO. As a result, applicants must determine which occupations their past working experience matches. Occupation Solver uses ANZSCO version 1.3, the version most Australian visa legal instruments are based on. Check [the home affairs' website](https://immi.homeaffairs.gov.au/visas/working-in-australia/skill-occupation-list) for more details.

***How can this program help me?***

You may have held several jobs in the past, but there might not always be a direct one-to-one correspondence between your job titles and the standard occupations. For example, a data scientist, depending on the specific responsibilities of the role, could be matched to occupations such as Statistician (224113), ICT Business Analyst (261111), Developer Programmer (261312), or even a combination of these. These differences can affect your visa eligibility. Occupation Solver aims to match your job experience to the standard ANZSCO occupation definitions and filter out the most likely results. While some consultants may charge hundreds of dollars per hour for this service, Occupation Solver provides it for free.

***How it works?***

There are 1,023 occupations defined in ANZSCO v1.3. Since I have no prior knowledge of most of Occupation Solver's potential users, the program will initially assume equal probabilities for all occupations. The user will answer a series of multiple-choice questions where they match their work experience to various descriptions. Based on their responses, the program will update the underlying probabilities using Bayesian statistics and determine the next question. Thanks to the hierarchical structure of the classification, the program can first match the user to broader categories that encompass many occupations, and then progressively narrow down the results until it reaches the most specific occupation level.

***Occupation Solver is designed and developed by 实愚 (Shi-yu), a PhD candidate in statistics. 实愚 also holds a first-class honours degree in mathematics and has prior experience as a programmer/software engineer. If you find Occupation Solver helpful, you can support me via the PayPal or WeChat QR codes available in the program. Enjoy!***
