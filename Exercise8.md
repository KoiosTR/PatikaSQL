# Patika SQL Egitim Odev 8

1. Test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```
CREATE TABLE employee (
	id SERIAL PRIMARY KEY,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
)
```

2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```
insert into employee (id, name, email, birthday) values (1, 'Kathrine', 'krozzier0@so-net.ne.jp', '2004-10-17');
insert into employee (id, name, email, birthday) values (2, 'Fayth', 'fhenderson1@cbslocal.com', '2013-01-31');
insert into employee (id, name, email, birthday) values (3, 'Derick', 'dpunter2@stumbleupon.com', '2002-03-27');
insert into employee (id, name, email, birthday) values (4, 'Roseanna', 'rcokely3@wordpress.org', '2007-01-06');
insert into employee (id, name, email, birthday) values (5, 'Marge', 'mmcgunley4@vistaprint.com', '2009-03-27');
insert into employee (id, name, email, birthday) values (6, 'Mahmud', 'mrhymer5@bloomberg.com', '2003-03-04');
insert into employee (id, name, email, birthday) values (7, 'Lennie', 'ljerzak6@theglobeandmail.com', '2013-11-21');
insert into employee (id, name, email, birthday) values (8, 'Pepillo', 'pschenkel7@washington.edu', '2011-10-13');
insert into employee (id, name, email, birthday) values (9, 'Silvan', 'scollymore8@cbsnews.com', '2002-06-09');
insert into employee (id, name, email, birthday) values (10, 'Tymothy', 'tthickpenny9@gmpg.org', '2010-04-07');
insert into employee (id, name, email, birthday) values (11, 'Jennifer', 'jcoolinga@yale.edu', '2006-01-18');
insert into employee (id, name, email, birthday) values (12, 'Madge', 'mventonb@yale.edu', '2013-05-04');
insert into employee (id, name, email, birthday) values (13, 'Julina', 'jhartellc@pbs.org', '2000-08-14');
insert into employee (id, name, email, birthday) values (14, 'Anastasia', 'agormand@t.co', '2006-04-13');
insert into employee (id, name, email, birthday) values (15, 'Chastity', 'cabbisone@ucla.edu', '2011-10-13');
insert into employee (id, name, email, birthday) values (16, 'Crystal', 'cvennardf@google.pl', '2007-05-20');
insert into employee (id, name, email, birthday) values (17, 'Meghann', 'mselbyg@guardian.co.uk', '2003-12-27');
insert into employee (id, name, email, birthday) values (18, 'Gussi', 'gmcettrickh@wordpress.com', '2004-03-17');
insert into employee (id, name, email, birthday) values (19, 'Nessy', 'nhundleyi@google.fr', '2009-03-24');
insert into employee (id, name, email, birthday) values (20, 'Celinda', 'cfilippoj@wikispaces.com', '2012-09-18');
insert into employee (id, name, email, birthday) values (21, 'Benny', 'bpitcherk@barnesandnoble.com', '2007-08-09');
insert into employee (id, name, email, birthday) values (22, 'Harriett', 'htipplel@trellian.com', '2003-10-24');
insert into employee (id, name, email, birthday) values (23, 'Julieta', 'jgarzm@tamu.edu', '2003-02-11');
insert into employee (id, name, email, birthday) values (24, 'Garrott', 'gtommasin@macromedia.com', '2009-04-22');
insert into employee (id, name, email, birthday) values (25, 'Nikolia', 'nfildeo@utexas.edu', '2012-12-11');
insert into employee (id, name, email, birthday) values (26, 'Lula', 'lsweetenhamp@ucla.edu', '2009-06-12');
insert into employee (id, name, email, birthday) values (27, 'Lane', 'lbrouneq@github.io', '2013-08-26');
insert into employee (id, name, email, birthday) values (28, 'Bibbye', 'bbuckstonr@wix.com', '2010-09-30');
insert into employee (id, name, email, birthday) values (29, 'Alla', 'atwydells@china.com.cn', '2005-02-07');
insert into employee (id, name, email, birthday) values (30, 'Lemar', 'lenstont@bravesites.com', '2001-01-17');
insert into employee (id, name, email, birthday) values (31, 'Devlen', 'dpendleberyu@prnewswire.com', '2005-06-23');
insert into employee (id, name, email, birthday) values (32, 'Griff', 'gmandrakev@si.edu', '2005-10-18');
insert into employee (id, name, email, birthday) values (33, 'Gaynor', 'glearmonthw@abc.net.au', '2002-09-21');
insert into employee (id, name, email, birthday) values (34, 'Angelina', 'awordesworthx@nature.com', '2000-04-29');
insert into employee (id, name, email, birthday) values (35, 'Ode', 'ogareisry@4shared.com', '2015-01-02');
insert into employee (id, name, email, birthday) values (36, 'Giulio', 'gchristescuz@wikimedia.org', '2003-06-07');
insert into employee (id, name, email, birthday) values (37, 'Hugo', 'hjockle10@diigo.com', '2009-12-17');
insert into employee (id, name, email, birthday) values (38, 'Elianora', 'eiacovo11@pen.io', '2001-12-04');
insert into employee (id, name, email, birthday) values (39, 'Bartram', 'bdiviney12@rakuten.co.jp', '2011-09-17');
insert into employee (id, name, email, birthday) values (40, 'Sandy', 'scicculi13@live.com', '2012-08-14');
insert into employee (id, name, email, birthday) values (41, 'Ailsun', 'arockell14@biblegateway.com', '2004-10-22');
insert into employee (id, name, email, birthday) values (42, 'Erminie', 'edixie15@symantec.com', '2014-01-21');
insert into employee (id, name, email, birthday) values (43, 'Kelcie', 'kjeavon16@auda.org.au', '2014-04-04');
insert into employee (id, name, email, birthday) values (44, 'Homer', 'hfreire17@dropbox.com', '2010-11-20');
insert into employee (id, name, email, birthday) values (45, 'Chantal', 'caskew18@upenn.edu', '2013-06-18');
insert into employee (id, name, email, birthday) values (46, 'Aeriela', 'aferrey19@latimes.com', '2004-07-03');
insert into employee (id, name, email, birthday) values (47, 'Carline', 'calcalde1a@wordpress.org', '2001-08-30');
insert into employee (id, name, email, birthday) values (48, 'Hillel', 'hbrockest1b@samsung.com', '2014-03-16');
insert into employee (id, name, email, birthday) values (49, 'Orran', 'olesaunier1c@seesaa.net', '2006-10-26');
insert into employee (id, name, email, birthday) values (50, 'Wilona', 'wkimberly1d@twitter.com', '2005-04-14');
```

3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```
UPDATE employee
SET name = 'Arda', email = 'arda@gonca.com'
WHERE id = 50;
----
UPDATE employee
SET name = 'Gülistan', email = 'yilmaz@top.com'
WHERE id = 31;
----
UPDATE employee
SET name = 'Samet', email = 'samet@gungor.com'
WHERE id = 41;
----
UPDATE employee
SET name = 'Ali', email = 'ali@gungor.com'
WHERE id = 29;
----
UPDATE employee
SET name = 'Hakan', email = 'hakan@yagar.com'
WHERE id = 10;
```

4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```
DELETE FROM employee WHERE id = 47;
DELETE FROM employee WHERE id = 1;
DELETE FROM employee WHERE id = 10;
DELETE FROM employee WHERE id = 21;
DELETE FROM employee WHERE id = 15;
```
