# Sqlite database with Senzing database schema and configuration

Sqlite database with Senzing database schema installed and the Senzing configuration.

The database schema includes tables, indexes, and a few insertions.
The various SQL files for creating the schema can be found in
`/opt/senzing/er/resources/schema`

The Senzing configuration includes the default Senzing configuration information specified at
`/opt/senzing/er/resources/templates/g2config.json`.

## Download

1. :pencil2: Specify where to download the file.

   Example:

    ```console
    export SENZING_DATABASE_DIRECTORY=~/senzing-database
    ```

1. If needed, create the directory.

   Example:

    ```console
    mkdir -p ${SENZING_DATABASE_DIRECTORY}
    ```

1. Download file.

    ```console
    curl \
      --output ${SENZING_DATABASE_DIRECTORY}/sz.db \
      https://raw.githubusercontent.com/senzing-garage/demo-databases/refs/heads/main/sqlite/with-config/sz.db
    ```

## Details

1. [x] Senzing database schema
1. [x] Senzing configuration
