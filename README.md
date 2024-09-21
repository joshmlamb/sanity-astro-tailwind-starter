# Sanity + Astro + Tailwind Starter

To get started, follow these steps:

1) Clone the repository
    
    ```
    git clone ...
    ```

2) Install dependencies

    ```
    npm install
    ```

3) Copy `.env` example

    ```
    cp .env.example .env
    ```

4) Update `.env` with the required details and update the `projectId` and `dataset` values in `astro.config.mjs`. An API token will need to be generated in Sanity with `Viewer` permissions, this can be named as you like.

5) Get building! Visit `/admin` to edit content

    ```
    npm run dev
    ```