# Gyft
## Empowering every community and small businesses to be financially agile.
#### Created by Achilles Dabrowski, Alex Xu, Franklin Boampong, and Steven Cheng
#### Hack The Northeast 2020

## Purpose and Value:

Gyft is a platform that empowers communities by connecting local businesses with community members and potential customers. It allows businesses to start selling online Gift Card/Certificates for their business quickly, intuitively, and affordably, even without past experience. 

Gyft enables small businesses to be financially agile during tumultuous times of crisis (such as during COVID-19). The ability to generate revenue even during shutdowns has been reserved for large, corporate businesses in the past. Gyft seeks to change that. Moreover, Gyft continues to add value to businesses beyond these times by generating revenue, attracting new customers, strengthening customer loyalty, and boosting branding.

Gyft also empowers community members to continue to patronize and support their local businesses, even when there is a temporary shutdown due to coronavirus. It also draws family and friends closer together through gifts for special occasions.

## Pricing:

Revenue will be generated by charging a one-time 3% service fee on every gift card purchased. In other words, if a customer purchases a $50.00 gift card, the business will receive $48.50. There are no monthly fees or other charges.

Our fees are highly competitive compared to a physical gift card program. It can cost businesses $300-$400 for gift card software, and over $2 per gift card. Transaction fees and lengthy, restrictive contracts add even more costs [1].

## Marketing and Audience
Currently, there is no alternative solution on the market that makes it easy and affordable for small business owners to create their own gift card program targeting their local communities. Furthermore, it is difficult for community members to discover small businesses in their area that need their support. Gyft fills in this gap in the market.

Gyft’s target audience are small businesses and community members. Especially during times of crisis and shutdowns (COVID-19), there have been calls by leaders and the media to purchase gift cards to support local businesses [4]. However setting up a gift card program is a long and tedious process.

Our marketing strategy includes advertising through online websites targeted at small business owners and COVID-19 related content. In addition, there will be social media advertisements to users in areas where there are small businesses in need of support. Finally, small businesses will generate awareness of their gift cards on the Gyft platform for themselves, which adds to our marketing efforts.

## Market and Financial Potential

According to the US Small Business Administration, there are 30.7 million small businesses in the US in 2019 [2]. Of these, over 2.6 million are in Retail Trade, and over 0.9 million are in the Accomodation and Food Services Industry. These two industries are examined because they are highly suitable for the Gyft platform. Small businesses in these industries generate more than 345 billion dollars of profit annually [2]. Gyft seeks to absorb some of this revenue, and generate additional revenue streams beyond existing in-person channels. In 2016, consumers spent 27.5 billion dollars on gift cards during the holiday season alone [3]. Gyft will tap into this market by providing consumers an alternative to gift cards that are dominated by large, corporate chains.

## Technology:

The Gyft platform consists of mobile applications (Android and iOS) built using Flutter and Firebase/Google Cloud Services. In developing the mobile application, we also used Figma for wireframing.

## GitHub Repository Breakdown
The Github repository is separated into two Flutter apps.
- htn2020: This is the Flutter app with functionalities such as Log In, Sign Up/Register, and Querying data from the Firebase. Essentially, this is the backend component of the Flutter app. This is prototyped on Android (as half of our team used Android simulators).
- gyft-1: This is the Flutter app with the UI interface coded up as seen from the Figma wireframe. Functionalities include navigation/routing, buttons, and input data. This is prototyped on iOS.

## Challenges we ran into
Challenges we ran into fell into two large groups:
1. Unfamiliarity with the codebase: For all of the members, this is the first time developing with Flutter, as such, it took some time to get used to the structure of program and to implement the features we wanted to create.
2. Compatibility issues: Because half of our group used Android and the other half used iOS, we were unable to combine the UI interface (coded in iOS) and backend functionalities (coded in Android). As such, we ended with two different codebases with not enough time to merge them together.

## Accomplishments that we're proud of and what we learned
We are very proud of being able to working together and delegate different tasks efficiently. Even though the codebase was new to us, we were able to create a coherent project and pitch it effectively. Through this endeavor, we learned a lot about mobile development, both in terms of creating a captivating UI and interacting with servers and databases.

## What's next for Gyft
For the next steps, we hope to merge functionality with UI for our app and further hone the small mistakes that still exists in our current iteration. We also want to market our product to investors and consumers so that we are able to empower every community and small businesses to be financially agile.

## Sources:
[1]https://www.costowl.com/b2b/gift-card-custom-program-cost.html#:~:text=Depending%20on%20how%20many%20gift,%24300%20to%20%24400%20per%20location.
[2]https://cdn.advocacy.sba.gov/wp-content/uploads/2019/04/23142719/2019-Small-Business-Profiles-US.pdf
[3]https://www.softwareadvice.com/resources/gift-cards-for-small-business/#holiday
[4]https://www.npr.org/2020/03/20/818797729/how-buying-a-gift-card-can-help-a-small-business
