# fhirapi
test fhir api w consent


ubuntu 16 container
openjdk8
java_home declared
sample springboot api on port 8087

docker build -t fhirapi .

docker run -dti -p 8087:8087 fhirapi
