---
layout: post
title:  "Writing Financial Regulations"
date:   2018-03-02
---

I am learning [Apache MXNet](https://mxnet.incubator.apache.org/) and specifically recurrent neural nets (RNNs). There are [three solid tutorials about RNNs for text generation](http://gluon.mxnet.io/chapter05_recurrent-neural-networks/simple-rnn.html). The text I am using for the tutorials is MiFID II. Below, I am going to share what the RNNs generate. I am running the tutorials on a CPU so I am using 50 epochs insteatd of 2000 which the tutorials use. 

The plain RNN and LSTM at epoch 49 resemble MiFID II the most but are still not close to human generated text.

#### Plain RNN

__Epoch 0. Loss: 77.03520176790099__

The committee shall submit the investment firm or market operators of the investment firm or market operators operating an MTF or an OTF to be abequard to the investment firm or market operators operating an MTF or an OTF shall submit those draft regulatory technical standards to the Commission to adopt the implementing technical standards to the Commission to adopt the implementing technical standards to the Commission to adopt the implementing technical standards to the Commission to adopt the implementing technical standards to the Commission to adopt the implementing technical standards to the Commission to adopt the implementing technical standards to the Commission to adopt the implementing technical standards to the Commission to adopt the implementing technical standards to the Commission to adopt the implementing technical standards to the Commission to adopt the implementing technical standards to the Commission to adopt the implementing technical standards to the Commission to adopt the implementing technical s

__Epoch 24. Loss: 69.77740541578774__

The committee shall submit those draft regulatory technical standards to the Commission by 3 July 2015.

Power is delegated to the Commission to adopt the regulatory technical standards to the Commission by 3 July 2015.

Power is delegated to the Commission to adopt the regulatory technical standards to the Commission to adopt the regulatory technical standards to the Commission by 3 July 2015.

Power is delegated to the Commission to adopt the regulatory technical standards to the Commission by 3 July 2015.

Power is delegated to the Commission by 3 July 2015.

Power is delegated to the Commission to adopt the regulatory technical standards to the Commission by 3 July 2015.

Power is delegated to the Commission by 3 July 2015.

Power is delegated to the Commission to adopt the regulatory technical standards to the Commission to adopt the regulatory technical standards to the Commission to adopt the regulatory technical standards to the Commission by 3 July 2015.

Power is delegated to the Commission to adopt the regulato

__Epoch 49. Loss: 65.15755056439647__

The committee shall be informed of a regulated market to the competent authority of the home Member State of the obligations under this Directive and shall contract to any procedures and arrangements to a financial instrument or derivatives thereof and the size of the services or provided to the competent authority of the home Member State of the obligations under this Directive and the firm and the procedures and the size of the services or provided to the competent authority of the host Member State shall contract to the provision of the services or activities or the order on the market operator operating an MTF or an OTF shall be investment services or perform investment activities as defined in Article 2(1) of Regulation (EU) No 600/2014 and the competent authority of the home Member State of the investment firm shall not be subject to the service in respect of the services or activities that the conditions for initial authorisation and operation of the regulated market shall be made available to the competent authori

#### GRU

__Epoch 0. Loss: 2.9113809377981266__

Traders wille the the the the the the the the the the therentiontite the the the therentiontintiontis ontiontionses the the the the the the the the the the the the the the the the the the the theres the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the therentiontins antiontins the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the therentiontiontiontiontis ons the the the the the the theres ontintiontiontis onte the the therentiontis on the the the the the the the the the the the the the the the therentiontiontiontiontins the the the the the the the the the the the the the the the the theres the the the the the the theres the the the the the the the therention the theres thes the the the the the the the the the the the the the theres the the the the the the the the the the thes ont

__Epoch 24. Loss: 0.8781695486314105__

Traders will be applicable to the contract and related acts and the protection of the protection of the protection of clients and the consolidated take and protection of the protection of the protection of the client or adopt the requirements and of the protection of the client or professional client orders and the protection of the protection of the protection of the protection of the protection of the protection of the client or request the contract and the protection of the protection of the protection of the protection of the client or an investment firm or market operator or a protection of the protection of the protection of the client or administrative and account the client orders or participants of the regulated market and the protection of the protection of the protection of the client or the protection of the protection of the client or the protection of the client or administrative and account the client or adopt the request the contract in accordance with Article 14(1) to (1) of Regulation (EU) No 600/2014 o

__Epoch 49. Loss: 0.7883913808882361__

Traders will be able to require the conditions for investment firms and the conditions for investment firms and the conditions for investment firms and the provision of investment services and activities and the contract in accordance with Article 14 of Regulation (EU) No 600/2014 and the provision of investment services and activities and the provision of investment services and activities and the conditions for investment firms and the provisions of this Directive or of Regulation (EU) No 600/2014 and the provisions of this Directive and of the Council of 14 Article 13(1), Article 20(1), Article 20(1), Article 20(1), Article 23(1), Article 24(1), Article 20(1), Article 20(1), Article 20(1), Article 20(1), Article 20(1), Article 20(1), Article 25(1), Article 20(1), Article 20(1), Article 20(1), Article 23(1), Article 20(1), Article 20(1), Article 24(1), Article 25(1), Article 24(1), Article 24(1), Article 20(1), Article 20(1), Article 23(1), Article 20(1), Article 20(1), Article 23(1), Article 20(1), Article 23(1), Arti

​
#### LSTM

__Epoch 0. Loss: 3.2066613358610434__

The committee te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te on te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te tin on te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te tin te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te tite te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te on te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te te tin te te te te te te te te te te te te on te te te te ten te te te te 

__Epoch 24. Loss: 0.9464266509444252__

The committee investment firms and provided for the provisions of the competent authorities and the conditions for the provisions of the conditions of the conditions for the provisions of the conditions of the conditions of the conditions of the conditions for the purpose of provided to the competent authority of the competent authorities and the conditions for the provisions of the conditions in the content of the competent authorities of the competent authority of the competent authority of the competent authority of the competent authority of the competent authorities of the conditions for the provisions of the conditions for the provisions of the competent authority of the competent authority of the competent authority of the competent authorities of the competent authority of the competent authority of the competent authority of the competent authorities of the conditions for the purposes of the conditions for the purpose of provided for the provisions of the competent authority of the competent authorities of the co

__Epoch 49. Loss: 0.8360352498476799__

The committee the investment firm or market operators operating an MTF or an OTF shall be ensured that the competent authority of the home Member State and the provisions of the provisions of the provisions of the provisions of the provision of investment firms and market operators operating an MTF or an OTF shall be empowered to adopt delegated acts in accordance with Article 19 of Regulation (EU) No 1095/2010 of the European Parliament and of the Council of 2 July 2014 on the transactions concerning the provisions of this Directive and securities and an investment firm or market operators operating an MTF or an OTF shall be empowered to adopt delegated acts in accordance with Article 19 of Regulation (EU) No 600/2014 of the European Parliament and of the Council of 2 July 2016 on the transactions concerned and the subject to the competent authorities of the services or perform investment services or perform investment services or perform investment services or activities and an investment firm or market operators operat