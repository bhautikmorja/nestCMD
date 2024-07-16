# nestCMD
//Install nestjs
Install Step 1 => npm install -g @nestjs/cli
Install Step 2 => nest new project-name

//Install Module & Contoller
Install Resource like Module - Controller - Service =>	nest g resources project-name
Install Only Resource => nest g resource
Install Module => nest g module project-name
Install Contoller => nest g contoller project-name
Install Service => nest g service project-name
Install Migratiton => npx sequelize-cli migration:generate --name create-user
Install types/express => npm i @types/express --save-dev


**********************************************************************************

//Security
Install BeltGuard = nest g guard belt

**********************************************************************************

//Run Server
Run Server => npm run start:dev

**********************************************************************************

//Points
=> Service ma Lakhay a Controller ma Function Ma return Ma jay

**********************************************************************************

//Type ORM
=> TypeORM is an Object-Relational Mapping (ORM) tool that makes it easy to work with relational databases in Node.js and TypeScript

**********************************************************************************

//Bus Project
=> Migratiton no use databases manage karva thay	
=> allowNull - Value Null True / False
=>  references: {
          model: 'Kayu Populate Karavu Che',
          key: 'id',
        },
=> Entity mathi Import Karavu Hoy Tyare Repository no Use Thay

**********************************************************************************

//=> Gitignore to set gitignore file


**********************************************************************************

=> Sequelize init error => npx sequelize-cli init


**********************************************************************************

=>Middleware Request Vakhate j Work Kare Jyare Interceptor request and response bane time work kare

**********************************************************************************

=> HttpStatus (@nestjs/common) - to Set Code from The Name
=> Response NestJs Automatic Set Kare Apde Set Karvu Hoy to HttpStatus thi Thay
=> @Res({passthrough:true}) res:Response => Response status apde set karvanu return nestjs handel kare
=> Multiple Header hot tyare Alg thi @Header('X-name','Name') Apine  Set Thay
=> Interface thi Direct Datatype Define Thay => Interface QueryParams{age:number;name:string} pachi Contoller ni Ander getVideos(@Query() query:QuaryParams)

**********************************************************************************
=> npm install --global yarn
=> yard install

