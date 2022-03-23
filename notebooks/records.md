## 回归模型
![img.png](img.png)

## 沪深300指数: 2017-2022
![img_3.png](img_3.png)

## 沪深300指数：2022
![img_6.png](img_6.png)

## 五年数据训练,未来预测: 2022
- data_path = 'data/cs_space_1d_rate_20d_2022_pre'
- model_path = 'models/model_c2_p[[0.0, 0.3], [0.7, 1.0]]_b32_lr0.001_d0.5_e500.pth'

[0:20] average precision: tensor([0.3950, 0.0000])
![img_10.png](img_10.png)

## 五年数据训练，历史回测：2017-2022
- data_path = 'data/cs_space_20d_rate_20d_2017_pre'
- model_path = 'models/model_c2_p[[0.0, 0.3], [0.7, 1.0]]_b32_lr0.001_d0.5_e500.pth'

[0: 20] average precision: tensor([0.5833, 0.0000])
![img_7.png](img_7.png)

[20: 40] average precision: tensor([0.5275, 0.0000])
![img_8.png](img_8.png)

[40: 60] average precision: tensor([0.5200, 0.0000])
![img_4.png](img_4.png)

[60: 80] average precision: tensor([0.5233, 0.0000])
![img_5.png](img_5.png)

[80: 100] average precision: tensor([0.5058, 0.0000])
![img_9.png](img_9.png)