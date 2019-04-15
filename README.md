# soccerleague
First version of tables
CREATE TABLE [dbo].[Team] 
(  
	 teamKey varchar(50),
	 code  varchar(10),
	 teamName  varchar(100)
);
CREATE TABLE [dbo].Match 
(  
	 matchDate datetime,
	 team1Code  varchar(10),
	 team2Code  varchar(10),
	 score1 int,
	 score2 int
);
