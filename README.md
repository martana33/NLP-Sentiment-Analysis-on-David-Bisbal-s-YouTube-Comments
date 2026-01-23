# NLP-Sentiment-Analysis-on-David-Bisbal-s-YouTube-Comments
This project involves scraping YouTube comments via an API and performing sentiment analysis using a dictionary-based approach with natural language processing (NLP) techniques. The goal is to analyze the language and sentiment expressed in comments from David Bisbal’s listeners.

**Where the Data Comes From?**

I used a file called ComStat_DavidBisbalVEVO.csv containing comments from his YouTube channel.
To extract the comments, I copied the comment column and saved it in Notepad++ as com_david_b.txt.
In total, there are **3,040** comments.

**How We Analyzed the Sentiments?**

To figure out if comments were positive, negative, or neutral, I used a word dictionary that gives each word a score from **-5 to 5**:

- Negative values → negative feelings (criticism or discontent)
- Values close to 0 → neutral feelings (ordinary comments without strong emotion)
- Positive values → positive feelings (praise or excitement)

**What We Found**

After analyzing the comments, here are the main results:
- **Average sentiment**: 0.5985

Most comments are slightly positive. Not extremely enthusiastic, but still showing a generally good vibe.
- **Most negative comment**: -1.5652

A few fans left critical comments, but nothing too harsh.
- **Most positive comment**: 3.9686

Some fans expressed very positive feelings, showing a lot of love for the singer.

**Conclusion**

Overall, the comments on David Bisbal’s YouTube channel are mostly positive. This shows that, while there are occasional criticisms, most fans enjoy his music and appreciate him as an artist.

**Business insight**

This analysis suggests that David Bisbal’s audience is generally happy and engaged, which could be valuable for marketing, fan engagement strategies, or promoting new releases—knowing that his fan base responds positively gives confidence for future campaigns.
