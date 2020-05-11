<!-- ### WukongCRM (Version 9.0)
Wukong Software has long provided enterprises with information services such as R&D, implementation, marketing, consulting, training and service of enterprise management software (CRM/HRM/OA/ERP, etc.). We have taken high technology as its starting point, technology as the core, and perfect after-sales service as its backing. With the spirit of stability and development, factualism and innovation, it has provided services for thousands of enterprises at home and abroad.

The development of Wukong benefits from open source and vice versa. In 2019, Wukong CRM will continue to adhere to the concept of “embracing openness, cooperation and win-win, creating value”, move forward on the road of open source, and make positive contributions to open source at home and abroad with more community developers.

Official website: ：[http://www.72crm.org](http://www.72crm.org/)

Demo ：[demo9.5kcrm.net](http://demo9.5kcrm.net/)(account number: 18888888888 password: 123456)

Wukong CRM adopts a new mode separating front-end from back-end. The front-end vue packaged files have been integrated into the warehouse code, eliminating the need for packaging operations.

If you need to adjust the front-end code, please download the front-end code separately. The front-end code is in the ux folder of the root directory.

## Main technology stack

Back end framework: ThinkPHP 5.0.2

Front end MVVM framework: Vue.JS 2.5.x

Routing: Vue-Router 3.x

Data interaction: Axios

UI framework: Element-UI 2.6.3

Wukong crm9.0 operating environment requires PHP5.6 or above.


## One click installation

The front-end vue packaged files has been integrated into the code without the package operation: Take the local (phpstudy integrated environment) setup as an example: download the Wukong CRM9.0 open source version, create the 72crm folder in the server root directory (www directory), and place code; browser access 

`http://localhost/72crm/index.php/admin/install/index.html `

Complete the deployment and installation of Wukong CRM9.0 according to the installation prompt steps.





## Development dependencies (you need  personalized  installation or adjust the front-end code and please follow the tutorial below, one-click installation users can ignore this step.) 

### Data interaction
Data interaction is implemented by axios and RESTful architecture. User verification is put in header by auth-key returning from log-in. It is worth noting that in the case of cross-domain, there will be a pre-request OPTION.

### Server setup
The framework used by the server is thinkphp5.0.2. Make sure to have the lamp/lnmp/wamp environment before building.

The setup mentioned here is actually putting the server framework into the WEB runtime environment and using port 80. Import the server root folder database file public/sql/5kcrm.sql and modify the config/database.php configuration file.

### Configuration requirements
PHP >= 5.6.0  When accessing http://localhost/, "Wukong Software" appears, which represents the successful setup of the backend interface.
### Front-end deployment

Install the front-end part of node.js  based on node.js, so you must first install node.js with  version  6.0 or above.

Use npm to install dependencies, download the Wukong CRM9.0 front-end code; place the code in the backend peer directory frontend, execute the command to install dependencies: npm install

    npm install

Modify the internal configuration and request address or domain name: modify BASE_API (development environment server address, default localhost) in config / dev.env.js, modify the custom port:  modify the dev object port parameter in config / index.js (default 8080, Not recommend to modify)

### Running front end npm run dev

     npm run dev

Note: The front-end service starts, it will occupy port 8080 by default, so before starting the front-end service, please make sure that port 8080 is not occupied. The Server port needs to be set up before the program runs.

--- -->




