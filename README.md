# Machine-Translation-From-Danish-to-English

This is a Model that is made of Gated Recurrent Units.
The model consists an encoder and decoder layer, The input goes through an embedding layer created with the help of Keras and then it goes to the input layer which
Outputs a vector that is sent to the decoder layer which at every time step goes to a dense layer of 10,000 nodes which predicts the word and combining all time steps 
gives the translated sentence.

![model](https://github.com/rishabh-vasudevan/Machine-Translation-From-Danish-to-English/blob/main/21_machine_translation_flowchart.png)
