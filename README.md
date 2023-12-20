# Statistical analysis of the SgML Speech Reception Threshold test

This code performs statistical analysis on data collected from the Speech Reception Threshold (SRT) Test conducted in the Malay language. 

❗ The dataset is part of the Development of Singapore Malay Speech Audiometry research project, conducted by the Otolaryngology Department of the National University of Singapore.

📰 In this research study, speech reception threshold test (SRT) scores and pure tone average scores were obtained from a group of native Singapore Malay speakers. Subjects were given two test lists, one with a familiarisation of word lists condition where subjects were familiarised with the list of words before testing, and another test list without a familiarisation condition. A retest was also administered to each subject. 

📎 The raw dataset contained each subject's pure tone average (PTA), obtained from a pure tone audiometry hearing test, followed by their SRT test lists, and the corresponding SRT test scores. The score difference between PTA and SRT scores were also obtained in the raw dataset. 

### The goal of this code: 🎯
The goal of this code is to validate the SRT test lists by performing statistical tests to determine any statistically significant differences between PTA and SRT scores. 

### Statistical analysis conducted: 📈
1. **Pearson's correlation coefficient:** :To determine the degree of correlation between PTA and SRT with and without familiarisation, by obtaining the pearson's correlation coefficients.
2. **Scatterplots of PTA and SRT:** 📊 To visualise the relationship between SRT and PTA with and without familiarisation.
3. **Paired t-tests:** 5 different paired t-tests were conducted to determine if there are any statistically significant differences between the two specified variables. Here is a list of the paired t-tests conducted:
   - **PTA and SRT** (with familiarisation, test condition)
   - **PTA and SRT** (without familiarisation, test condition)
   - **SRT** (w/ familiarisation) **and SRT** (w/o familiarisation) - Test condition
   - **SRT test and retest** (w/familiarisation)
   - **SRT test and retest** (w/o familiarisation)
  
For questions or issues related to this code, feel free to contact Jannah at nuruljannahalias@outlook.com
