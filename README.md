## Serverless Node.js Basic restapi

### Routes:

post /todos <br />
get /todos <br />
get /todos/{id} <br />
update /todos/{id} <br />
delete /todos/{id} <br />

### Deployment

`sls deploy`

### Requirements

- configure your AWS profile ie add secret and access key by editiing config and credentials by navigating to `cd ~/.aws`
- install serverless cli globally `npm i -g serverless`
