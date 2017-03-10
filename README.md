# 13bce0334
assignment for commutatus campus drive


create a database for storing the extracted data may be in the form of a spreadsheet or dataset.
name the columns as serial_no, movie_name, language, rating, release_ate, serial_code
assign constraints to the data.
search for the particular movie name using the primary key constraint.
traverse throught the data by displaying the name of the movies depending on constraints.
we can search for the movies released during a particular date or sorting according to rating etc


#themysql code is as follows

create table imdb(sno number(10) NOT NULL, movie_name varchar2(50) NOT NULL, language varchar2(10) NOT NULL, rating number(2) NOT NULL, realese_date date, serial_code char(50) PRIMARY KEY);
insert into imbd values(&erial_no, &movie_name, &language, &rating, &release_date, &serial_code);
select * from imdb where release_date=' ' && rating=' ';
END;
