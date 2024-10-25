# external_src_demo
A demo repo to demonstrate how we can customize the local Astro environment to load Dags from folders outside of the astro project

## How it works
The [docker-compose.override.yml](astro_runtime%2Fdocker-compose.override.yml) has been edited to mount the `src` folder to the Airflow dags folder. 

## Running your local Astro development environment

### Prerequisites
1. [install the astro cli](https://www.astronomer.io/docs/astro/cli/install-cli)

2. Start local development environment:
 ```
 cd astro_runtime
 astro dev start
 ```

3. Open your browser and navigate to `http://localhost:8080/home`