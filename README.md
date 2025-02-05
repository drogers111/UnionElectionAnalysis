Hey there. The code for this project is lost data right now, but I'm working on reconstructing it from tidbits in my analysis which has been uploaded as a pdf in this repo. 
The core idea for this project was to take National Labor Relations Board data about union elections and use that data in combination with other data I could find to come to some actionable advice on behalf of union organizers. 
The data files are below. The first set is the NLRB data.

https://drive.google.com/file/d/1v4QxQdFS1hwh3p_q7tl_31CPzHsF60cu/view?usp=drive_link, 
https://drive.google.com/file/d/13vzLzK-NZAlC4U2a-XHqdDqhMTn7o2AS/view?usp=drive_link, 
https://drive.google.com/file/d/1rzCjj1BXJ5aZHYcdxTfUq2VjYwpXIKWX/view?usp=drive_link, 
https://drive.google.com/file/d/1jYTGHR-MWXcRTWC29hiancE0v_xBkJQz/view?usp=drive_link, 
https://drive.google.com/file/d/1mEDzksTNbuizFL_swY2xPX_7zyc0zZRu/view?usp=drive_link, 
https://drive.google.com/file/d/1Oaj3AtAb_MMIpGmQ2obc3SioquJaWbVJ/view?usp=drive_link, 
https://drive.google.com/file/d/1qdWNv0M6cZ1IkdadXvIUyb9IfA-IyIO5/view?usp=drive_link, 
https://drive.google.com/file/d/1J_2S4ZyKuUVEbAawi-X1pTi56CBIWEc7/view?usp=drive_link, 
https://drive.google.com/file/d/1cP_hhRKORpacHfN4qtYFVrysbebRSW_g/view?usp=drive_link, 
https://drive.google.com/file/d/1DTDlTmXRyagAncE9R-pUPVGZGom0AFn6/view?usp=drive_link, 
https://drive.google.com/file/d/1KHNDqFD0NrC9BlLHQkPQWyi-9G6mFQJ6/view?usp=drive_link, 
https://drive.google.com/file/d/10ltSNf6Fg7KKhHgPzTtoxm0di3nm61BM/view?usp=drive_link, 
https://drive.google.com/file/d/1-C74-j6QwUZIKikI8oLXsz70mRTXlDyi/view?usp=drive_link, 
https://drive.google.com/file/d/1M3f8ipQdR7dZxVEDl2q_TAxksacX9b-L/view?usp=drive_link

[https://drive.google.com/file/d/1WRnnf3nVWSKhqtDpvIVDxHk7gLRa-maO/view?usp=sharing](https://drive.google.com/uc?id=1WRnnf3nVWSKhqtDpvIVDxHk7gLRa-maO&export=download)

The last link is a dataset found online containing presidential election vote counts for all candidates from both parties and other relevant candidates. For the purposes of my research, this dataset was used to establish some idea of 'local political leaning' 
and define 'strongly republican' and 'strongly democrat' states by their vote in the most recent presidential election, where 'strong' is any vote calculated as 55% or over when comparing 'candidatevotes' to 'totalvotes'. For example, the first row
in the US elections dataset contains the Democrat candidate Jimmy Carter's voting numbers in Alabama, where he earned 659,170 votes compared to 1,182,850 total votes 659170/1182850*100 = 55.7, meaning that my methodology categorizes Alabama as 'strongly democrat' 
for November 1976 through November 1980, at which point the categorization would then be determined by the following 1980 election. This is applied to all relevant data in the set (elections 2008 and after) because we do not have union election data before 2011. 

If you'd like any additional context you can contact me at droge@umich.edu . The analysis code should be reconstructed shortly. 
