```JavaScript
COLUMN NAME          COUNT          TYPE      DESCRIPTION
username               999 non-null object    username of the account
isBrand                999 non-null bool      True / False if brand or not. (Label that you need to predict)
biography              946 non-null object    biography of the user
mediaCount             993 non-null float64   number of media the user has
cityId                 641 non-null float64   city id of the user's location
latitude               637 non-null float64   latitude value of the user's location
longitude              642 non-null float64   longitude value of the user's location
zip                    203 non-null object    zip of the user's location
contactPhoneNumber     414 non-null float64   phone number of the user   
followingCount         993 non-null float64   number of accounts user is following
followerCount          993 non-null float64   number of accounts following this user
usertagsCount          993 non-null float64   number of accounts tagged by user across his images
isBusiness             806 non-null object    True / False if the account is a 'Business' account
externalUrl            584 non-null object    link to website added by user
category               642 non-null object    business account category
geoMediaCount          993 non-null float64   number of locations tagged by user across images
shoppablePostsCount    993 non-null float64   number of posts linked to Shopify for in app purchasing
followingTagCount      993 non-null float64   number of hashtags the user is following
picture                966 non-null object    url of profile picture
imageLabels            999 non-null object    image labels derived from profile picture
hasEmail               999 non-null bool      True / False if user has email 
```

```JavaScript
// Sample row from data.csv
{
    "biography": "Jalan Sawahan No. 60 Padang (Dekat Pertamina Sawahan) —— > 08.00 - 22.00",
    "category": "",
    "cityId": "",
    "contactPhoneNumber": "",
    "externalUrl": "",
    "followerCount": 265.0,
    "followingCount": 17.0,
    "followingTagCount": 0.0,
    "geoMediaCount": 0.0,
    "hasEmail": False,
    "imageLabels": [("text", 0.92769134, 0.92769134), ("product", 0.85267156, 0.85267156), ("logo", 0.823976, 0.823976), ("product", 0.79528636, 0.79528636), ("font", 0.7606693, 0.7606693), ("brand", 0.6831392, 0.6831392), ("line", 0.6778981, 0.6778981), ("area", 0.6720096, 0.6720096), ("signage", 0.6699288000000001, 0.6699288000000001), ("sign", 0.57547855, 0.57547855)],
    "isBusiness": False,
    "latitude": "",
    "longitude": "",
    "mediaCount": 16.0,
    "picture": "https://scontent-iad3-1.cdninstagram.com/vp/a7ca7ad444218f958e66251b49ffffc8/5BEDDED1/t51.2885-19/26361473_1902711543375186_5050501572929257472_n.jpg",
    "shoppablePostsCount": 0.0,
    "username": "helthematic",
    "usertagsCount": 3.0,
    "zip": ""
}
```
