# 2022 AI CUP 農地作物現況調查影像辨識競賽 - 春季賽：AI作物影像判釋
https://aidea-web.tw/topic/93c8c26b-0e96-44bc-9a53-1c96353ad340
# 訓練順序    
  Data_resize.ipynb -> iInceptionResNetV2+SE-net.ipynb
# 訓練方法
  >Data_resize .ipynb 
  >>更改Train與Valid的位置成你儲存的位置   
  >>更改Train_RGB_500與Valid_RGB_500的位置成你要儲存的位置
  >>![image](https://user-images.githubusercontent.com/93694868/169791680-ad85aa60-972e-4e82-9ff9-e788244ea57f.png)  

  >iInceptionResNetV2+SE-net.ipynb  
  >>更改Train_RGB_500與Valid_RGB_500的位置成你儲存的位置
  >>![image](https://user-images.githubusercontent.com/93694868/169791831-61d7c858-29aa-4f9d-9198-ec435bc764a4.png)     
  >>更改model的位置成你要儲存的位置  
  >>![image](https://user-images.githubusercontent.com/93694868/169791896-9638d292-19b7-4998-836a-68298d5a1291.png)  
# 測試
  >test.ipynb
  >>更改Valid_RGB_500的位置成你儲存的位置  
  >>![image](https://user-images.githubusercontent.com/93694868/169792059-d1f82e0a-bfba-4480-ab4e-1ee62561fb69.png)  
  >>更改model的位置成你儲存的位置  
  >>![image](https://user-images.githubusercontent.com/93694868/169792097-04ac17a9-40cb-4479-bc99-a3639cf2f208.png)  
# 預測private data
  >test_private.ipynb  
  >>更改private的位置成你儲存的位置  
  >>更改model的位置成你儲存的位置  
  >>![image](https://user-images.githubusercontent.com/93694868/169791104-21453090-d7cb-41e0-9bfc-c582ddc3e370.png)  
  >>更改Train_RGB_500的位置成你儲存的位置  
  >>![image](https://user-images.githubusercontent.com/93694868/169791266-9aa51f72-860c-4b14-9967-88b0e04529c1.png) 
