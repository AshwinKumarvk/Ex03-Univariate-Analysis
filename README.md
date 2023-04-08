# Ex03-Univariate-Analysis

## AIM: 
          To perform univariate analysis on a given data set 

## ALGORITHM:
         1.Start 
         2.Read the data from the file 
         3.clean the data a.remove outliers b.fill the null values by using statistical methods or drop the null value coulmn 
         4.perform univariate analysis it can be applied only on a single data. 
         5.exit
         
## PROGRAM: 
         Describe ()
         
         Code: 
         
         import pandas as pd 
         df=pd.read_csv("/content/SuperStore.csv") 
         df.describe()
![image](https://user-images.githubusercontent.com/95520655/230703672-3b84b7f4-0a25-4d3f-89e1-0e88dba0c704.png)

          df.info()
![image](https://user-images.githubusercontent.com/95520655/230703733-11f0a3e4-e19c-495a-a745-f148fb2a5932.png)

          df.isnull().sum()
![image](https://user-images.githubusercontent.com/95520655/230703763-aa883fba-d46b-4930-a52d-ccb6dee4bb0e.png)
          
          Box plot:
![image](https://user-images.githubusercontent.com/95520655/230703790-fff96460-3240-4653-915d-60f9688d0e6c.png)
          
          Count plot:  
![image](https://user-images.githubusercontent.com/95520655/230703863-03ba770d-5b33-4d92-9264-4ed769f8c5af.png)
          
          Skew fnction:
![image](https://user-images.githubusercontent.com/95520655/230703891-6af1d229-3a74-477f-9b7c-0747f8741659.png)
          
          Dist plot: 
![image](https://user-images.githubusercontent.com/95520655/230703911-e144984e-fbff-46dc-8468-c48d992fa33b.png)
          
          Hist plot:
![image](https://user-images.githubusercontent.com/95520655/230703951-0b6000de-9147-4454-8337-77f16b51f248.png)

## Result:
          Thus we have done the univariate analysis on the given dataset.



         
        
