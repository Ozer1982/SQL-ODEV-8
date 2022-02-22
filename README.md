# SQL-ODEV-8
SQL-ODEV 8

test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.



CREATE TABLE employee (id SERIAL PRIMARY KEY, name VARCHAR(50) NOT NULL, birthday DATE, email VARCHAR(100));


insert into employee (id, name, birthday, email) values (1, 'Marja', '2006-02-08 08:11:08', 'mwortt0@gov.uk');

insert into employee (id, name, birthday, email) values (2, 'Marketa', '1997-09-28 15:05:20', 'mfero1@ycombinator.com');

insert into employee (id, name, birthday, email) values (3, 'Koo', '1984-09-25 11:03:35', 'kcorde2@ucsd.edu');

insert into employee (id, name, birthday, email) values (4, 'Janelle', '2005-05-08 10:14:11', 'jshurman3@mac.com');

insert into employee (id, name, birthday, email) values (5, 'Brana', '1997-04-29 11:49:53', 'bweyland4@goo.ne.jp');

insert into employee (id, name, birthday, email) values (6, 'Kat', '1981-11-14 08:29:30', 'kdietz5@mediafire.com');

insert into employee (id, name, birthday, email) values (7, 'Mayne', '1996-01-13 16:40:39', 'mchessman6@usda.gov');

insert into employee (id, name, birthday, email) values (8, 'Abel', '2017-05-12 08:03:35', 'akelcey7@jigsy.com');

insert into employee (id, name, birthday, email) values (9, 'Lonny', '2007-12-16 18:30:04', 'lhazeldene8@goo.ne.jp');

insert into employee (id, name, birthday, email) values (10, 'Dietrich', '1995-04-24 20:30:54', 'dburkett9@aol.com');

insert into employee (id, name, birthday, email) values (11, 'Chloette', '2010-01-07 14:51:53', 'clarensona@furl.net');

insert into employee (id, name, birthday, email) values (12, 'Lind', '2021-12-06 05:55:01', 'lmillisb@mit.edu');

insert into employee (id, name, birthday, email) values (13, 'Coleman', '2006-04-18 15:54:10', 'cmcnuttc@nih.gov');

insert into employee (id, name, birthday, email) values (14, 'Yelena', '1980-04-24 21:50:15', 'ybulbrookd@csmonitor.com');

insert into employee (id, name, birthday, email) values (15, 'Gilda', '1992-05-19 20:04:04', 'gstrobande@webnode.com');

insert into employee (id, name, birthday, email) values (16, 'Jilly', '1987-01-15 12:51:35', 'jsprittf@microsoft.com');

insert into employee (id, name, birthday, email) values (17, 'Allianora', '2021-02-24 03:06:24', 'aadamczykg@sohu.com');

insert into employee (id, name, birthday, email) values (18, 'Garrard', '1996-08-02 04:24:19', 'gweblingh@samsung.com');

insert into employee (id, name, birthday, email) values (19, 'Sandi', '1995-03-06 08:42:06', 'scarmei@salon.com');

insert into employee (id, name, birthday, email) values (20, 'Pepi', '1989-11-21 05:01:34', 'pcurringtonj@quantcast.com');

insert into employee (id, name, birthday, email) values (21, 'Lonee', '2016-05-18 22:07:44', 'lmcpakek@rambler.ru');

insert into employee (id, name, birthday, email) values (22, 'Timmi', '1980-06-23 08:03:27', 'tmapsonl@vinaora.com');

insert into employee (id, name, birthday, email) values (23, 'Ermengarde', '2008-08-13 23:13:07', 'evynehallm@yellowpages.com');

insert into employee (id, name, birthday, email) values (24, 'Kerry', '1981-04-18 07:33:39', 'knowern@weebly.com');

insert into employee (id, name, birthday, email) values (25, 'Waldemar', '1980-06-03 00:05:24', 'wbalcho@goodreads.com');

insert into employee (id, name, birthday, email) values (26, 'Ky', '1987-07-20 23:58:39', 'kpratep@ycombinator.com');

insert into employee (id, name, birthday, email) values (27, 'Sada', '2013-05-07 23:51:42', 'smacinerneyq@icq.com');

insert into employee (id, name, birthday, email) values (28, 'Malynda', '1988-01-30 10:04:04', 'mfulunr@sohu.com');

insert into employee (id, name, birthday, email) values (29, 'Constantia', '2010-09-11 15:05:35', 'cwinnings@nhs.uk');

insert into employee (id, name, birthday, email) values (30, 'Sophronia', '1991-06-12 08:26:05', 'shatzart@imageshack.us');

insert into employee (id, name, birthday, email) values (31, 'Darelle', '2015-05-04 10:47:01', 'dyushkovu@fda.gov');

insert into employee (id, name, birthday, email) values (32, 'Marybeth', '2021-05-25 02:02:33', 'mmaytev@unesco.org');

insert into employee (id, name, birthday, email) values (33, 'Anastasia', '2019-04-08 07:55:59', 'alarwellw@google.com');

insert into employee (id, name, birthday, email) values (34, 'Harald', '2015-02-17 14:14:36', 'hwonterx@canalblog.com');

insert into employee (id, name, birthday, email) values (35, 'Dexter', '2001-07-24 13:23:16', 'dgillisony@upenn.edu');

insert into employee (id, name, birthday, email) values (36, 'Lorilee', '2011-07-30 10:37:07', 'lronnayz@indiatimes.com');

insert into employee (id, name, birthday, email) values (37, 'Harri', '2017-06-01 07:09:27', 'hpaynton10@webeden.co.uk');

insert into employee (id, name, birthday, email) values (38, 'Webster', '1999-07-17 02:22:51', 'wlayburn11@oaic.gov.au');

insert into employee (id, name, birthday, email) values (39, 'Shanda', '1994-07-19 23:17:16', 'ssawdy12@tiny.cc');

insert into employee (id, name, birthday, email) values (40, 'Nate', '2014-11-03 22:03:12', 'nvaughanhughes13@fotki.com');

insert into employee (id, name, birthday, email) values (41, 'Josepha', '2004-11-05 23:40:38', 'jcullip14@earthlink.net');

insert into employee (id, name, birthday, email) values (42, 'Ring', '1995-04-21 06:53:39', 'rrosenblath15@latimes.com');

insert into employee (id, name, birthday, email) values (43, 'Clair', '2018-05-28 08:28:50', 'cgulk16@github.com');

insert into employee (id, name, birthday, email) values (44, 'Farra', '2022-02-21 03:25:03', 'fjane17@mit.edu');

insert into employee (id, name, birthday, email) values (45, 'Belia', '2015-01-16 23:45:45', 'bschaben18@jalbum.net');

insert into employee (id, name, birthday, email) values (46, 'Jessica', '1992-02-25 17:12:45', 'jbankhurst19@t.co');

insert into employee (id, name, birthday, email) values (47, 'Leona', '2014-06-15 19:52:17', 'lbeet1a@wikimedia.org');

insert into employee (id, name, birthday, email) values (48, 'Gilbertine', '2016-07-13 14:50:32', 'grampling1b@ask.com');

insert into employee (id, name, birthday, email) values (49, 'Rourke', '2005-10-06 15:31:49', 'rbarkas1c@reddit.com');

insert into employee (id, name, birthday, email) values (50, 'Alwin', '1999-10-12 01:06:43', 'areolfo1d@marketwatch.com');


UPDATE employee SET name = 'Cavit', birthday = '1982-01-01', email = 'cavit@gmail.com' WHERE id = 2;

UPDATE employee SET name = 'Can' WHERE id = 5;

UPDATE employee SET birthday = '1982-01-01' WHERE id = 7;

UPDATE employee SET email = 'cavit@gmail.com' WHERE id = 10;

UPDATE employee SET birthday = '1982-01-01', email = 'cavit@gmail.com' WHERE id = 15;



DELETE FROM employee WHERE name = 'Ring';

DELETE FROM employee WHERE name LIKE 'M%';

DELETE FROM employee WHERE id = 3;

DELETE FROM employee WHERE id > 20 RETURNING *;

DELETE FROM employee WHERE email LIKE '%gmail.com';


