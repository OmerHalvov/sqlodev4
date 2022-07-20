# sqlodev4
Patika Sql Ödev-4

Cevap-1:
select distinct replacement_cost from film;

Cevap-2:
select count (replacement_cost) from film;

Cevap-3:
select count(*) from film  where title like 'T%' and rating='G'

Cevap-4:
select count(country) from country where length(country)=5;

Cevap-5:
select count(*) from city where city ilike'%R';
