---
layout: page
title: Data Science
permalink: /data_science/
---

## Fake News Detector

During my 5 week fellowship at <a href="https://www.correlation-one.com/ds4a">Data Science for All Women's Summit</a> (Fall 2020), my teammates and I built a fake news detector using various natural language processing tools such as embeddings, RNN, BERT, and transfer learning. We performed careful preprocessing to remove biases in the dataset, and we used a model interpretability tool called LIME to identify points of improvement for our model.

<iframe src="//www.slideshare.net/slideshow/embed_code/key/f5TLIG5Ag7wuGg" width="595" height="400" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe>

## Hospital bed shortage prediction due to COVID-19

Check out this <a href="https://covid19-hospital.herokuapp.com/">COVID-19 hospital app</a> I built!  

The app predicts the dates during which hospitals in the US are expected to experience bed shortage due to COVID-19. 

![_config.yml]({{ site.baseurl }}/images/app_image.png){:height="300px"}

The app uses COVID-19 data from the <a href="https://github.com/CSSEGISandData/COVID-19">Johns Hopkins CSSE repository</a> to fit a SIR model. It also uses state-level demographic information and hospital capacity to predict the number of COVID-19 patients that will require hospital and ICU beds. 

For details on the model, please read this <a href="https://medium.com/@irishryoon/predicting-hospital-bed-shortage-in-the-us-due-to-covid-19-2d860ecdaba2">medium post.</a> 

You can play around with the <a href="https://gist.github.com/irishryoon/fe2c769ccca1028dbda2e4a5f060fb7e"> code</a> on Google Colab.


*Note: The app uses data that was available on March 26, 2020*
