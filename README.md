## This is the link of image-filter-app after deploying successfully on EB
http://image-filter-app-dev.us-west-2.elasticbeanstalk.com/filteredimage?image_url={{}}

## example with "real" image on the internet:
http://image-filter-app-dev.us-west-2.elasticbeanstalk.com/filteredimage?image_url=https://www.petcity.vn/media/news/1607_33164909_1952608778137726_6205015380826521600_n.jpg
or use suggestion from this post of Udacity's mentor (Joan):
http://image-filter-app-dev.us-west-2.elasticbeanstalk.com/filteredimage?image_url=https://s.yimg.com/os/creatr-uploaded-images/2020-11/2ecd3e90-2811-11eb-bf2e-a5ff0cfc4b94

## note that some images can cause error: '(node:10868) UnhandledPromiseRejectionWarning: Error: Could not find MIME for Buffer <null>'
# just try with some other images.