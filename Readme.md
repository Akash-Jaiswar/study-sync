eb clone
eb deploy my-study-sync-cloned
eb swap study-sync-prod-env2 --destination_name my-study-sync-cloned
eb terminate study-sync-prod-env2 





for docker 


Limited\Documents\AWS_CERTIFICATIONS\AWS_DEVELOPER_ASSOCIATE\AWS_EB\study-sync>eb init -p docker study-sync


eb create --single










ecr  commands 

-----------------




for login using aws cli  


aws ecr get-login-password --region ap-south-1 | docker login --username AWS --password-stdin 419445948502.dkr.ecr.ap-south-1.amazonaws.com














docker tag 0c6e0e8ace9f 419445948502.dkr.ecr.ap-south-1.amazonaws.com/study-sync




419445948502.dkr.ecr.ap-south-1.amazonaws.com/study-sync



after this   --  eb init 


with configurations regions , application name , codecommout used or not 



eb create --single -- for creating elastic beanstalk application 

