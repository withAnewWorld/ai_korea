# ai-korea

## image classification <br/>
1. 해양 침적 쓰레기 분류 (submerged marine debries) <br/>
   [URL](https://ai-korea.kr/playground/selectTutorialPlaygroundTask.do)  <br/>
   * method <br/>
     a) fine tune: EfficientNetB0(NDVIA)   
    
   * log <br/>
     a) Time <br/>
     &nbsp; &nbsp; Train & eval: About 40 minutes for total epochs (colab GPU) <br/>
     b) # of Epochs: 10 <br/>
     c) loss function: Cross Entropy <br/>
     d) optimizer: Adam <br/>
     
   RESULT: 0.51(F1 Score)
