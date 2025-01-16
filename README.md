NBA DATALAKE
------------
This challenge defines the creation of a data querying system utilizing python script to essentially query data from an API and process the queried results

Visit my Medium for full documentation# NBADatalake

Query Sample for Athena 
-----------------------
SELECT FirstName, LastName, Position, Team
FROM nba_players
WHERE Position = 'PG';
