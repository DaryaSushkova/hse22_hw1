# hse22_hw1
_Сушкова Дарья Сергеевна, подгруппа 2_   
### Список команд на сервере   
_Взаимодействие осуществлялось с помощью MobaXterm._   
1. Создание ссылок на требуемые файлы:   
![image](https://user-images.githubusercontent.com/89806836/193797088-f5c0c29d-e4d8-477a-9e46-863e553ba614.png)   
2. Выбор случайных чтений для каждого типа соответственно:   
![image](https://user-images.githubusercontent.com/89806836/193797253-be9c9858-f562-472a-a3a5-2eafee7806cd.png)   
3. Оценка качества исходных чтений с помощью программы fastQC:   
![image](https://user-images.githubusercontent.com/89806836/193797478-9ab6241c-4799-491e-8a5b-b4ecfa64a8af.png)   
4. Создание отчета с помощью программы multiQC:   
![image](https://user-images.githubusercontent.com/89806836/193797657-e8b4e547-664b-452f-971b-fc8551c5fa24.png)   
5. Подрезка чтений по качеству и удаление адаптеров:   
![image](https://user-images.githubusercontent.com/89806836/193797798-ff411793-ae68-47bb-bc1a-bff28885ce3d.png)   
![image](https://user-images.githubusercontent.com/89806836/193797847-42bdb193-777d-41ed-8b25-b4dbdbffcab9.png)   
_Примечание: удаление файлов с исходными чтениями производились вручную благодаря средствам MobaXtern.   
На следующих шагах имена **sub*** и **mp*** имеют только файлы с **подрезанными** чтениями._   
6. Оценка качества **подрезанных** чтений с помощью программы fastQC:   
![image](https://user-images.githubusercontent.com/89806836/193798286-fd03b72e-f942-4425-8a4a-8bff7823d611.png)   
7. Создание отчета для **подрезанных** чтений с помощью программы multiQC:   
![image](https://user-images.githubusercontent.com/89806836/193798444-795648cb-6cdd-4777-bcd3-f417276567ef.png)   
8. Сбор **контигов** для подрезанных чтений:   
![image](https://user-images.githubusercontent.com/89806836/193798588-336c0df1-92d7-41a5-a423-ddf260428bb3.png)   
9. Сбор **скаффолдов** из контигов и подрезанных чтений:   
![image](https://user-images.githubusercontent.com/89806836/193798736-c86b99d0-f5cc-4ff4-be3d-fcade86237ca.png)   
10. Уменьшение количества гэпов:   
![image](https://user-images.githubusercontent.com/89806836/193798863-407999ad-deae-44e5-a66a-b37eb1cd81ee.png)   
### Статистика multiQC:   
1. Для исходных чтений:   
![image](https://user-images.githubusercontent.com/89806836/193799249-5b6229c1-4e06-4dd7-9cf0-29dd4b10daa2.png)   
![fastqc_per_sequence_quality_scores_plot](https://user-images.githubusercontent.com/89806836/193799519-e4a0c514-db94-4942-b0b7-cf40c650bddb.png)   
[Ссылка на полный отчет]   
2. Для подрезанных чтений:   
![image](https://user-images.githubusercontent.com/89806836/193799736-265f441b-06b3-40b1-b8e6-44454b7ad2df.png)   
![fastqc_per_sequence_quality_scores_plot (1)](https://user-images.githubusercontent.com/89806836/193799866-bdb8eac2-137c-4115-99dc-66e0d205f63c.png)   
[Ссылка на полный отчет]   
### [Ссылка на ноутбук Google Colab](https://colab.research.google.com/drive/1n30yJRxBCYKbarCmZ0HE_wolGy2c8fhk)   
### Результаты работы кода:   
1. Основная часть задания:   
2. Бонусная часть задания:   
_Примечание: количество случайных чтений было сокращено в половину: 2500000 для типа paired_end и 750000 для типа mate_pairs._
