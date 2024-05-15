# GenRestAPI
Generator of backend project in spring boot framwork

Create your backend projet quickly using this commmand line.

1- Download the project and unzip it inside your current project
2- Add the envirment varibale for the script
 -> Exmple:
 - The path of your project is: C:\WorkSpace\YourProject\api
 - The envirmment varivale is:
3- Configure the description of cartage.properties
   Like this:

Now to using command line you need to know this:
After open a terminal inside your project:
Ex1:
$ cartage c e NameOfEntity(id:Long,name:String,dateExapmle:Date)
--> This is meanin:
  c: create
  e: entity
  NameOfEntity: is the name of entity that you want to create
  (id:Long,name:String,dateExapmle:Date): is the description of the types and attributes for your entity

Ex2:
$ cartage m NameOfEntity
=> Create Model NameOfEntity

$ cartage r NameOfEntity
=> Create repository for model NameOfEntity

$ cartage s NameOfEntity
=> Create service/service impl from model NameOfEntity

$ cartage c NameOfEntity
=> Create controller for NameOfEntity

