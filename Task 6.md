#Task 6

select City.Name from City INNER JOIN Country ON City.CountryCode = Country.Code where Country.Continent='Africa';
