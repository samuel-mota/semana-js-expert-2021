mkdir recorded
    npm init -y 

    npm i mocha@8 chai@4 nyc@15 sinon@9

    mkdir test/
        todo.test.js 
            dependencies
            describe('todo', () => {

            })
    package.json 
       test 
       test:dev 
       test:cov 
    npm t 
    npm run test:dev  
    npm run test:cov 

    mkdir src/todo.js 
        constructor
        module.exports 
    
    todo.test.js 
        sandbox 
        describe('isValid')
        it('should return invalid when creating an object without text')
        it('should return invalid when creating an object without "when" or "when" is invalid')
        it('should have "id", "text", "when" and "status" properties after creating object')

    npm run test:dev 
    todo.test.js
        1o it
    todo 
        !!this.text    
    todo.test.js
        2o it
    todo 
        isNaN()
    todo.test.js 
        3o it 
    
    npm i lokijs@1.5

    todoRepository
        all 
    todoRepository.test.js 
        all 

    todoService
        list (only signature)
    todoService.test.js 
        #list 
    todoService 

    todoService 
        create( only signature)
    todoService.test.js 
        it('shouldn\'t save todo item with invalid data')
        it('should save todo item with late status when the property is further than today')
        it('should save todo item with pending status')
    
        beforeEach
        1o it 
    todoService
        implement if 
    todoService.test.js 
        2o it (without fakerTimer and today)
    todoService
        add implementation 
    todoService.test.js 
        addd faker and todday 
     
    todoService.test.js 
        3o it 
            all 
    src/index.js 
            all 
    npm run test:cov 
end