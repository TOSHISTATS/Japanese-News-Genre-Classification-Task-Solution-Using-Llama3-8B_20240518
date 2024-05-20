# Llama3-8Bによるlivedoor-newsデータを用いたニュースの9クラス判別問題 / Japanese-News-Genre-Classification-Task-Solution-Using-Llama3-8B_20240520

livedoor-newsデータ(1)を用いた9クラスのニュース判別問題を finetuneしたLlama3-8Bで90%超の精度を達成

Achieve more than 90% accuracy with finetuned Llama3-8B for 9 class-news-classification problem using livedoor-news data

trainingデータ・testデータともに1000サンプルでファイン・チューニング

finetuned with data of livedoor news corpus for 9 classes (training 1000 samples, test 1000 samples)








### 予測と正解の分布 / distributions of prediction and label

![Screenshot 2024-05-20 12 57 52](https://github.com/TOSHISTATS/Japanese-News-Genre-Classification-Task-Solution-Using-Llama3-8B_20240520/assets/28681557/137773a3-4960-4e7a-a4cb-0f9837dfde16)





![Screenshot 2024-05-20 12 58 03](https://github.com/TOSHISTATS/Japanese-News-Genre-Classification-Task-Solution-Using-Llama3-8B_20240520/assets/28681557/d66808d9-8f89-4588-b0dc-8243b987f6cf)



(1) livedoor news corpus https://www.rondhuit.com/download.html#ldcc
CC BY-ND 2.1 JP https://creativecommons.org/licenses/by-nd/2.1/jp/


Copyright © 2024 ToshiStats Co.,Ltd. All right reserved

This code is solely for educational purposes. 

Notice: ToshiStats Co., Ltd. and I do not accept any responsibility or liability for loss or damage occasioned to any person or property through using materials, instructions, methods, algorithms or ideas contained herein, or acting or refraining from acting as a result of such use. ToshiStats Co., Ltd. and I expressly disclaim all implied warranties, including merchantability or fitness for any particular purpose. There will be no duty on ToshiStats Co., Ltd. and me to correct any errors or defects in the codes and the software.
