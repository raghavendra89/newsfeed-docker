# NewsFeed - A news aggregator

Solution for the innoscripta take home challenge.

### How to run this?

- Clone this repository.
- Pull the `frontend` and `backend` submodules with this command: `git submodule update --init`.
- Run the docker compose command: `docker-compose up -d`.

**Voila! That's it—you should now be up and running and see a screen similar to this one:**



**Now go to the browser and access the NewsFeed app at [http://localhost:3000](http://localhost:3000).**

### Next Steps:

Initially news database is empty. Follow these steps to pull the articles from the news sources.

1. Login as admin user using the shared credentials.
2. Navigate to Admin page.
3. Pull the news articles from the provided sources.

Alternatively you can run the below artisan command in the backend docker container:

`php artisan news:pull --source=SOURCE_OPTION`

Available source options are: NewsApi, NewsData, TheGuardian, NyTimes.