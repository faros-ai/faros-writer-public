# Faros AI Writer

This repository is a simple typescript project that can help you get started writing arbitrary data to Faros AI!

## Usage

1. Clone the repository
1. Make any changes that you would like to the models that will be uploaded to Faros AI
1. Build the project

    ```sh
    npm i
    ```

1. Export the necessary environment variables or set them manually in the code

    ```sh
    # required
    $ export FAROS_API_KEY='<key>'
    # optional (default shown)
    $ export FAROS_API_URL='<url>' # https://prod.api.faros.ai
    $ export FAROS_GRAPH='<graph>' # default
    $ export FAROS_ORIGIN='<origin>' # faros-writer
    ```

1. Run the project

    ```sh
    npm run debug
    ```

    The command above will print the mutations it would write to the console. When you are ready to send the data to Faros AI execute:

    ```sh
    npm run send
    ```
