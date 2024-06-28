# functions-assignments
#weather observation station 8
#task 1


SELECT CITY
FROM STATION
WHERE lower(SUBSTR(CITY,1,1)) IN  ('a' , 'e' , 'i' ,'o' , 'u') and
                lower(SUBSTR(CITY,-1)) IN ('a' , 'e' , 'i' , 'o' , 'u');
