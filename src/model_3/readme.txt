ִ�� run.py     �������result_gy.csv���������һ��Ŀ¼��

�ű�Ŀ¼
gy

������Դ
data/dataset/

======����Ԥ����========

generate_20min_volume.py    
ͳ��ÿ20���ӳ������� 4��ʱ�䴰��  ������ 0,5,10,15 min��

preprocessing0.py
����������Ԥ��������Сʱ���ˣ� ֻ����6,7,8,9��15,16,17,18 ������

preprocessing1.py
��������Ԥ����

preprocessing2.py
�ϲ������ͳ����������ɲ�������

preprocessing3.py
ʱ�����зֽ⣬�õ�seasonal����

preprocessing4.py
�����������ڼ��գ��׸�\������� �� ÿ�ܵ�n��


======ģ��========

model1.py
���ɭ��
ʹ�ö���ʱ�䴰������
ÿ�� tollgate\direction  ѵ��һ��ģ��

model2.py
knn
��ʹ�ö���ʱ�䴰������
ÿ�� tollgate\direction  ѵ��һ��ģ��

model3.py
���ɭ��
�����쳣ֵ
ʹ�ö���ʱ�䴰������
volume = log��volume��
����tollgate\direction  ѵ��һ��ģ��

model4.py
GBRT
ʹ�ö���ʱ�䴰������
����tollgate\direction  ѵ��һ��ģ��

model5.py
knn
ʹ�ö���ʱ�䴰������
����tollgate\direction  ѵ��һ��ģ��


======�ں�========
stacking.py
�ں�5��ģ�ͽ��
���������result_gy.csv���������һ��Ŀ¼��
