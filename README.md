# Survey-insights

## `Description`
in these survey the focused in classifying people who are being asked into groups like based on alot of features like **gander,nationality,Religion**
and more other features even **race and zodiac signs** and then ask them 5 main questions for the survey:
* What do you think when an influencer is obviously selling a product?
* What social platform has influenced your online shopping most?
* What is the most important trait when defining an influencer?
* Who are your favorite people to follow online?
* Does it annoy you when popular social media accounts endorse products or services?
* What do you consider an influencer?


with this so many groups it will be hard to access all this information 
<br>
**`Goal`is to build an interactive dashboard to accessing the information and insights of the survey more easily**
<br>
with a small piece of code with python splited the qusitions info 5 data farmes each one have a qusiton of the survey

``` python 
influencer_seller=df[df['Question'] == 'What do you think when an influencer is obviously selling a product?']
online_shoping_influencer=df[df['Question'] == 'What social platform has influenced your online shopping most?' ]
defining_a_influencer=df[df['Question'] == 'What is the most important trait when defining an influencer?' ]
favorite_people=df[df['Question'] == 'Who are your favorite people to follow online?' ]
Churn_from_ads=df[df['Question'] == 'Does it annoy you when popular social media accounts endorse products or services?']

#Save to CSV
influencer_seller.to_csv('E:\\py\\Servay\\influencer_seller.csv',index=False)
online_shoping_influencer.to_csv('E:\\py\\Servay\\online_shoping_influencer.csv',index=False)
defining_a_influencer.to_csv('E:\\py\\Servay\\defining_a_influencer.csv',index=False)
favorite_people.to_csv('E:\\py\\Servay\\favorite_people.csv',index=False)
Churn_from_ads.to_csv('E:\\py\\Servay\\Churn_from_ads.csv',index=False)
```
<br>

## `Dashboard`
<p align="center">
  <img src="https://github.com/Abdelrhman-Sadek/Survey-insights/blob/main/Pics/Screenshot%20(522).png" />
  <img src="https://github.com/Abdelrhman-Sadek/Survey-insights/blob/main/Pics/Screenshot%20(523).png" />
  <img src="https://github.com/Abdelrhman-Sadek/Survey-insights/blob/main/Pics/Screenshot%20(525).png" />
  <img src="https://github.com/Abdelrhman-Sadek/Survey-insights/blob/main/Pics/Screenshot%20(526).png" />
  <img src="https://github.com/Abdelrhman-Sadek/Survey-insights/blob/main/Pics/Screenshot%20(521).png" />
  </p>

> **Note**
> Groups that have less than 20 person are exterminated
> Web and Mobile groups were also removed because they don't make sense to be measured with 
