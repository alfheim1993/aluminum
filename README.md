# ���ͼ�����Baseline����
[2018�㶫��ҵ��������ݴ��´������������㷨��](https://tianchi.aliyun.com/competition/introduction.htm?spm=5176.11165320.5678.1.54114443WSKVPP&raceId=231682)��δ�������������`0.921`
---
## ���д���ǰ����Ҫ��ͼƬ����dataĿ¼�£�Ŀ¼�����£�

	|--data
		|--guangdong_round1_train1_20180903
		|--guangdong_round1_train2_20180916
		|--guangdong_round1_test_a_20180916
	|--gen_label_csv.py
	|--model_v4.py
	|--main_inception_v4.py

---
## �������з�ʽ��
	python gen_label_csv.py
	python main_inception_v4.py

---
## ����˵����
��ܣ�Pytorch 0.4

���뾭���ԣ����Ϸ���Ϊ`0.921`������19��������2018.9.20����

����а汾������ֻ���޸������������������Զ�������Ŀ¼���ڱ���ģ�������ļ���

ʹ�õ�ģ��ΪImageNetԤѵ����inception v4������˼·��������ǿ֮��ֱ�ӽ�����ȫ����һ��ѵ�������򵥷��ࡣ

������Ϊbaseline��δ���κε��Σ�ѵ��������������ǿ��ʽ�ȿ������������޸ġ�

����ߴ�Ϊ384��384���������out of memory���Դ治�㣩���ɼ�Сbatch size�������ܡ�
