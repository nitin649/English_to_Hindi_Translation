# English to Hindi Language Translation (Machine Translation)

# Description:

## Machine Translation
Machine Translation (MT) is the task of automatically converting one natural language into another, preserving the meaning of the input text, 
and producing fluent text in the output language.


# Project Structure

1. For the purpose of this project, we will use online dataset of english and hindi sentences. 

## Model Aerchitecture 

### Sequence to Sequence Modelling
1.  Sequence Modelling problems refer to the problems where either the input and/or the output is a sequence of data (words, letters…etc.)
2.Sequence-to-Sequence (Seq2Seq) problems is a special class of Sequence Modelling Problems in which both, the input and the output is a sequence. 
Encoder-Decoder models were originally built to solve such Seq2Seq problems. 

### Encoder-Decoder Model
1. An Encoder-Decoder architecture was developed where an input sequence was read in entirety and encoded to a fixed-length internal representation.
   A decoder network then used this internal representation to output words until the end of sequence token was reached. 
2. Recurrent networks are used for both the encoder and decoder
3. I have used LSTM for this task.

