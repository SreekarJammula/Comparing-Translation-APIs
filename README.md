Comparing the Microsoft and Google translation APIs.
In the fierce cloud market, both the big tech companies Microsoft and Google have introduced their translation API’s as services on their cloud platforms. So, I decided to try them both and make a comparison. In this small blog, I have tried comparing them on parameters such as ease of use, punctuations, accuracy and speed. 

Let me discuss these parameters on a case by case basis. 

Ease of use:
Although I did not try to develop any applications using these APIs, I tried to see if there was any way to try it on the web consoles. In this aspect, GCP wins hands down. It allows the user to try or preview the API if one has a GCP account and also displays the HTTP requests made and the JSON responses received from the server.
 Azure on the other hand doesn’t allow a user to preview the API. One has to go through a lengthy registration process and also choose a translation API plan. Thus, I settled down to use the Bing Translator tool(which internally uses the Microsoft translate API available on Azure platform) on the web which is similar to Google Translate. 

Punctuations: 
I tried four different sentences in French and translated them into English on both platforms. Although both platforms preserved the punctuations and delivered the meanings, google platform lags in the fact that it does not preserve the new line delimiter. This means that, even though one inputs several separate sentences, they all are translated as one single paragraph.  

 <img src ="https://github.com/SreekarJammula/Comparing-Translation-APIs/blob/master/Assets/Screenshot%20(10).png">
 
 
 <img src="https://github.com/SreekarJammula/Comparing-Translation-APIs/blob/master/Assets/Screenshot%20(11).png">

Thus, Microsoft translator API is better in this aspect

Accuracy:  
Both the platforms perform well in this aspect.  I tried two different paragraphs and both of these were translated almost similarly by both platforms. I can say that these translations were 99% similar when compared from platform to platform. This is a very good sign as one always expects to receive accurate and useful translations when using these APIs. 

Speed: 
To test the speed, I tried  huge French paragraphs on the platforms in three different iterations. During all attempts, the time taken was very very less(maybe milliseconds) on both the platforms. Thus, both the platforms perform equally in this aspect. 
Finally, I feel that both the platforms are equally good in translating languages. However, there are several limitations to my experiments as I have tried only French to English translations and also I did not use the APIs to develop any programs or applications. It is impressive that Microsoft which is a late entrant into this domain has developed such a great product which is competing with other leading translators. Google Translate API on the other hand has been around for some time now and one can clearly observe  the amazing transformation and the tuning it has undergone  before it has been introduced on the GCP.
