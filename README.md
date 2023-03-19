# Sentiment-Analysis-During-Covid-19
This paper focused on twitter data and trending hashtags which was trend during covid time. The experiment is performed using neural network, Bi-LSTM, and CNN algorithms. It achieves the overall accuracy for the proposed model is 95.7% with 0.0019 average training time and 0.0082 standard deviation.

Procedure
            The analysis is performed with 5 phases: 
            1.Dataset
            2.Preprocessing
            3.Model Selection and Extraction
            4.Neural Network
            
1. Dataset
            In this dataset we have 5 classification term in sentiment
            1. Positive
            2. Extremely Positive
            3. Neutral
            4. Negative
            5. Extremely Negative
        
Twitter Dataset Image
2. Preprocessing
            In preprocessing we have several task to perform like:
            a. Selecting Features
            b. Remove Patterns
            c. Stemming
            d. Remove Stop words
        
3. Model Selection and Extraction
            Tokenizing and Encoding the data
            Tokenizers are used to vectorize text. Tokenization converts text into different forms
            such as sequence, string, matrix, and so on. To make use of the neural network's
            compute capacity, tweets must be converted to a series of integers.
            Splitting the data
            Training and testing are the process of dividing our dataset into two sections, one for
            training our model so that it may learn and the other for assessing our model's
            performance. Typically, we regarded 70% of our dataset to be a training subset and 30%
            of the data to be a testing subset. 
            
4. Neural Network
            This technique is highly effective in our dataset since the tweets are in text(string),
            giving the model an advantage in the computational component.
            The operation of embedding layers is straightforward; the layer is initially seeded with
            random weights, and as the model advances, the layer begins learning the embedding
            component for all the words in the training dataset.
            Long short-term memory (LSTM) is a sort of RNN (Recurrent Neural Network) that
            can pass over the data's long-term reliance. The LSTM can readily connect prior and
            present information. LSTM basically has a memory cell that can remember information
            for a long time.
            
4 Methodology and Results
            In this work, we first investigate the data supplied by Twitter. We focus on the nature
            of the data and visualize it while examining it. This enables us to determine the
            proportion of each tweet. We extract the data that is required based on the knowledge
            base. As we all know, the polarity of a tweet is unaffected by the location of the person
            who tweets. So we may delete that feature without examining its relationship to the
            label. The removal of hashtags, links, and ids, among other things, is critical in tweet
            preprocessing because it can cause problems such as underfitting and overfitting. The
            stemming process makes the tweet more understandable for the computer once the
            superfluous patterns are removed. In the stemming section each word is replaced with
            its root word. Removing stop words from the NTLK corpus library reduces the
            dimensions and chance of overfitting. This corpus library contains all the words which
            do not add any meaning to sentences like is, are, the etc.
