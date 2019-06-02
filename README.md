Please follow the instructions on my article published on Data Driven Investor.

https://medium.com/datadriveninvestor/from-model-inception-to-deployment-adce1f5ed9d6


## How to run:


`
cd dockerized_scalable_ml && 
docker-compose up
`

## Sample request:

`
curl --header "Content-Type: application/json" --request POST --data'[{"sepal_length":6.3,"sepal_width":2.3,"petal_length":4.4,"petal_width":1.3}]' http://localhost:8080/predict
`
