# Code-Refactor-Homework1
# What was the motivation for this project?

Web accessibility is an increasingly important consideration for businesses, ensuring that people with diabilities or socio-economic restrictions have access to their website, while helping them avoid litigation. 

The motivation of this project was to ensure that existing website stays visually the same while making the code more sustainable. 

#   Why did I build this project?

By refactoring the code for our clients, Horiseon, we are able to improve the code base for long term sustainability through making the code itself more efficient and cleaner to read. This is important to do as you want to make both the html and the css are easy to read and understand for those who come after you. 

#   How did I accomplish refactoring the code for our client, Horiseon?

I made the following changes to the code. The sections are divided up by the changes made to the index.html file and the style.css file. 

Index.html Changes:

*Changed div to section around class=search engine optimization (line 29)
*added alt text to line 30 for the search engine optimization image
*changed div to section around id=online reputation management (line 36)
*added alt text to line 37 for the online reputation management image
*changed div to section around id=social media marketing  (line 43)
*added alt text to line 44 for the social media marketing image
*added alt text to line 54 for the lead generation image
*added alt text to line 61 for the brand awareness image
*added alt text to line 68 to cost management image
*removed the </img> and changed the image wrapping around Cost Management on line 68
*Changed Title to a more descriptive title of the company not just websit. It was changed to Horiseon Website
*changed div to section on line 51 and 73 as this is a separate section on the side of the website
*added reset.css file and linked them
*removed id="online-reputation-management" and id="social-media-maketing" as they already had a class assigned to this and no corresponding CSS
*Added comments and dividers to the html to provide a quick reference for the following sections, as well as, a quick summary or pertinant changes. 

Style.css Changes:

*Moved .content to below .hero to reflect the order in the HTML
*corrected the css for the font calibra as it was not correctly inputed, should be 'calibra'
*moved p below .float-left to reflect the order in the HTML
*moved .benefit-brand h3 to below .benefit-brand to reflect order in HTML
*moved .benefit-brand img to below .benefit-brand h3 to reflect order in HTML
*moved .benefit-cost h3 to below .benefit-cost to reflect order in HTML
*moved .benefit-cost img to below .benefit-cost h3 to reflect order in HTML
*moved .benefit-lead h3 to below .benefit-lead to reflect order in HTML
*moved .benefit-lead img to below .benefit-lead h3 to reflect order in HTML
*moved .search-engine-optimization to below .content to refelct order in HTML
*moved .search-engine-optimization img to below .search-engine-optimization to reflect order in HTML
*moved .online-reputation-management to below p to reflect order in HTML
*moved .online-reputation-management img to below .online-reputation-management to reflect order in HTML
*moved .social-media-marketing to below .float-right to reflect order in HTML
*moved .social-media-marketing img to below .social-media-marketing to reflect order in HTML
*moved .search-engine-optimization h2 to below .float-left to reflect order in HTML
*moved .online-reputation-management h2 to below .float-right to relect order in HTML
*moved .social-media-marketing h2 to below .social-media-marketing img to reflect order in HTML
*Combined the class for seach-engine-optimization, online-reputation-management, and social-media-marketing into new class=services-info
*Combined search-engine-optimization, online-reputation-management, and *social-media-marketing h2 sections into .services-info h2 as they had the same value
*Combined search-engine-optimization, online-reputation-management, and social-media-marketing img sections into .services-info img 
