- User Table:
  - Vader
  - Leia 
  - Obi-Wan
    
- Tweet Table:
  -Two tweets are added:
    - Vader's tweet :" I find your lack of faith disturbing"
    - Obi-Wan's tweet: "The Force will be withyou.Always."
  -Comment
    -Leia comments on Obi-Wan’s tweet: “Help me, Obi-Wan Kenobi. You’re my only hope.”
    -**In Tweet table comments are identified by OriginalTweetID.If it is NULL it means it is not comment but if OriginalTweetId is provided it means TextualContent is a comment.**
      
- Like Table:
  - Leia likes Vader's tweet.
    
- Retweet Table:
  -Obi-Wan retweets Vader's tweet.
  
- Follow Table:
 - Leia follows Vader
 - Vader follows Obi-Wan.
