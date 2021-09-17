# Lab Notebook

## 09-09-2021(Thursday)
Right now my main focus is (at a high level) understanding how attention and transformers work in language models. I'm doign this by:

- reading the goodfellow deeplearning textbook
- blogposts()

Next, I'm going to try and figure out how to use pytorch 

## 09-13-2021(Monday)
- have read through most of the code for gMVP. Trying to run the initial data generation scripts, but missing input files. Rest of lab has not been super reponsive 
- I did find some processed files elsewhere on the `/data` drive ( in `hz**/protein/tf` ), that I might be able to use in the mean time to get something up and running 
- debating on whether or not to talk to yufeng about the lack of communication/documentation on the project. 

## 09-14-2021(Tuesday)
- realized I have no idea how to use pytorch, and will probably be more of a bottle neck, so i think it will be  a better use of my time to focus on that.
    - right now my plan is to go through tensorflow walkthroughs, but implement them in pytorch, so I will get exposure to both.
- Also, need to devote more time to the goodfellow book, bc I'm definitely feeling a bit lost math wise 

## 09-15-2021(Wednesday)
- Made a little more progress on pytorch today, but had a lot of course work and wasnt able to get into it as much 

## 09-(16, 17)-2021
Overall progress for the week
- realized me learning pytorch will be the biggest bottle neck for the project; have devoted most of time since tuesday on learning pytorch
- made decent progress, implmented a basic LSTM-rnn in colab (https://colab.research.google.com/drive/1HgkZ73uq3awAE1zllIALeKz8EetKfpk3)
- spoke with xiao, and she gave me the necessary files to both re-generate the training data and re-train the original gMVP tensorflow model
    - xiao mentioned that the gMVP model took a month(!) to train, so maybe talk to yufeng about using AWS (spot instances likely )
Tasks for next Week
- run the basic rnn we implemented in colab on the shen lab server, so we can get some practice setting up the env(maybe use docker?)
- implement a seq2seq model with attention 
- regenerate the training data and prepare it for use with pytorch 
Reflections for the week 
- I think I have enough time for research during the day, but need to careful about how I manage my time
- I have a little more sense about the gMVP project, and I am overall a little more comfortable working with yufeng
- one thing I have noticed is that the quality of code in the lab is pretty poor, which might not be what I want long term. 
- Another thing is that there doesn't seem to be a large sense of community in the lab; for the most part people kind of work on their own stuff and dont collaborate as much 

