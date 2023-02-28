# STAT624 Redis Docker Environment
**Contents**: Dockerfiles and docker compose for STAT 624 Redis environment

## Quick start guide
1. Download zipped folder containing all files in this repository.
2. Unzip folder and store in local directory of your choosing.
3. In a terminal window, navigate to the local directory containing `docker-compose.yml`.
4. Run the command `docker compose up`.  The Docker images will be downloaded to your system and containers will be created accordingly.
5. Open a web browser window and type `localhost:8081` to open the Redis Commander GUI to interact with the database.
6. Populate the sample database using `redis_leaderboard_dataload.txt`.

