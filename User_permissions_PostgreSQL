--create etl user
CREATE USER etl WITH PASSWORD 'Password1';
--grant connect
GRANT CONNECT ON DATABASE "AdventureWorks" To etl;
--grant table permissions
GRANT SELECT, INSERT, UPDATE, DELETE ON ALL TABLES IN SCHEMA public To etl;
