1. 验证集所有样本
在code路径下执行python main.py --cfg cfg/eval_bird.yml --gpu 0即可实现验证。屏幕会打印出图片保存路径。

2. 验证集部分采样
在code/cfg/eval_bird.yml下有个重要参数，B_VALIDATION为False时，默认验证.\data\birds\example_filenames.txt中包含的caption。
