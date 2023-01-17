# Image Filter Project

Content
=============

###Elastic Bean Stalk URL:
                
http://image-filter-start-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://nationaltoday.com/wp-content/uploads/2020/08/international-cat-day.jpg

## Specifications to submit the project 

#### 1.  Development Server:

1- Starting the server with npm run dev runs a local instance of the server with no errors
<img width="661" alt="image" src="https://user-images.githubusercontent.com/54766487/212855510-42eaac50-aa00-4572-8ddb-a301a3d1fb6e.png">

2- The stubbed @TODO1 endpoint in src/server.ts is completed and accepts valid requests including:

<img width="953" alt="image" src="https://user-images.githubusercontent.com/54766487/212856225-821e9e1c-2f9c-4ac8-bfdc-86e7ae53743b.png">

3- Successful responses have a 200 code, at least one error code for caught errors (i.e. 422)

1. Sending Wrong url "http://localhost:8082/filteredimage?image_url=https://nationaltoday.com/wp-content/uploads/2020/08/international-cat-da.jpg"
<img width="677" alt="image" src="https://user-images.githubusercontent.com/54766487/212856678-6c8cb2e4-a10c-4e9f-9a0f-b5da0c2b5916.png">

2. not sending a url "http://localhost:8082/filteredimage?image_url="
<img width="667" alt="image" src="https://user-images.githubusercontent.com/54766487/212856918-2e1b66e5-8110-4965-be5d-abbfe4ed64b4.png">

#### 2.  Elastic Beanstalk Deployment:
1- The project demonstrates the ability to create functional cloud deployments 
<img width="960" alt="image" src="https://user-images.githubusercontent.com/54766487/212857482-143309b4-ce4d-44e8-b4ca-31633beacf8b.png">

2- The project was deployed using the AWS Elastic Beanstalk CLI eb init, eb create, and eb deploy commands.
<img width="665" alt="image" src="https://user-images.githubusercontent.com/54766487/212857885-5f6d5903-3ac0-4869-a6d6-d6603ae99e70.png">

<img width="674" alt="image" src="https://user-images.githubusercontent.com/54766487/212857983-b1f7c7c3-5601-425b-ad01-7b3d80a04f0f.png">

<img width="670" alt="image" src="https://user-images.githubusercontent.com/54766487/212858096-c6df096a-7e22-4a1c-9c45-33ed4ce05b9f.png">


