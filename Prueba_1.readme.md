"EY_QA_Prueba_1"
1) The calculation of the total price is wrong (there may be 2 reasons; the promo code may not be calculating correctly or there is an error in the calculation code),
   There are 2 realizar pedido buttons (there is a design repitition or there may be a hard code error), the master card view is wrong (design problem),
   There is a typo in the letter a and the word codigo (the user´s computer language format may be different or it may be sending differently when exporting/translating to another application/format).
   In the second image client got 403 error, as it is 400 error we can understand its an client side issue. client is forbidden from accessing a valid url.

2)First web driver need to find locater of fecha de expiracion then use sendKeys method to send date.
First web driver need to find locater of CVV / CVC then use sendKeys method to send date.
First web driver need to find locater of nombre en la tarjeta then use sendKeys method to send date.

3) 1= 7 tests
   2= There is no way to run only second scenario with given tags, but I can run my test on the feature file ¨run test¨ button which is next to the each scenario.
   3 = Yes, there is a way to run only one of the tests. We write each test under multiple examples and put tags above each examples. While running, we can click the ¨run test¨ button next to those tags.

4) I haven't done a performance test before.

5) As I understand from the image, there are 2 stages (preparation and test:e2e).
   First one is preparation stage and to make work this stage , they have @preparation tag and maven command to build and run the job.
   As second stage there is e2e stage which has preparation stage as dependencies.
   I think before e2e test preparation stage must be run.
   e2e stage will be running always however expire in a 1 week.
   To build and run the job there is maven command for this stage as well.
   In this stage they will use @standard tag and the path of the directory is located in OUTPUT_DIRECTORY and incase of failing test the number of attempts is indicated as ¨1¨.

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