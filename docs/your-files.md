# Your Files

Projects include instructor example files that end with `_case`.
Keep these as working examples.

You will generally copy the instructor file, rename it with your alias,
and run your version in addition to the instructor version.

## Choose Your Name (example: `buzz`)

You may use your real name or any professional alias.
You are **never required to use your real name**.

Naming rules:

- all lowercase
- no spaces (use underscores as needed)

## 1. Python Files

Copy the instructor Python file and rename the copy using your alias.
For example:

```text
src/streaming/kafka_producer_case.py
src/streaming/kafka_producer_buzz.py
src/streaming/data_engineering/derived_fields_dawson.py
src/streaming/data_validation/data_validation_dawson.py
src/streaming/data_validation/data_contract_dawson
src/streaming/kafka_consumer_dawson.py
src/streaming/kafka_producer_dawson.py
src/streaming/kafka_admin_dawson.py
```

## 2. Python File Execution Command

In your `README.md`, add a line with the execution command just after the instructor command.
Use this command to run your file. For example:

```shell
uv run python -m streaming.kafka_producer_case
uv run python -m streaming.kafka_producer_buzz
```

## Phase 4 & 5 Changes

```text
Changed KAFKA_CLEAR_TOPIC_ON_START=false in .env.
  That means it will reprocess older messages already stored in the topic and creating duplicates.
Changed KAFKA_CLEAR_TOPIC_ON_START=true in .env (back to original setting)
  This shows the latest consumed messages only.
Changed the Kafka topic set in .env: streaming-03-analytics-dawson
```

## 3. Data Files

You may modify the data/ files as needed for your project,
but it is not required.
