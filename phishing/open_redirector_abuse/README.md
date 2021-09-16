# Open Redirector Abuse

It’s no surprise that phishing continues to be the main access vector when targeting everything from small to large 
businesses. Our team has continued the research that [Microsoft](https://www.microsoft.com/security/blog/2021/08/26/widespread-credential-phishing-campaign-abuses-open-redirector-links/) has published in order to further highlight some 
behavior we’ve been observing in our customer environments. The purpose of this work is to share the results of what 
IronNet has seen, and to allow others to build on this research. We’ve divided our research into two:
* Phishing domains abusing open redirectors in conjunction with reCAPTCHA
* Phishing domains serving ExRobotos phish kit and abusing open redirectors

Full research on abusing open redirectors in conjunction with reCAPTCHA: [Blog Post](https://www.ironnet.com/blog/gone-phishing)

Full research on phishing domains serving ExRobotos phish kit and abusing open redirectors: [Blog Post](https://www.ironnet.com/blog/phishing-again-prolific-use-of-ex-robotos-phishing-kit)


Files                                                                                                         | Description
--------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------
[`urlscan_notebook`](./urlscan_notebook.ipynb)                                                                | Jupyter notebook for gathering final destination domains
[`phish_domains_abusing_reCAPTCHA.txt`](./phish_domains_abusing_recaptcha.txt)                                | Final destination domains abusing reCAPTCHA and hosting phish kit
[`phish_domains_abusing_reCAPTCHA_with_datetime.csv`](./phish_domains_abusing_recaptcha_with_datetime.csv)    | Final destination domains abusing reCAPTCHA and hosting phish kit with datetime
[`phish_domains_exrobotos_group_one.txt`](./phish_domains_exrobotos_group_one.txt)                            | Final destination domains serving ExRobotos phish kit (group 1)
[`phish_domains_exrobotos_group_one_with_datetime.csv`](./phish_domains_exrobotos_group_one_with_datetime.csv)| Final destination domains serving ExRobotos phish kit (group 1) with datetime
[`phish_domains_exrobotos_group_two.txt`](./phish_domains_exrobotos_group_two.txt)                            | Final destination domains serving ExRobotos phish kit (group 2)
[`phish_domains_exrobotos_group_two_with_datetime.csv`](./phish_domains_exrobotos_group_two_with_datetime.csv)| Final destination domains serving ExRobotos phish kit (group 2) with datetime


### Warning :warning:
Some domains used to host the phishing kit are compromised domains. Use at your own risk when implementing block rules.


### Acknowledgments
* [Microsoft 365 Defender Threat Intelligence Team](https://www.microsoft.com/security/blog/2021/08/26/widespread-credential-phishing-campaign-abuses-open-redirector-links/)
* [Jake | JCyberSec_](https://twitter.com/JCyberSec_)
