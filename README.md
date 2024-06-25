# commands

export NODE_OPTIONS=--openssl-legacy-provider

npx insomnia-documenter --config <Insomnia_2023-11-14.json> --output <insomnia>

cat your_dump.sql | docker exec -i your-db-container psql -U postgres
