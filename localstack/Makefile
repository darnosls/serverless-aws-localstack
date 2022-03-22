run:
	docker-compose up -d --build

logs:
	docker logs -f localstack

logs-s3:
	docker logs -f localstack-s3-ui

down:
	docker-compose down

bash:
	docker exec -it localstack bash

clean:
	rm -rf data/data/recorded_api_calls.json
	rm -rf lambda/.serverless