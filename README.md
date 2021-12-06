# WasteManagementSystem

Waste Management System is a web-based application which can be used to make the users collaboratively manage waste in different communities 
such as households, offices, markets, etc. The website which is developed by us will be used by Waste generator and Waste Collector. The idea is to 
automate the waste collection and waste reusability process through the website. The generated waste can be disposed so, the other party can buy 
and use that waste for recycling at industry level. The different types of wastes are segregated at community levels such as plastic waste from 
market and public places, paper and organic waste from households, glass waste from industries. We have created this web application to help India in 
becoming a waste free country because our country faces many problems related to waste management, the waste is not managed properly and it 
makes hazardous impact on humans and animals life and also on our environment. We are hoping that may be our small step will make a huge difference to make our India clean

In any type of waste management system there are two categories of people which plays very imp role in managing the proper waste disposal and 
collection. The first one is the person who has waste available and he/she knows that this waste can be further recycled and there’s no logic in 
dumping this waste and pollute our environment. The second one is the person who collects the waste and recycle it for further utilization and makes
the best out of waste. The website will be used by 2 types of users Generator (Disposal ofwaste) and Collector (Recycle of waste), Generators are those people who 
have the thrift waste available with them, they can be from households, industries, offices, etc. They can dispose their waste by filling all required 
details in the form in our website and Collectors are the people who need the thrift waste and then they recycle it. So first of all, they can check 
whether their required waste is available or not by filling the search form and if their desirable waste type (e.g., Plastic, metal, organic, glass, etc.) is 
available they can fill the form and contact the desired generator who have thrift waste.


System Requirement

Hardware Specification
1. 4GB Ram
2. 1TB Hard disk

Software specification
1. PyCharm Community 3.7
2. Python 3.9.0
3. Chrome
4. Sqlite3
5. WhatsApp

Languages
1. Python
2. CSS
3. HTML

Technology
1. Django
2. Google Dialog Flow
3. Botcopy


IMPLEMENTATION

We have designed 2 modules to implement the web application:

1. Waste Disposal

This module is designed for Waste generators who have waste available like plastic, metal, organic, glass, and organic from different communities like households, industry, markets, and offices. 
Waste generator can dispose of their waste through the system by following below steps

1. First of all, waste generator has to register themselves into the system with their details like username, password and email id.
2. After successful registration user can login into the system with the registered credentials (username and password).
3. User can take the help of Chabot to solve queries related to system and its working and can also take help to segregate waste and related task.
4. After Login user have to select disposal tab and then user can dispose the waste through the system by filling the waste disposal form with the details name, address, contact, type of waste, community, quantity of waste.
5. After clicking on the submit button the details of particular user will be stored into the database.


2. Waste Recycle
This module is designed for waste collectors who have to collect thewaste from the waste generators for recycling the waste to generate new byproducts. 
User can collect the waste through the system by following below steps:

1. Waste collector have to register into the system first with the details like username password and email id.
2. After successful registration user can login into the system with the registered credentials (username and password).
3. The system has provided Chatbot (Waste Management Bot) which will help the user to solve the queries related to the system and its working.
4. After login user have to select recycle tab and then user can first search that waste is available or not. If the waste is available user can buy it for recycling through the system by filling the recycle waste form with details like name, address, contact, type of waste, community.
5. After filling the form, the waste collector gets the list of waste generators with the required waste type so waste collector have to select one waste generator from the list and can contact the generator via call and WhatsApp message.
6. After contacting the waste generator, the collector can collect the waste for recycling from the specified address of generator from the list
