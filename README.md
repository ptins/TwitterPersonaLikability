## TweekOrTweet

SocialSensing Project

The goal of this project is to determine an individual's 'likability' by perusing their social media, namely their Twitter account.

## Steps

### Step 1 - Determine How to Calculate Likability

Likability goes two ways: what you broadcast, and what others broadcoast about you.

The first part is what you broadcast directly, namely tweets, and for each tweet we have:
- [ ] 'created_at': 'Fri Dec 01 13:26:33 +0000 2017'
- [ ] 'text': 'Your funniest #DecorationDisaster tweets! https://t.co/0s88ssjFYQ #FallonTonight'
- [ ] 'entities': {See Below}

'entities': {
    'hashtags': [
         {'text': 'DecorationDisaster', 'indices': [14, 33]}, 
         {'text': 'FallonTonight', 'indices': [66, 80]}
    ], 
    'symbols': [],
    'user_mentions': [], 
    'urls': [
         {'url': 'https://t.co/0s88ssjFYQ', 
         'expanded_url': 'https://www.youtube.com/watch?v=9k5y_aO-8Jo',
         'display_url': 'youtube.com/watch?v=9k5y_a…', 
         'indices': [42, 65]}
    ]
}

Additionally, your profile is also something you broadcast.
- [ ] 'location': 'New York, New York'
- [ ] 'description': 'astrophysicist'
- [ ] 'followers_count': 50486064
- [ ] 'friends_count': 7800
- [ ] 'listed_count': 68034
- [ ] 'favourites_count': 69
- [ ] 'statuses_count': 10474
- [ ] 'profile_image_url', 'profile_background_url', ...  


## Progress