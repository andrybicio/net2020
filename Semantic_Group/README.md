# The semantic network project 

This group is focused on the semantic and sentiment anlysis of the text corpus.

Members: 
Diego pilutti, Yasmine Elkhaloufi, Andrea Nicolai, Natascia Caria, Lynda Wainaina, Baran Karakaya.

## TimeTable

### Week 0 (30-6 dic)
```Common_start``` folder: find instructions about how to "play with data" in the README.md

1)**Text cleaning** (post and comments):
- Format the charachters  (FR kayborrd)
- Removing punctuations  (to be fixed - we still have some "l'")
- Tokenization  (list of words) 
- Stop Words removal 
- Lemmizzation (we have done stemming, but we prefer lemming) 

Open challenge:
- how to transofrm emoji into text to not lose informations -- or cleaning emoji
- be sure to keep the hastags as hashtags
- manual cleaning of text
  1) removing the mispelling words (filter all the words with a dictionary to find out the incorect words)
  2) with Lemmization some informations are lost: ex. "sinistra" will be "sinistro" and this could be a problem for sentiment analysis

### Week 1 (7-13 dic)
<p align="left">
  <img src="https://upload.wikimedia.org/wikipedia/de/thumb/2/20/Matrix-logo.svg/1200px-Matrix-logo.svg.png" width="350" title="hover text">
</p>
1) Network creation: "create the matrix"
- Using ```networkX``` create links between words and plot some initial graphs.
- Adding the weight to the links: two words are liked if the are together in the same post/tweet/comment
- Adding attributes to the nodes (like sentiment)
- Export files to be used in Gephi (EdgeList + NodesAttribute )

2) Create a defitive files with pickle fuction 

Open challenge:
- create node and links DB to be able to open the graph on Gephi --> you can take ispiration from [last year project](https://github.com/SalvatoreRomano1/HateSpeech_NetworkAnalysisProject) 
- try to create a visualization directly on python with networkX
- chose witch ```countVectorize``` or ```AdjencyMatrix``` is better and less time consuming in the matrix creation

### Week 2 (14-20 dic)

1) Final cleaning of the word list, to be done manually by an italian student 
2) 

- add new nodes' features (like )

### Week 3 (21-3 jan)
<<Holydays!>>

1)Sentiment analysis of the words
  -we still need the final list of words to be analyzed (the list of 47K unique words)  
  
2)Some papers will be shared 


### Week 4 (4-10 jan)
create the gephi graphs

### Week 5 (11-17 jan)
Perform network analysis

### Week 6 (18-24 jan)
Report and Presentation writing

### final Exams
date: 28/01
