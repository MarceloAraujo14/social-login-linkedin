Teaching how to authenticate user with Oauth2, Spring Security, Java, Google and Linkedin

Step 1:
- Create a developer Google and Linkedin Account
  - https://console.cloud.google.com/
  - https://www.linkedin.com/developers/

Step 2:
- Google: 
  - Create an application credential and configure the Authorization 
  Domain URI and Redirection URI to your application domain
  - Configure your properties file with your client_id and client_secret
- Linkedin:
  - Create an application on linkedin developer linking with your linkedin page. 
  - Verify you linkedin app.
  - Configure the Authorization Domain URI and Redirection URI to your application domain.
  - Configure your properties file with your client_id and client_secret.
  - Configure your properties with the linkedin provider configuration.

To run this app:
- After configure your application propertie file
  - run the project on your IDE
  - access http://localhost:80 in your browser
  - choose your authentication server
