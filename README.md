# mountbank_lab
# web
1. http://www.mbtest.org/docs
# set up
1. install: npm install -g mountebank
2. run: mb —configfile imposters.ejs —allowInjection
3. Postman
    EX: (Endpoint api)
        Post http://localhost:3000/customer/v1/profiles/create
        Body :
        {
            "requestTransactionID": "xxx",
            "name": "TestName",
            "lastname": "TestLastname",
            "cardIdentification": "XY"
        }
