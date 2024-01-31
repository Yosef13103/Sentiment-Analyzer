# Sentiment Analyzer 🚀

## Table of Contents 📋

- [Sentiment Analyzer 🚀](#sentiment-analyzer-)
  - [Table of Contents 📋](#table-of-contents-)
  - [Introduction 🌐](#introduction-)
  - [Installation ⚙️](#installation-️)
  - [Usage 🛠️](#usage-️)
  - [Contributors 👥](#contributors-)
  - [Contact 📬](#contact-)
  - [License 📄](#license-)

## Introduction 🌐

In the world of e-commerce and digital marketplaces, customer reviews play an essential role in changing the product’s reputation and manipulating customer views. These reviews heavily influence product purchasing decisions, which makes it vital to understand and improve your product based on these reviews. This presents a valuable opportunity for AI to analyze and process the vast amount of product reviews available to try and isolate the most negative and most positive things about the product. This, in turn, will help manufacturers know exactly what to focus on when improving their product.

This project, titled "Sentiment Analyzer," is a Python application that utilizes the TextBlob library to perform sentiment analysis on given text. The sentiment analysis function, `sentimentAnalyzer`, takes a string of text as input and returns whether the sentiment of the text is "positive," "negative," or "neutral" based on the polarity score calculated by TextBlob.

This algorithm is then applied to given data from Amazon Reviews. The data is first cleaned, and then the sentiment analysis function is applied to the data. The results are then analyzed and displayed in multiple graphs.

## Installation ⚙️

To install this project, simply clone the repository and run the `sentimentAnalyzer` function with a string of text as input. The function will return the sentiment of the text as a string.

## Usage 🛠️

Using a huge data collection with a bunch of customer reviews based on many different products, we decided to isolate our application to focus on a singular product: the All-New Fire HD 8 Tablet, with 8 HD Display, Wi-Fi, and 16 GB Ram. After analyzing the given data, we found the products assigned ID and created a DataFrame to represent only that product. We then cleaned the data by removing any unnecessary columns and rows, and then applied the `sentimentAnalyzer` function to the data. The results were then analyzed and displayed in multiple graphs.

This is just a showcase of the TextBlob library and its capabilities. The `sentimentAnalyzer` function can be applied to any string of text and will return the sentiment of the text as a string.

## Contributors 👥

- Mamdouh Khalaf Aldhfaeeri
- Ali Abdulelah Aldhamen
- Radwan Ali albahrani
- Yosef Mohamed Ahmed
- Abdulrahman Sultan Almutairi
- Saad Ibrahim alromaizan

## Contact 📬

- Radwan Ali albahrani
  - [Email](mailto:Radwan.Albahrani@icloud.com?subject=[GitHub]%20Sentiment%20Analyzer)
  - [LinkedIn](https://www.linkedin.com/in/radwan-albahrani-0030b8198/)
  - [GitHub](https://github.com/Radwan-Albahrani)
  - [Twitter](https://twitter.com/RadwanAlbahrani)
- Mamdouh Khalaf Aldhfaeeri
  - [Email](mailto:MamdouhKhalaf76@gmail.com?subject=[GitHub]%20Sentiment%20Analyzer)
  - [LinkedIn](https://www.linkedin.com/in/mamdouh-aldhafeeri/)
  - [GitHub](https://github.com/Mamdouh66)
  - [Twitter](https://twitter.com/MamdouhAI)
- Ali Abdulelah Aldhamen
  - [Email](mailto:ali77dhamen@hotmail.com?subject=[GitHub]%20Sentiment%20Analyzer)
  - [LinkedIn](https://www.linkedin.com/in/ali-al-dhamen-323a04144/)
  - [GitHub](https://github.com/Ali-AlDhamen)
  - [Twitter](https://twitter.com/_AliDhamen)
- Yosef Mohamed Ahmed
  - [GitHub](https://github.com/Yosef13103)
  - [LinkedIn](https://www.linkedin.com/in/yahmed131/)

## License 📄

This project is licensed under the MIT License - see the [LICENSE.md](./LICENCE.md) file for details 📄
