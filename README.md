--SELECT * FROM movies

--select title, IMDB_score from movies where IMDB_score <= 6.5;

--select * from movies where genre = 'Sci-fi';

--select * from movies WHERE (rating BETWEEN 'G' AND 'PG') AND (runtime < 100);


--select AVG(runtime) from movies where IMDB_score < 7.5 group by genre = 'horror';
--select AVG(runtime) from movies where IMDB_score < 7.5 group by genre = 'sci-fi'';
--select AVG(runtime) from movies where IMDB_score < 7.5 group by genre = 'documentary';
--select AVG(runtime) from movies where IMDB_score < 7.5 group by genre = 'comedy';
--select AVG(runtime) from movies where IMDB_score < 7.5 group by genre = 'animation';


--UPDATE movies set rating = 'R' where title = 'Starship Troopers';

SELECT id, rating from movies where genre = 'Horror' OR genre = 'Documentary';

--select AVG(IMDB_score) from movies WHERE rating = 'PG';
--select AVG(IMDB_score) from movies WHERE rating = 'TV-14';
--select AVG(IMDB_score) from movies WHERE rating = 'PG-13';
--select AVG(IMDB_score) from movies WHERE rating = 'R';
--select AVG(IMDB_score) from movies WHERE rating = 'PG';
--select AVG(IMDB_score) from movies WHERE rating = 'G';

--select MAX(IMDB_score) from movies WHERE rating = 'PG';
--select MAX(IMDB_score) from movies WHERE rating = 'TV-14';
--select MAX(IMDB_score) from movies WHERE rating = 'PG-13';
--select MAX(IMDB_score) from movies WHERE rating = 'R';
--select MAX(IMDB_score) from movies WHERE rating = 'PG';
--select MAX(IMDB_score) from movies WHERE rating = 'G';

--select MIN(IMDB_score) from movies WHERE rating = 'PG';
--select MIN(IMDB_score) from movies WHERE rating = 'TV-14';
--select MIN(IMDB_score) from movies WHERE rating = 'PG-13';
--select MIN(IMDB_score) from movies WHERE rating = 'R';
--select MIN(IMDB_score) from movies WHERE rating = 'PG';
--select MIN(IMDB_score) from movies WHERE rating = 'G';

--select * from movies having count (*) > 1;

--delete from movies where rating = 'R';
