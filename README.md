Rest Services in Intersystems-Iris.

In this step, you create a web application that provides access to your REST service. In the Management Portal, complete the following steps:

    1- Click System Administration > Security > Applications > Web Applications.

    2- Click Create New Web Application.

    3- Specify the following values:

    Name: Name for the web application; this must be unique within this instance of InterSystems IRIS. The most common name is based on the namespace in  which the web application runs: /csp/namespace

    Namespace:  Select the namespace in which you generated the classes.

    Enable Application:  Select this check box.

    Enable:  Select REST.

    Dispatch Class: Type the fully qualified name of the dispatch class.

    Click Save.

![Captura de pantalla 2023-01-23 a las 14 18 59](https://user-images.githubusercontent.com/107713900/214049575-207de892-d193-4e44-977f-f4dc8a8c20b0.png)


This is the web application created:

![Captura de pantalla 2023-01-23 a las 13 09 41](https://user-images.githubusercontent.com/107713900/214048812-b1a2ec94-b62a-4a3d-93dc-4a22ff29da53.png)


![Captura de pantalla 2023-01-23 a las 14 12 10](https://user-images.githubusercontent.com/107713900/214049812-7e15c7d3-f3b2-4f7a-a310-44b5b3ec71b8.png)
