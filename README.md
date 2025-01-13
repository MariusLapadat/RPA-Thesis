https://youtu.be/dEV4v1sSvWo 

Abstract
This project develops a Robotic Process Automation (RPA) system using
Automation Anywhere to automate the order placement process on the Altex website.
The manual process involves accessing an Outlook email, downloading an attached
Excel file with order details, logging into Altex, searching for products, applying filters,
placing orders, logging out, and responding to the email with order details.

The automated solution divides this process into modular bots: loading data,
downloading orders, logging in, searching for products, placing orders, logging out,
and responding to the email. This design ensures flexibility and ease of maintenance,
with try-catch blocks for error handling and data passed between bots via input and
output variables.

Key challenges included accurate product selection and managing diverse
price filter interfaces. System requirements include a stable internet connection, a
dedicated operations folder, and an input Excel file with login credentials and a file 
path.

Initial testing of each bot and comprehensive testing of the entire process using
simulated orders helped optimize the system. The project demonstrates RPA's
potential to enhance efficiency and reduce errors in e-commerce tasks. Future
research could integrate AI and machine learning to further improve capabilities and
extend automation across the e-commerce lifecycle.
