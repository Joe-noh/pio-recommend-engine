
```
./bin/up

cd ./templates/MyRecommendation
../../bin/pio-docker build --verbose
../../bin/pio-docker train
../../bin/pio-docker deploy

curl -H "Content-Type: application/json" -d '{ "user": "2", "num": 4 }' http://localhost:8000/queries.json
```
`
