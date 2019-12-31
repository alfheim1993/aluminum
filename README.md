[2018广东工业智造大数据创新大赛——智能算法赛](https://tianchi.aliyun.com/competition/introduction.htm?
## 运行代码前，需要将图片放在data目录下，目录树如下：

	|--data
		|--guangdong_round1_train1_20180903
		|--guangdong_round1_train2_20180916
		|--guangdong_round1_test_a_20180916
	|--gen_label_csv.py
	|--model_v4.py
	|--main_inception_v4.py

---
## 代码运行方式：
	python gen_label_csv.py
	python main_inception_v4.py

---
## 程序说明：
框架：Pytorch 0.4

