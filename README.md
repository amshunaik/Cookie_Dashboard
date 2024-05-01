# Open Cookie Database 

## About the database :

Cookie : A cookie is a piece of data from a website that is stored within a web browser that the website can retrieve at a later time. Cookies are used to tell the server that users have returned to a particular website.

For this project we have choosen Open cookie database . This database consist of 10 columns. The attribute of the database consist of   
'ID', 'Platform', 'Category', 'Cookie / Data Key name', 'Domain','Description', 'Retention period', 'Data Controller', 'User Privacy & GDPR Rights Portals', 'Wildcard match. This database describe and categorise all major cookies. The info provided by these attributes are :

1. The database consists of 3 different categories of cookies which are  Functional which is also known as technical, essential or strictly necessary, Analytics also known as performance or statistics and Marketing which is also known as tracking or social media. 
2. Platform : It is a  device platform from which a cookie originates or is stored.
3. Cookie / Data Key name : The "cookie name" refers to the identifier assigned to a specific cookie
4. Domain : When a cookie is set by a website, the website can specify the domain(s) for which that cookie is relevant.
5. Description : This attribute provide documentation outlining the purpose, usage, and characteristics of a specific cookie.
6. Retention Period : refers to the duration for which a cookie remains stored on a users device before it expires and is automatically get deleted.
7. data controller of a cookie:  refers to the entity or organization that determines the purposes and means of processing the personal data collected through the cookie
8. User privacy  GDR rights : data protection laws and regulations the data controller is responsible for complying .
9. Wildcard match : In this attribute column a '0' in this column means that the cookie name is not a wildcard, and  '1' means that the cookie name is a wildcard.


## Steps for running the code : 
1. Install VsCode in your pc.
2. Open the terminal and install dash and its dependancies 
- pip install dash
- pip install dash-core-components dash-html-components dash-bootstrap-components plotly
3. Install other necessary libraries such as
- pip install wordcloud.
- pip install plotly
4. Then write the command "python part1.py" in terminal and press enter
5. You will see a  simple dash application running locally at 'http://127.0.0.1:8050/'

