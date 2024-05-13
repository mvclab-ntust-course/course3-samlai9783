[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/X3WkcXtG)
這份專案是參考[子不語怪力亂神的Stable Diffusion -- 訓練LoRA](<https://vocus.cc/article/642db062fd897800014596ad>)完成的。

先將兩個程式碼複製到雲端硬碟，在雲端硬碟中新增一個名稱為Loras的資料夾，在Loras內用專案名稱新增資料夾(ex. SteveJobs)和regulation資料夾，我先利用[BRIME](<https://www.birme.net/?target_width=512&target_height=512>)網站將所有使用到的圖片都裁剪成512x512，再把訓練圖放入專案名稱資料夾內，把規範圖放入regulation資料夾內。再利用Dataset_maker產生提示詞，最後用Lora_trainer訓練模型，再使用stable-diffusion的webui產生圖片。
