# Andrew's Store
 It is a store manager web application which adds products to the store, provides quick search of specific products available, It enable store owners to access sales made on a particular day and it provides an efficient way in adding goods in a shopping cart and making a purchase.
 
 ## Test store's Endpoints
All endpoints of the store's manager.[![Build Status](https://travis-ci.org/Njaya2019/storemanager.svg?branch=ft-add-product-endpoint-161206503)](https://travis-ci.org/Njaya2019/storemanager).


## Test coverage reporting
Reports code coverage of all endpoints added in the application.[![Coverage Status](https://coveralls.io/repos/github/Njaya2019/storemanager/badge.svg?branch=ft-add-product-endpoint-161206503)](https://coveralls.io/github/Njaya2019/storemanager?branch=ft-add-product-endpoint-161206503)

###### usage
To use this reporting tool create .travis.yml file and have an account in https://coveralls.io.
To get the report you run the script below in travis file.

1. install:
 - pip install -r requirements.txt
 - pip install coverage
 - pip install coveralls
 - pip install pytest pytest-cov
 
2. script:
 - pytest --cov=.

3. after_sucess:
 - coveralls


