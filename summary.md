# 23 Post Processor
# Resume

## What is Post Processors 
The test plan elements that are used to perform certain actions after the processing of a sampler request.
These post processors are usually used for extracting certain values from the response of a sample request e.g. we 
can extract the value of session variables from an HTTP request and pass the session variables's value to the subsequent request.

## JSON Path
- Digunakan untuk ekstrak isi dari json response 
- Beberapa eksperesi yang umum digunakan :
1. $ = root element
2. . = child operator (object)
3. [] = child operator (array)
4. .. = recursive descent (langsung ke objek)
5. * = willcard (all things)
6. [startend] = array slice operator borrowed

## Let's do exercise
Specification :
- BASE_URL : https://reqres.in
- PATH : 
1. path 1 : [GET] /api/users?page=2
2. path 2 : [GET] /api/unknown/${id}
3. path 3 : [POST] /api/users
