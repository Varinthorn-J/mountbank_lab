# mountbank_lab
# web
1. http://www.mbtest.org/docs
# set up
1. install: Node js
2. install: npm install -g mountebank
3. run: mb —configfile imposters.ejs —allowInjection
# Example Test
1. Postman
    EX: (Endpoint api)
        Post http://localhost:3000/customer/v1/profiles/create
        Body :
        {
            "requestTransactionID": "xxx",
            "name": "TestName",
            "lastname": "TestLastname",
            "cardIdentification": "XY"
        }

# medium
1. https://s6135512053.medium.com/mock-service-by-mountebank-b854a6de8528
