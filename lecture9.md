cs224d lecture9

  关键词
  
    ·LSTM
    
    ·recursive neural network(递归神经网络，RcNN,区别于RNN（循环神经网络）)
    
        word vector space model
        
          通常我们把单词以向量形式表示在向量空间中
          那么我们怎么表示短语甚至是句子？
          By mapping them into the same vector space!
          把一个句子在词向量空间中表示，先将每两个相邻单词通过算法（没具体讲）得到一个新的向量和一个得分（score），该向量与词向量同维度，得分越高说相应的两个单词组合在一起有更大的几率是合理的，重复这一过程，最终得到的一棵语法树就代表该句子的向量。
         
        如何训练该模型？————max-margin parsing
        
        <img src="./test.jpg" width="50" height="50">
          
        
      
