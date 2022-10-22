# DemoBlazeTask

*This is a maven project.

*Java language and OOP concept(Encapsulation,Inheritance,Abstraction,Polymorphism) has been used.

*Build up with Cucumber-Junit framework(Feature File,StepDefinitions,Runner class, Hooks).

*Resources/Feature file where I keep scenarios. It is written with plain English by using Gherkin Language.

*Step Definitions are java classes where all java code is written in it.

*Runner class is text executor which is working with Tags. it also has rerun and report extension.

*Hooks class is where I keep my before and after method.

*Page Object Model design pattern has been used(Configuration properties,Configuration readers,pages,Utilities).

*Pom.xml is brain of our project I put all kind of dependencies and libraries needed.

*Configuration Properties is a central for saving all necessary data(url,browser,credentials).

*Pages are each web page has a corresponding java class where I keep all necessary locators and methods.

*Utilities folder has Driver,Browser Utils and Configuration Readers class.

*The task can be run in different browsers as chrome,firefox.

*Because of my internet connection I put waits before some steps(otherwise my tests were failed) but if the environment fast they are not necessary.

*Reports: Default-html-reports and cucumber-html-reports are implemented in Target folder that you can see them as well.

------------------------
1) the calculation of the total price is wrong (there may be 2 reasons; the promo code may not be calculating correctly or there is an error in the calculation code),
   There are 2 realizar pedido buttons (there is a design repitition or there may be a hard code error), the master card view is wrong (design problem),
   There is a typo in the letter a and the word codigo (the user´s computer language format may be different or it may be sending differently when exporting/translating to another application/format).
   in the second image client got 403 error, as it is 400 error we can understand its an client side issue. client is forbidden from accessing a valid url.

2)first web driver need to find locater of fecha de expiracion then use sendKeys method to send date.
first web driver need to find locater of CVV / CVC then use sendKeys method to send date.
first web driver need to find locater of nombre en la tarjeta then use sendKeys method to send date.

3) 1= 7 tests
   2= there is no way to run only second scenario with given tags, but I can run my test on the feature file ¨run test¨ button which is next to the each scenario.
   3 = I will look online

4) I will check after performance test

5) I will look later

6)
1. Los links del menu no tienen el mismo color que los diseños. (BAJO)
2. Al intentar iniciar sesón no ocurre nada (ningún tipo de feedback). (CRITICO)
3. Al hacer click en un producto en concreto aparece una página de error. (ALTO)
4. Uno de los banners publicitarios de la web es demasiado grande y se solapa con el menu, haciendo que este no pueda ser utilizado.(ALTO)
5. No es posible pagar un pedido utilizando Paypal, salta un error por pantalla.(CRITICO)
6. Al navegar por cierta sección de la app esta se cierra automáticamente (la aplicación).(CRITICO)
7. Al hacer click en cualquier producto aparece una página de error.(CRITICO)
8. Las páginas de categorías muestran los productos mal alineados entre ellos.(MEDIO)
9. Al realizar un pedido no está llegando el e-mail de confirmación.(ALTO)
10. En la página de un producto aparece un precio y luego al añadirlo al carrito aparece otro completamente distinto.(CRITICO)