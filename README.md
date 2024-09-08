# Provinciya_Omsk_Hack
## Репозиторий команды "Provinciya" для окружного хакатона СФО
## Краткое описание файлов хранящихся в репозитории:
main.py - Файл, использущийся для итогового предсказания. Содержит в себе все необходимые этапы предобработки данных. На выходе получаем файл 'submission.csv' с результатами работы наших моделей  
provinciya_Sal.ipynb - Ноутбук, содержащий в себе все этапы разработки модели предсказания заработной платы с подробными комментариями. 
 
 provinciya_Vac.ipynb - Ноутбук, содержащий в себе все этапы разработки модели предсказания подходящей вакансии с подробными комментариями.
## Описание основных признаков для модели регрессии
required_experience - Требуемый опыт  
federalDistrictCode - Код федерального округа  
code_professional_sphere - Код профессиональной сферы  
education - Образование  
change_time - Время изменения  
distance_to_moscow - Расстояние до Москвы  
company_business_size - Размер компании  
busy_type - Вид занятости  
schedule_type - График работы  
need_medcard - Необходимость медкнижки  
code_profession - Код профессии  
accommodation_capability - Предоставление жилья  
distance_to_nearest - Расстояние до ближайшего областного центра  
company_code - Код компании  
transport_compensation - Компенсация транспорта    
is_quoted - Квотируемая вакансия  
work_places - Количество требуемых рабочих мест  
source_type - Тип источника вакансии  
metro_ids - ID станции метро  
is_mobility_program - Возможность переезда
## Используемые технологии
Работа с данными: Numpy, Pandas  
ML: pytorch, catboost, transformers, scikit-learn
