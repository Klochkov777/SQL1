# data base 1
<<<<<<< HEAD
=======
# Домашнее задание к занятию "`sdb-homeworks`" - `Klochkov Vladimir`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1
* [link to screen]()

### Задание 2
* [link to screen]()

### Задание 3

* [link to screen]()

### Задание 4
* [link to screen]()

простыня всех запросов:

* select distinct district from address a
WHERE district not LIKE '% %' and district LIKE 'K%a';  

* select * from payment p where p.amount > 10.00 
and p.payment_date between '2005-06-15' and '2005-06-18 23:59:59.999';  

* SELECT * FROM rental r 
order by r.rental_date DESC 
limit 5;  

* select c.customer_id, c.store_id, REPLACE(LOWER(c.first_name), 'll', 'pp') as first_name , 
REPLACE (LOWER(c.last_name), 'll', 'pp') as last_name, c.email, c.active  from customer c 
WHERE c.first_name = 'Kelly' and c.active = 1 OR c.first_name = 'Willie' AND active = 1;   



