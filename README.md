# Parrot
Project localization system built with Go and Angular 2.
Currently in heavy development, breaking changes guaranteed :)

TODO:

General:
- Add exports feature (JSON, csv, xml (android resources), strings (apple strings), Excel sheet)
- Add snapshots feature
- Add forgotten password feature

Backend:
- Communicate only via SSL within the microservices network
- Support migrations via .env files (e.g. db.migrations.strategy="create/drop" or "up")
- Add copy web app build to nginx as a static server
- Add timestamps to DB tables
- Add tests

Frontend:
- Handle role based menu display
- Handle api errors presentation
- Add API error-message map
- Add app localization
- Cleanup CSS and switch to using SASS
- Add tests
