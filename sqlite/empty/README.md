# Empty Sqlite database

This is a zero-length file with no database.

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
      https://raw.githubusercontent.com/senzing-garage/demo-databases/refs/heads/main/sqlite/empty/sz.db
    ```

## Details

1. [ ] Senzing database schema
1. [ ] Senzing configuration
