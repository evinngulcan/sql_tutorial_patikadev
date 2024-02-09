Ödev-8 Soru Çözümleri 

1-test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

CREATE TABLE employee (
     id INT NOT NULL,
     name VARCHAR(50) NOT NULL,
     birthday DATE NOT NULL,
     email VARCHAR(100)
  );

2-Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

insert into employee (id, name, email, birthday) values (1, 'Barbe', 'bwethered0@vinaora.com', '2023-08-06');
insert into employee (id, name, email, birthday) values (2, 'Lovell', 'llabden1@blogger.com', '2023-11-15');
insert into employee (id, name, email, birthday) values (3, 'Brett', 'bguild2@ustream.tv', '2023-12-01');
insert into employee (id, name, email, birthday) values (4, 'Gerladina', 'gweinberg3@businessinsider.com', '2023-08-10');
insert into employee (id, name, email, birthday) values (5, 'Amby', 'aingles4@zimbio.com', '2023-08-17');
insert into employee (id, name, email, birthday) values (6, 'Kimmie', 'kcroysdale5@bloglovin.com', '2023-12-13');
insert into employee (id, name, email, birthday) values (7, 'Florinda', 'fvenus6@feedburner.com', '2023-10-17');
insert into employee (id, name, email, birthday) values (8, 'Caleb', 'cbowater7@pbs.org', '2023-08-16');
insert into employee (id, name, email, birthday) values (9, 'Hanna', 'hmaddox8@fc2.com', '2023-10-05');
insert into employee (id, name, email, birthday) values (10, 'Meriel', 'mgregson9@slashdot.org', '2023-11-19');
insert into employee (id, name, email, birthday) values (11, 'Sharai', 'slacka@ucla.edu', '2023-06-08');
insert into employee (id, name, email, birthday) values (12, 'Rosina', 'rredonb@prnewswire.com', '2023-05-21');
insert into employee (id, name, email, birthday) values (13, 'Jenni', 'jobroganec@domainmarket.com', '2023-12-04');
insert into employee (id, name, email, birthday) values (14, 'Pippo', 'pcockrend@springer.com', '2023-09-13');
insert into employee (id, name, email, birthday) values (15, 'Felice', 'fputtergille@weebly.com', '2024-01-13');
insert into employee (id, name, email, birthday) values (16, 'Axe', 'aduigedf@hao123.com', '2023-11-22');
insert into employee (id, name, email, birthday) values (17, 'Bryce', 'bwasbroughg@auda.org.au', '2023-03-13');
insert into employee (id, name, email, birthday) values (18, 'Jedidiah', 'jskivingtonh@free.fr', '2023-09-22');
insert into employee (id, name, email, birthday) values (19, 'Cora', 'cdawtoni@loc.gov', '2024-02-02');
insert into employee (id, name, email, birthday) values (20, 'Angie', 'askidmorej@ebay.com', '2023-05-20');
insert into employee (id, name, email, birthday) values (21, 'Rycca', 'rjoyek@hibu.com', '2023-08-21');
insert into employee (id, name, email, birthday) values (22, 'Wilfred', 'wdanelll@tripod.com', '2023-09-24');
insert into employee (id, name, email, birthday) values (23, 'Lilas', 'lkurtenm@rakuten.co.jp', '2023-06-29');
insert into employee (id, name, email, birthday) values (24, 'Berny', 'bsturgeonn@abc.net.au', '2023-03-12');
insert into employee (id, name, email, birthday) values (25, 'Rafaelita', 'rhastieo@irs.gov', '2023-11-06');
insert into employee (id, name, email, birthday) values (26, 'Agneta', 'ajimesp@abc.net.au', '2023-12-31');
insert into employee (id, name, email, birthday) values (27, 'Barnett', 'bbulledq@i2i.jp', '2024-02-04');
insert into employee (id, name, email, birthday) values (28, 'Lorinda', 'lfreathyr@about.com', '2023-04-17');
insert into employee (id, name, email, birthday) values (29, 'Becki', 'borricks@psu.edu', '2024-01-05');
insert into employee (id, name, email, birthday) values (30, 'Trudey', 'tarstallt@dagondesign.com', '2024-02-03');
insert into employee (id, name, email, birthday) values (31, 'Sonni', 'ssidwicku@cargocollective.com', '2023-09-02');
insert into employee (id, name, email, birthday) values (32, 'Duke', 'ddobbsonv@addthis.com', '2023-08-19');
insert into employee (id, name, email, birthday) values (33, 'Robinet', 'rkestevenw@booking.com', '2023-03-16');
insert into employee (id, name, email, birthday) values (34, 'Heath', 'hduffanx@friendfeed.com', '2023-06-05');
insert into employee (id, name, email, birthday) values (35, 'Glen', 'gvolantey@nps.gov', '2023-07-28');
insert into employee (id, name, email, birthday) values (36, 'Melly', 'mswinburnez@harvard.edu', '2023-12-23');
insert into employee (id, name, email, birthday) values (37, 'Gilles', 'grathe10@instagram.com', '2023-06-30');
insert into employee (id, name, email, birthday) values (38, 'Zacharia', 'zshoutt11@nhs.uk', '2023-06-19');
insert into employee (id, name, email, birthday) values (39, 'Jedediah', 'jauton12@cornell.edu', '2023-11-04');
insert into employee (id, name, email, birthday) values (40, 'Andra', 'acranstoun13@slashdot.org', '2023-08-29');
insert into employee (id, name, email, birthday) values (41, 'Jannelle', 'jknocker14@com.com', '2023-11-09');
insert into employee (id, name, email, birthday) values (42, 'Jamima', 'jsoares15@exblog.jp', '2023-09-06');
insert into employee (id, name, email, birthday) values (43, 'Marj', 'mseton16@princeton.edu', '2023-09-07');
insert into employee (id, name, email, birthday) values (44, 'Camey', 'clichfield17@4shared.com', '2023-06-17');
insert into employee (id, name, email, birthday) values (45, 'Marys', 'mgait18@columbia.edu', '2023-09-24');
insert into employee (id, name, email, birthday) values (46, 'Rodney', 'rjost19@alexa.com', '2023-08-23');
insert into employee (id, name, email, birthday) values (47, 'Brigid', 'bbassett1a@mtv.com', '2024-02-01');
insert into employee (id, name, email, birthday) values (48, 'Dory', 'dkelloch1b@shareasale.com', '2024-02-06');
insert into employee (id, name, email, birthday) values (49, 'Fraze', 'fcooling1c@lycos.com', '2024-02-07');
insert into employee (id, name, email, birthday) values (50, 'Lida', 'lhansill1d@archive.org', '2023-07-07');

3-Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

  UPDATE employee 
  SET name = 'Ahmet Taş'
  birthday = '1987-04-03'
  email = 'ahmet@gamil.com'
  WHERE id = 30;

  UPDATE employee
  SET name = 'Marys'
  birthday = '2023-09-23'
  email = 'marys@gmail.com'
  WHERE id = 43;
  
  UPDATE employee
  SET name = 'Dory'
  WHERE name like 'S%'
  RETURNING *;
  
  UPDATE employee
  SET name = 'ALİ'
  WHERE name = 'Lida'
  RETURNING *;
  
  UPDATE employee
  SET name = 'Camey'
  birthday = '2023-09-23'
  WHERE id BETWEEN  27 AND 35;

     
4-Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

  DELETE FROM employee 
  WHERE name = 'Axe'
  RETURNING *;
  
  DELETE FROM employee 
  WHERE id>45;


  DELETE FROM employee 
  WHERE email = 'rkestevenw@booking.com' and birthday = '2023-12-23'
  RETURNING *;
  
  DELETE FROM employee 
  WHERE name like '%a'
  RETURNING *;
  
  DELETE FROM employee 
  WHERE email like '.com'
  RETURNING *;
  









