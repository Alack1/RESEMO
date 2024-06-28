# RESEMO: A Benchmark Chinese Dataset for Studying Responsive Emotion from Social Media Content

🔥**Note**: If you need to use our dataset, please send an email to zhangm@mail.ustc.edu.cn to obtain it.

## Dataset: RESEMO
![](image.png)

- **Overview**: <br>
we propose a Chinese dataset named RESEMO for responsive emotion analysis, including 3813 posts with 68,781 comments collected from Weibo, the largest social media platform in China. RESEMO contains three types of human annotations with
respect to responsive emotions, namely, responsive relationship, responsive emotion cause, and responsive emotion category.
- **Emotion Category**: <br>
Our dataset is annotated with 16 emotion categories, including 6 positive emotions, 9 negative emotions, and 1 neutral emotion. The details are shown in the following table:
![](image2.png)
- **Responsive Relationship**: <br>
The responsive relationship label indicates which preceding comments or the blog post itself the current comment is responding to, allowing for the possibility of a one-to-many relationship.
- **Responsive Emotion Cause**: <br>
The responsive emotion cause label identifies a specific word-level text span that acts as the reason
behind the conveyed emotion in the current comment. Given that a user’s responsive emotion stems
from interactions with other users, it is anticipated
that this emotion cause originates from the blog
posts or comments to which the current comment
is responding. Therefore, we only need to annotate
word-level text spans as emotion causes within sentences with such response relationships.




