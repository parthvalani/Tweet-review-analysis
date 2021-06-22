

# Tweet review analysis #



<!-- ABOUT THE PROJECT -->
## About The Project

This project mainly shows the sentimental analysis of any keyword (hashtag) that are used on the twitter in real-time. It also shows past 100 tweets of the same topic. The main thing is it can also fetch the emotion which is linked with the tweet.

### Built With

Tools and framework used in the project. Here are a few examples.
* [python](https://python.org)
* [tweepy](https://www.tweepy.org/)
* [emot](https://pypi.org/project/emot/)



<!-- GETTING STARTED -->
## Getting Started

Step by step guide of how project works

### Prerequisites

Any IDEs for python. I've used pycharm here.
* [pycharm](https://www.jetbrains.com/pycharm/download/#section=windows)


### Installation

1. Get a free API Key at [https://twitter.com/](https://twitter.com/)
2. Clone the repo
   ```sh
   git clone https://github.com/parthvalani/Tweet-review-analysis.git
   ```
3. Install python packages
   ```sh
   pip install tweepy textblob numpy matplotlib emot
   ```
4. Enter your API in `def __init__(self):`
   ```JS
   consumer_key = 'YOUR CONSUMER KEY'
   consumer_secret = 'YOUR COSUMER SECRET KEY'
   access_token = 'YOUR ACCESS TOKEN'
   access_token_secret = 'YOUR ACCESS TOKEN SECRET';
   ```



<!-- USAGE EXAMPLES -->
## Methodology

* load the data from the twitter API
* clean tweet text by removing links, special characters using simple regex statements
* separate the keyword and tweets
* take out the emotion of the tweet using emot
* get tweet sentiment using textblob
* fetch past 100 original tweets
* then, main function use all the above function to generate positive, negetive and nuetral tweets 
* visualize it in the pie chart using matplotlib


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact
Parth Valani - [@parth_valani](https://www.linkedin.com/in/parthvalani/) - parthnvalani@gmail.com

Project Link: [https://github.com/parthvalani/Tweet-review-analysis](https://github.com/parthvalani/Tweet-review-analysis/)
