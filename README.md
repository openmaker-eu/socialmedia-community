<img src="https://github.com/openmaker-eu/socialmedia/blob/master/Ekran%20Resmi%202017-01-11%2014.34.43.png" width="158">
<img src="https://github.com/openmaker-eu/socialmedia/blob/master/Boğaziçi_Üniversitesi_Logo.png" width="108">
<img src="https://github.com/openmaker-eu/socialmedia/blob/master/OpenMakerLogo.png" width="158">

OpenMaker project is a project funded by the European Commision. The project aims at fascilitating creative collaboration between makers and traditional manufacturers. As part of OpenMaker, Boğaziçi University is fetching and monitoring data from social media platforms to monitor the relevant communities, influencers, and trending topics.

#Community for a Theme
A community is a group of people who share common interests.
#Introduction:
Our aim is to detect the community (people as well as the network structure) interested to some theme. Theme examples are arduino, raspberry pi, 3d printing. We assume that a theme is described by some keywords. For example for arduino: Arduino, ... A (real/virtual) person is a member of a community for a theme; if the corresponding account meets one of the following:
shares at least one post containing one or more of the keywords,
follows one the influencers of the theme.
For the implementation we need to select a social media platform. This selection first depends on the community itself. Some communities prefers some platforms more than other. On the other hand each platform has own its data access limitations. Twitter is the most open (in terms of providing public data) among them. Therefore, we start with Twitter.

#Twitter API:
For the details see https://github.com/openmaker-eu/socialmedia/blob/master/Twitter.ipynb. Twitter allows us to listen tweets by Stream API. It is also possible to collect all the tweets of a single account and of course all the followings of that account. This means that it is possible to check the membership of an account to a community.
