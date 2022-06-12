# Proje-2
### [16,21,11,8,12,22]  Merge Sort

#### 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
###### MErge Sort: Birleşmeli Sıralama, bilgisayar bilimlerinde {\displaystyle {\mathcal {O}}} derecesinde karmaşıklığa sahip bir sıralama algoritmasıdır. Girdi olarak aldığı diziyi en küçük hale gelene kadar ikili gruplara böler ve karşılaştırma yöntemi kullanarak diziyi sıralar

**İkili bölme işlemi**	

![image](https://user-images.githubusercontent.com/103898383/173248899-5dfa1b42-9f7d-47c6-af2e-21b229e058c7.png)

**İkili birleştirme yöntemi**	
											
![image](https://user-images.githubusercontent.com/103898383/173249092-4be22d4f-a975-42f1-b89e-606b0ddcdb5e.png)


#### 2. Big-O gösterimini yazınız.
Recursive bir fonksiyon olduğu için sürekli kendini çağırarak diziyi hep ikiye bölmektedir. Her bölünmüş dizinin Merge işlemi için de dizinin uzunluğu olan n işlem yapıldığından O(n*(logn)) --> O(6*(log6)) olacaktır.
