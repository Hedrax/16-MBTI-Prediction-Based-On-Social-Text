# 16 MBTI Prediction Based On Social Text
 The Use Of Classical Classification to Distinguish between 16 MBTI given a vectorized text using CBOW, BERT Models vs Classification using The LSTM model

## Project's KeyPoints
* LSTM Model
* BERT Model
* CBOW Model
* MBTI Classification
  
## Abstract of The Experiment
our primary objective was to develop a classification
framework for the Meyers-Briggs Type Indicator (MBTI) based on social media
posts. We adopted a dual-pronged approach to address this challenge. Initially,
we employed a Long Short-Term Memory (LSTM) neural network model to categorize vectorized text into one of the 16 MBTI types. Subsequently, we took a
dimensionality reduction approach, breaking down the 16 MBTI categories into
their 4 fundamental dimensions that define each unique personality. We then
applied traditional classification techniques to the vectorized text outputs from
two Natural Language Processing (NLP) models, namely BERT and CBOW.
In the second phase of our approach, we leveraged a set of six distinct models to optimize our classification results. This comprehensive strategy allowed us
to conduct a thorough and accurate comparative analysis of the Vectors produced by the BERT and CBOW models. Our findings contribute to a nuanced 
understanding of the effectiveness of different NLP models in the context of MBTI classification, paving the way for enhanced accuracy and insights into personality
Predictions based on social media content

## Results
### CBOW
<table>
  <tr>
    <td align="center">Model</td>
     <td align="center">I/E</td>
     <td align="center">N/S</td>
     <td align="center">T/F</td>
     <td align="center">J/P</td>
     <td align="center">AVG</td>
  </tr>
  <tr>
    <td align="center">Logistic Regression</td>
     <td align="center">0.72</td>
     <td align="center">0.757</td>
     <td align="center">0.8315</td>
     <td align="center">0.6724</td>
     <td align="center">0.7452</td>
  </tr>
  <tr>
    <td align="center">SVC Accuracy</td>
     <td align="center">0.7342</td>
     <td align="center">0.7834</td>
     <td align="center">0.8424</td>
     <td align="center">0.6858</td>
     <td align="center">0.7614</td>
  </tr>
  <tr>
    <td align="center">SGD Classifier</td>
     <td align="center">0.691</td>
     <td align="center">0.764</td>
     <td align="center">0.8199</td>
     <td align="center">0.6538</td>
     <td align="center">0.7321</td>
  </tr>
  <tr>
    <td align="center">Random Forest</td>
     <td align="center">0.6819</td>
     <td align="center">0.7347</td>
     <td align="center">0.8007</td>
     <td align="center">0.6512</td>
     <td align="center">0.7171</td>
  </tr>
  <tr>
    <td align="center">XGBoost</td>
     <td align="center">0.7104</td>
     <td align="center">0.7672</td>
     <td align="center">0.8192</td>
     <td align="center">0.6664</td>
     <td align="center">0.7408</td>
  </tr>
  <tr>
    <td align="center">CatBoost</td>
     <td align="center">0.7297</td>
     <td align="center">0.786</td>
     <td align="center">0.8370</td>
     <td align="center">0.6852</td>
     <td align="center">0.7594</td>
  </tr>
</table>

### BERT
<table>
  <tr>
    <td align="center">Model</td>
     <td align="center">I/E</td>
     <td align="center">N/S</td>
     <td align="center">T/F</td>
     <td align="center">J/P</td>
     <td align="center">AVG</td>
  </tr>
  <tr>
    <td align="center">Logistic Regression</td>
     <td align="center">0.8006</td>
     <td align="center">0.7896</td>
     <td align="center">0.7311</td>
     <td align="center">0.7311</td>
     <td align="center">0.7878</td>
  </tr>
  <tr>
    <td align="center">SVC Accuracy</td>
     <td align="center">0.7375</td>
     <td align="center">0.7682</td>
     <td align="center">0.8108</td>
     <td align="center">0.7032</td>
     <td align="center">0.7549</td>
  </tr>
  <tr>
    <td align="center">SGD Classifier</td>
     <td align="center">0.7801</td>
     <td align="center">0.7878</td>
     <td align="center">0.8252</td>
     <td align="center">0.7196</td>
     <td align="center">0.7781</td>
  </tr>
  <tr>
    <td align="center">Random Forest</td>
     <td align="center">0.7496</td>
     <td align="center">0.7124</td>
     <td align="center">0.769</td>
     <td align="center">0.6856</td>
     <td align="center">0.7291</td>
  </tr>
  <tr>
    <td align="center">XGBoost</td>
     <td align="center">0.7767</td>
     <td align="center">0.7434</td>
     <td align="center">0.7933</td>
     <td align="center">0.6995</td>
     <td align="center">0.7532</td>
  </tr>
  <tr>
    <td align="center">CatBoost</td>
     <td align="center">0.7838</td>
     <td align="center">0.7635</td>
     <td align="center">0.8064</td>
     <td align="center">0.7128</td>
     <td align="center">0.7666</td>
  </tr>
 </table>

 ### LSTM Model
 We trained the LSTM and managed to get an Accuracy of **73.02%**, a loss of **1.1323**.

#### For more detailed results check the report

## Contributors
<table>
<tr>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/hedrax>
            <img src=https://avatars.githubusercontent.com/u/88040920?s=400&v=4 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Alhossien Waly/>
            <br />
            <sub style="font-size:14px"><b>Alhossien Waly</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/AliFeteha>
            <img src=https://avatars.githubusercontent.com/u/116113529?v=4 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Ali Ibrahim/>
            <br />
            <sub style="font-size:14px"><b>Ali Ibrahim</b></sub>
        </a>
    </td>
</tr>
</table>
