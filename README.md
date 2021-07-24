## Phishing webpage detection dataset

### Note
Please cite the following work when you use this dataset for your research:
- Jehyun Lee, Pingxiao Ye, Ruofan Liu, Dinil Mon Divakaran, and Chan Mun Choon, “Building robust phishing detection system: an empirical analysis,” in NDSS MADWeb (Workshop on Measurements, Attacks, and Defenses for the Web), Feb. 2020.
Available at https://www.ndss-symposium.org/wp-content/uploads/2020/02/23007-paper.pdf


### Information
#### Data Collection 
##### Alexa 
 - Source: 
   - Alexa Top 1 Million Domains from https://ats.alexa.com/developer-guide. 
   - List in Februrary 2019.
 - Method: 
   - Start from one single main domain X from the list, get its HTML first. 
   - From that main page HTML, sample random links on the page.
   - Note that we only sample max three levels down for children of X. 
 - Collection Timeline: May 10 - Aug 5 2019 in 4 batches
 - Collection Result: 110,009 HTML

##### Phishtank
 - Source: 
   - Phishtank Feed https://phishtank.com/
 - Method: 
   - Crawl links directly
 - Collection Timeline: May 30 - July 10 2019 daily crawl
 - Collection Result: 32,159 HTML
 
 #### Features
- Features are based on these five papers

  1. X. Guang, H. Jason, P. R. Carolyn, and C. Lorrie, “Cantina+: A feature-rich machine learning framework for detecting phishing web sites,” in ACM transactions on information and system security, 2011, pp.1–28.
  2. M. Samuel, S. Kalle, S. Nidhi, and A. N, “Know your phish: Novel techniques for detecting phishing sites and their targets,” in IEEE International Conference on Distributed Computing Systems., 2016.
  3. K. Thomas, C. Grier, J. Ma, V. Paxson, and D. Song, “Design and evaluation of a real-time urlspam filtering service,” in Proceedings of the 2011 IEEE Symposium on Security and Privacy (SP), 2011, pp. 447–462.
  4. C. Whittaker, B. Ryner, and M. Nazif, “Large-scale automatic classification of phishing pages,” in Proceedings of the 2010 Network and Distributed System Security (NDSS) Symposium, 2010.
  5. L. Yukun, Y. Zhenguo, C. Xu, Y. Huaping, and L. Wenyin, “A stacking model using url and html features for phishing webpage detection,” in Future Generation Computer Systems, 2019, pp. 27–39
