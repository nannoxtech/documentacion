# Table: users

**Description**: No description available

| Column Name | Data Type | Max Length | Is Nullable | Default | Primary Key | Foreign Key |
|-------------|-----------|------------|-------------|---------|-------------|-------------|
| id | bigint |  | false | nextval('wallet.users_id_seq'::regclass) | users | users |
| user | bigint |  | false |  |  |  |
| username | character varying | 30 | false |  |  |  |
| password | character varying | 60 | false |  |  |  |
| oauth_client_id | bigint |  | false |  | users | oauth_clients |
| created_at | timestamp without time zone |  | true |  |  |  |
| updated_at | timestamp without time zone |  | true |  |  |  |
| whitelabel_id | integer |  | true |  |  |  |