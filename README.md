losssylesscompressionPHP
========================

PHP lossy less compression helper class using optiPNG advPNG and advdef. All these component must be installed in the server
to use this class. Installation of these components can be acheive by just installing advanceMAME:
http://sourceforge.net/projects/advancemame/


This class can be used independently or with Yii framework. 



examples: 

To compress the image by lossyless:
 LossylessHelper::lossylessImg('\img\example.png');
  
 To compress the images in the folder:
 LossylessHelper::lossylessFolder('\img');
 
 
 To use this class with other frameworks or independently: 
 just comment the lines: 
  if ($log)
            Yii::log($log);
            
            As:
        //    if ($log)
        //    Yii::log($log);


Any contribution to the class is highly appreciated.
