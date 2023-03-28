# Yii2 + Doctrine + DDD + TDD

This is work in process, please patience.
I will put example files also.

I have been forwarding to DDD and Clean Code.
But i have been using Yii for a long time and the MVC for big projects, gets very messy after some time.

So I have been trying something diferent.
First in Yii2 started using Modules (like Domains) with SubModules inside (if needed).

About Modules:
I like very much, everything inside the same Domain, it still litle messy because of the active records, not easy to detach from model.
If we try to detach, what i had encounter is to create Repositorys and Adapters, wich it seems the right way but not easy, a lot to refactoring, still a little lost, but starting. The tests are also inside each module what helps to simplify.

I think that DDD (Domain Driven Design) shouldn't be static, it depends always of the project and dimensions of it.
And also of the project complexity, i think most are crud, but my problem is when we want to get out of the box

--- Structure ---<br/>
Project Root<br/>
&emsp;|-> modules<br/>
&emsp;&emsp;|-> Inventory<br/>
&emsp;&emsp;&emsp;|-> Inventory Lines<br/>

Also trying to change from ActiveRecord do Doctrine, i have already did it in one Class :) , but because i use Yii after change i had encounter dificulties with the "Dataproviders" of the grids, still finding one workaround.

I Still repeat the creation of EntityManager, i didn't see "Dependency Injection" Yet
