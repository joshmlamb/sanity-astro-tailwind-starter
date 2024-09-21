# Sanity + Astro + Tailwind Starter

To get started, follow these steps:

1) Create your project directory and change into it
    ```
    mkdir project-name && cd project-name
    ```

2) Clone the repository
    ```
    git clone https://github.com/joshmlamb/astro-sanity-tailwind-starter.git
    ```

3) Install dependencies
    ```
    npm install
    ```

4) Copy `.env` example
    ```
    cp .env.example .env
    ```

5) Update `.env` with the required details and update the `projectId` and `dataset` values in `astro.config.mjs`. An API token will need to be generated in Sanity with `Viewer` permissions, this can be named as you like.

6) Get building! Visit `/admin` to edit content
    ```
    npm run dev
    ```