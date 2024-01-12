# The Geography of Information Diffusion in Online Discourse on Europe and Migration

This repository contains the data released for the paper:

 **The Geography of Information Diffusion in Online Discourse on Europe and Migration**. 

Elisa Leonardelli and Sara Tonelli. 2024.

Accepted in *Proceedings of the International AAAI Conference on Web and Social Media. 2024*, Buffalo, NY, United States. 

Paper available at [[paper]](link arxiv)


## Abstract

*The online diffusion of information related to Europe and migration has been little investigated from an external point of view. However, this is a very relevant topic, especially if users have had no direct contact with Europe and its perception depends solely on information retrieved online. 
In this work we analyse the information  circulating online about Europe and migration after retrieving a large amount of data from social media (Twitter), to gain new insights into topics, magnitude, and dynamics of their diffusion. We combine retweets and hashtags network analysis with geolocation of users, linking thus data to geography and allowing analysis from an “outside Europe” perspective, with a special focus on Africa. We also introduce a novel approach based on cross-lingual quotes, i.e. when content in a language is commented and retweeted in another language, assuming these interactions are a proxy for connections between very distant communities. 
Results show how the majority of online discussions occurs at a national level, especially when discussing migration. Language (English) is pivotal for information to become transnational and reach far. Transnational information flow is strongly unbalanced, with content mainly produced in Europe and amplified outside. Conversely Europe-based accounts tend to be self-referential when they discuss migration-related topics. 
Football is the most exported topic from Europe worldwide. Moreover, important nodes in the communities discussing migration-related topics include  accounts of official institutions and international agencies, together with journalists, news, commentators and activists.*

## Data Release
The data released with the current paper contains only the information necessary to replicate our study, without the possibility to retrieve the original data. Each tweet is represented as a (randomly assigned) ID, the tweet language, the user nation, the contained hashtags, the user ID (randomly assigned) and the retweets/quotes ID (randomly assigned). The textual content has been removed together with the real user names. All the files released are contained in the folder "Data" of this repository, except for # The Geography of Information Diffusion in Online Discourse on Europe and Migration

This repository contains the data released for the paper:

 **The Geography of Information Diffusion in Online Discourse on Europe and Migration**. 

Elisa Leonardelli and Sara Tonelli. 2024.

Accepted in *Proceedings of the International AAAI Conference on Web and Social Media. 2024*, Buffalo, NY, United States. 

Paper available at [[paper]](link arxiv)


## Abstract

*The online diffusion of information related to Europe and migration has been little investigated from an external point of view. However, this is a very relevant topic, especially if users have had no direct contact with Europe and its perception depends solely on information retrieved online. 
In this work we analyse the information  circulating online about Europe and migration after retrieving a large amount of data from social media (Twitter), to gain new insights into topics, magnitude, and dynamics of their diffusion. We combine retweets and hashtags network analysis with geolocation of users, linking thus data to geography and allowing analysis from an “outside Europe” perspective, with a special focus on Africa. We also introduce a novel approach based on cross-lingual quotes, i.e. when content in a language is commented and retweeted in another language, assuming these interactions are a proxy for connections between very distant communities. 
Results show how the majority of online discussions occurs at a national level, especially when discussing migration. Language (English) is pivotal for information to become transnational and reach far. Transnational information flow is strongly unbalanced, with content mainly produced in Europe and amplified outside. Conversely Europe-based accounts tend to be self-referential when they discuss migration-related topics. 
Football is the most exported topic from Europe worldwide. Moreover, important nodes in the communities discussing migration-related topics include  accounts of official institutions and international agencies, together with journalists, news, commentators and activists.*

## Data Release
The data released with the current paper contains only the information necessary to replicate our study, without the possibility to retrieve the original data. Each tweet is represented as a (randomly assigned) ID, the tweet language, the user nation, the contained hashtags, the user ID (randomly assigned) and the retweets/quotes ID (randomly assigned). The textual content has been removed together with the real user names. Different files are released in order to reproduce the different results. All the files released are contained in the folder "Data", except for the file related to results of Section 3 which exceeded size limitations (~2Gb) and is thus available upon request to the authors. In the following a brief description of the data released is given.

 
- ### DataSection2_pt1.tsv 
This file contains all the users that have been localized as described in section 2.3. 
Columns are:
```
userID, assigned_state
```

- ### DataSection2_pt2.tsv: 
This file contains the list of location manually evaluated (section 2.3, paragraph "Evaluation of the localization procedure").

Columns are:
```
location, assigned_state, annotation
```

- ### DataSection3.tsv
This file contains the information necessary to reproduce results of section 3. Given size limitations of this file (~2 Gb), the file is available upon request to the authors.

Columns are:
```
tweetID, retweetID, userID, retweet_userID, lang keyword_retrieved
```
- ### DataSection4.tsv
This file contains the information necessary to reproduce results of section 4 ("Exchanges between Africa and Europe").

Columns are:
```
tweetID, userID, lang, retweetID, retweet_userID, hashtags
```
- ### DataSection5.tsv
This file contains the information necessary to reproduce results of section 5 ("Cross-lingual outreach").

Columns are:
```
tweetID, userID, lang, quoteID, quote_userID, quote_lang, hashtags
``` which exceeded size limitations and is thus available upon request to the authors. In the following a brief description of the data released is given.

 
- ### DataSection2_pt1.tsv 
This file contains all the users that have been localized as described in section 2.3. 
Columns are:
```
userID, assigned_state
```

- ### DataSection2_pt2.tsv: 
This file contains the list of location manually evaluated (section 2.3, paragraph "Evaluation of the localization procedure").

Columns are:
```
location, assigned_state, annotation
```

- ### DataSection3.tsv
This file contains the information necessary to reproduce results of section 3. Given size limitations of this file (~2 Gb), the file is available upon request to the authors.

Columns are:
```
tweetID, retweetID, userID, retweet_userID, lang keyword_retrieved
```
- ### DataSection4.tsv
This file contains the information necessary to reproduce results of section 4 ("Exchanges between Africa and Europe").

Columns are:
```
tweetID, userID, lang, retweetID, retweet_userID, hashtags
```
- ### DataSection5.tsv
This file contains the information necessary to reproduce results of section 5 ("Cross-lingual outreach").

Columns are:
```
tweetID, userID, lang, quoteID, quote_userID, quote_lang, hashtags
```
