# Open Redirector Abuse

It’s no surprise that phishing continues to be the main access vector when targeting everything from small to large 
businesses. Our team has continued the research that [Microsoft](https://www.microsoft.com/security/blog/2021/08/26/widespread-credential-phishing-campaign-abuses-open-redirector-links/) has published in order to further highlight some 
behavior we’ve been observing in our customer environments. The purpose of this work is to share the results of what 
IronNet has seen, and to allow others to build on this research. We’ve divided our research into three groups:
* Customer Relationship Management (CRM) platforms allowing open redirects
* Compromised websites redirecting to reCAPTCHA
* Random reCAPTCHAs

Full research can be found here: [Blog Post]()

Files                                                                   | Description
------------------------------------------------------------------------|-----------------------------------------------------------
[`urlscan_notebook`](./urlscan_notebook.ipynb)                          | Jupyter notebook for gathering final destination domains
[`phish_domains.txt`](./phish_domains.txt)                              | Final destination domains hosting phishing kit
[`phish_domains_with_datetime.csv`](./phish_domains_with_datetime.csv)  | Final destination domains hosting phishing kit with datetime

