# An anonymized dataset of 50135 users of Medium
Identifying influential users in “cold start” scenarios, i.e., predicting whether a newly registered user or a current inactive user on an emerging OSN would become an influential one.

Licensed under [Creative Commons Attribution Share Alike 4.0](http://choosealicense.com/licenses/cc-by-sa-4.0/).



## File 
you can download the [medium_open_dataset.csv](https://raw.githubusercontent.com/willingnesshxl/medium-open-data/master/medium_open_dataset.csv).
</br>
Each line contains a user’s information, including his Twitter information and Medium information.
<br><br>

## Feature discription
* Index feature<br>
First column: Index of this user;<br>
mid: Anonymous medium userid;<br>
tid: Anonymous Twitter userid;<br>
<br><br>
* Twitter feature:<br>
bio_words_num: Number of words of the user’s biography in Twitter;<br>
has_location: Weather the user add location in his/her Twitter;<br>
utc_offset: UTC offset in Twitter;<br>
has_extended_profile: Whether the user add other homepage;<br>
t_account_age: Age of the account in Twitter;<br>
default_profile_img: Whether the user has changed the default profile image in Twitter;<br>
has_profile_bg_img: Whether the user has changed the default profile background image in Twitter; <br>
verified: Weather the user has verified by Twitter;<br>
follower_count: Number of follower in Twitter;<br>
following_count: Number of following in Twitter;<br>
total_tweets_num: Total tweets number in Twitter;<br>
geo_enabled: Weather the user has geo tags in Twitter;<br>
listed_count: Number of lists subscribed to in Twitter;<br>
t_num: Number of original tweets in Twitter;<br>
rt_num: Number of retweets in Twitter;<br>
t_favourite: Number of “likes” received in Twitter;<br>
t_rt: Number of “retweet” of original tweets in Twitter;<br>
avg_favourite: Average number of “likes” received of original tweets in Twitter;<br>
avg_rt: Average number of “retweet” of original tweets in Twitter;<br>
<br><br>
* Medium feature:<br>
follower: Number of follower in Medium;<br>
following: Number of following in Medium;<br>
latest_num: Number of the latest stories published by the user in Medium;<br>
bio_words:Number of words of the user’s biography in Medium;<br>
account_age:Age of the account in Medium;<br>
has_facebook: Weather the user has link to Facebook account in Medium;<br>
has_p_img: Weather the user has profile image in Medium;<br>
has_pb_img: Weather the user has background image in Medium;<br>
interest_tag_num: Number of interesting tags in Medium;<br>
claps_num: Number of stories the user claps for in Medium; <br>

## BibTex Entry
```
@inproceedings{Gong_Medium18,
	author = {Qingyuan Gong, Yang Chen, Xinlei He, Fei Li, Yu Xiao, Pan Hui, Xin Wang and Xiaoming Fu},
	title = {Identification of Influential Users in Emerging Online Social Networks Using Cross-Site Linking.}},
	booktitle = {Proc. of the 13th CCF Chinese Conference on Computer Supported Cooperative Work (ChineseCSCW’18)},
	year = {2018},
} 
