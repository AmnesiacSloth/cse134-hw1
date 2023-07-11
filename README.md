# CSE134B-SS20-HW1
# Name: Christian Velasquez
# PID: A15917590

## site deployed @ https://frolicking-naiad-e0f496.netlify.app/


Q2. Chrome DevTools - Network

1. # of requests by Content Type
   - 1 doc
   - 1 font 
   - 1 gif
   - 2 jpeg
   - 1 media
   - 1 png
   - 1 script 
   - 1 stylesheet
   - 27 svg+xml
   - 1 vnd.miscrosft (flavicon.ico)

2. Total # of Requests 
 - 37 requests

3. Total Bytes Sent
- 6.8MB transferred 

4. See waterfall screenshot in repo

Part 2

1. Am unable to navigate, page wont load after I install screen reader
2. am unable to, page wont load after I install screen reader

Part 3 
Q1
1. see ucsd screenshot in repo
2. see uci screenshot in repo
3. The UCI response HTTP header is http1.1 and additionally it requires the connection to stay alive. The UCSD http header is http2, where it is standard and required to NOT generate any connection specific metadata at the endpoint

Q2
1. screenshot
2. The nav bar doesn't show its drop down options but the overall layout and structure of the site holds with javascript disabled.
3. screenshot
4. On ucla's website the nav bar is still functional and allows for drop downs but the layout and much of the content on the website breaks without javascript

Q3
1. Yes it has a custom 404
2. https://www.csuci.edu/bruhpage
3. No it doesn't
4. https://jpcatholic.edu/buddha

Q4
1. Yes it does (screenshot)
2. No it doesn't
3. Since robots.txt doesn't bind all web crawlers to conform to their rules by defining a robots.txt you may be outlining where sensitive information might be found on your site. 

Q5
1. Google hacking database refers to a collection of search queries (aka dorks) that use google's built in advanced search querying capabilities to identify or collect insecure data from a website.
2. Since Google Bot will update or crawl most any websites, an attacker may add malicious links to their website that eventally Google Bot will traverse and create requests for
3. As a web developer we should be aware that Google Bot requests will be an eventuality and that we should valiadate them with a reverse ip search to ensure they fall within Google bots' proposed ip ranges
4. This question relates to 4 in the sense that Google Bot will abide by robots.txt therefore it is important to define any rules that we want Google Bot to abide by such as limiting the requests received from them or certain resources that we want to keep Google Bot from acessing.

Q6
1. About 5,130,000 results (0.27 seconds)
2. unable to find since i cannot page to the 500th url, only continuous scroll
3. The point of the question might be as to how google ranks pages and applies these ranking to our search query.

Q7.
1. screenshot
2. Medium probably put that information there to find curious minds intersted in digging around there site and recruit.
3. screenshot. These values might be set and used for recording traffic without identifying and saving personal information from either end point. Most of the values look hashed or dont have anything that can be readily understood just from having the data.

Q8.
1. datasetCount
2. It might be the count of the # of datasets accessed in the last 24 hrs
3. It might be more problematic in another situation where more sensitive information is logged

Q9.
1. Yes
2. Google loads in a different html file that shows previews of other content that a iphone user might readily jump to 

Q10
1. for bootstrap.min.css
x-Cache - debug response header that gives details on whether a content delivery network or the origin served your request. hit means the CDN served your request
x-content-type-options - enables or disables mimesniffing and signals that the mime type in content-type is to be followed
x-jsd-version - checks version of jsd used
x-jsd-version-type - checks if anything other than the regular distribuition is used
x-served-by - which server served your request

Q11
1. screenshot
2. Reduce unused css and enable text compression
3. sdsu scores ~15 points lower than ucsd in performance however they score much better in accesibiility, best practies, and SEO.
4. sdsu has more performance work to do

Q12.
1. https://chromestatus.com, https://github.com/mozilla/platform-status, https://developer.microsoft.com/en-us/microsoft-edge/, https://webkit.org/status/
2. Version 53 introduced shdow dom v1
3. Wednesday, August 31, 2016
4. September 2, 2023 the official release of chrome will be 15

Q13


Q14
1. This header specifies the user agent to strictly use the type specified by the content-type and avoid mime sniffing
2. Cloudflare is a company that provides networking, cloud services, security and domain registration among other things. 

Q15
1. 9 cookies
2. only a single domain of ucsd.edu is shown for these cookies
3. ucsd.edu
4. 2 cookies
5. only a single domain 
6. sdsu.edu
