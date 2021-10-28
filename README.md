# Tech-Excellence-Team-1
October 2021 Tech Excellence Course

Code and materials for launching an apache EC2 web server that allows the user to upload an image to S3.  A Lambda is triggered and call Rekognition to apply object-detection labels and input the labels into DynamoDB.  Jenkins is deployed on a separate EC2 that manages an automated deployment of updates to the apache server.
