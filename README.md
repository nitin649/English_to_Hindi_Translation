# English to Hindi Language Translation (Machine Translation)

# Description:

## Machine Translation
Machine Translation (MT) is the task of automatically converting one natural language into another, preserving the meaning of the input text, 
and producing fluent text in the output language.


# Project Structure

1. For the purpose of this project, we will use online dataset of english and hindi sentences. 

## Model Aerchitecture 

### Sequence to Sequence Modelling
![seq_2_seq](https://user-images.githubusercontent.com/55678844/149960315-3e1f8269-0303-44c4-aa8e-5a54ee75c8d3.png)

1.  Sequence Modelling problems refer to the problems where either the input and/or the output is a sequence of data (words, letters…etc.)
2.  Sequence-to-Sequence (Seq2Seq) problems is a special class of Sequence Modelling Problems in which both, the input and the output is a sequence. 
Encoder-Decoder models were originally built to solve such Seq2Seq problems. 

### Encoder-Decoder Model
![encoder_decoder_model](https://user-images.githubusercontent.com/55678844/149959954-099b3ef4-3690-4ae9-98c9-d931db4e4cc8.png)

1. An Encoder-Decoder architecture was developed where an input sequence was read in entirety and encoded to a fixed-length internal representation.
   A decoder network then used this internal representation to output words until the end of sequence token was reached. 
2. Recurrent networks are used for both the encoder and decoder
3. I have used LSTM for this task.


