# recentlyPlayedOnSpotify
Uses Spotify's RESTful API to create a playlist of you 50 most recently played songs.



In the secrets.py file the user needs to add some data.



spotify_user_id = Your user ID

base_64 = The base 64 encryption of you Client ID and Client secret in the format -> Client ID:Client Secret

Watch the following YouTuve video for an explanation of how to get your refresh token, sptify_token and your base_64.

youtube.com/watch?v=-FsFT6OwE1A&list=PLrp-hldHDJiQLs993k8VPYrDNDDpumDR6&index=4

Note:

When inputing the scopre of your code, you will need to add the scope "user-read-recently-played".
