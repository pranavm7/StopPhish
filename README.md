# StopPhish
Email Protection-as-a-Service

> [!NOTE]
> This project is under development and may change as development progresses. Kindly be patient with the same! :)

# Why  

Phishing is a leading vector for cybersecurity attacks globally.(Fig 1) Email phishing is a low-cost attack vector that does not require a high level of expertise or a large amount of time to be invested in order to be created and sent.

<a href="https://www.statista.com/statistics/1406484/cyber-attacks-experienced-by-us-companies/" rel="nofollow"><img src="https://www.statista.com/graphic/1/1406484/cyber-attacks-experienced-by-us-companies.jpg" alt="Statistic: Primary cause of cyber attacks encountered by companies in the United States in 2022 | Statista" style="width: 100%; height: auto !important; max-width:1000px;-ms-interpolation-mode: bicubic;"/></a><br />Figure 1: Root cause of cyber attacks experienced by US companies Source:<a href="https://www.statista.com" rel="nofollow">Statista</a>

Additionally, there has been an exponential increase in phishing domains registered in the last 4 years across the internet. (Fig 2) The alarming rate of increase in the phishing domains is indicative of greater efforts taken by potential bad-actors towards improving phishing attacks.

<a href="https://www.statista.com/statistics/266155/number-of-phishing-domain-names-worldwide/" rel="nofollow"><img src="https://www.statista.com/graphic/1/266155/number-of-phishing-domain-names-worldwide.jpg" alt="Statistic: Number of unique phishing sites detected worldwide from 3rd quarter 2013 to 34th quarter 2022 | Statista" style="width: 100%; height: auto !important; max-width:1000px;-ms-interpolation-mode: bicubic;"/></a><br />Number of global phishing sites Q3 2013- Q4 2022  Source:<a href="https://www.statista.com" rel="nofollow">Statista</a>

# What

The current project hypothesis is to leverage Machine Learning to be able to classify email-based phishing attempts in order to protect the online population at-scale.  

# How  

The goal is to create a LLM that can classify the contents of an email as likely to be a phishing attempt, additionally the links within the email as well as the metadata would be taken into consideration in order to provide a holistic approach towards the evaluation of the legitimacy of an email.
