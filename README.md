
Add Players:

curl -X POST http://localhost:3000/api/players -H "Content-Type: application/json" -d "{\"name\":\"John Doe\", \"position\":\"Goalkeeper\"}"
curl -X POST http://localhost:3000/api/players -H "Content-Type: application/json" -d "{\"name\":\"Jane Smith\", \"position\":\"Forward\"}"
curl -X POST http://localhost:3000/api/players -H "Content-Type: application/json" -d "{\"name\":\"Mike Johnson\", \"position\":\"Defender\"}"


Add Events:

curl -X POST http://localhost:3000/api/events -H "Content-Type: application/json" -d "{\"location\":\"Community Park\", \"date\":\"2024-12-24\"}"
curl -X POST http://localhost:3000/api/events -H "Content-Type: application/json" -d "{\"location\":\"Main Stadium\", \"date\":\"2024-12-31\"}"


Add Votes:

curl -X POST http://localhost:3000/api/vote -H "Content-Type: application/json" -d "{\"player_id\":1, \"event_id\":1, \"status\":\"yes\"}"
curl -X POST http://localhost:3000/api/vote -H "Content-Type: application/json" -d "{\"player_id\":2, \"event_id\":1, \"status\":\"no\"}"
curl -X POST http://localhost:3000/api/vote -H "Content-Type: application/json" -d "{\"player_id\":3, \"event_id\":2, \"status\":\"yes\"}"
