# Tips on using our code  
The following structure is as follows:  
- 1.Prepare the data  
- 2.Train the model  
- 3.Use saved model to evaluate 
## Generate Data
## Train the Model
### Signal Transformer
**using Stochastic Gradient Descent (SGD)**  
` python TRAIN.py -GI * -LP * -SP * -LR 0.5 `  
python C:\Users\lingli\Desktop\ofd_ai\Signal_Detection\DATA\TRAIN.py  -GI 0 -LP C:\Users\lingli\Desktop\ofd_ai\Signal_Detection\train\LP -SP C:\Users\lingli\Desktop\ofd_ai\Signal_Detection\train\SP -LR 0.5
**using Adam**  
` python TRAIN.py -GI * -LP * -SP * -OPTIM adam -LR 0.0001 `