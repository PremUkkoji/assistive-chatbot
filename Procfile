action-worker: python -m rasa_core_sdk.endpoint --actions actions
rasa-core-worker: python -m rasa_core.run --enable_api -d models/dialogue -u models/nlu/default/shoppingnlu --port 5002 --credentials credentials.yml --endpoints endpoints.yml