
# Auth Google with HTML & JS

This repository don't given data of account to other functions, only display on card after logged in, and the data of u account is not saved or stored anywhere.
When refresh page, this login is displayed.

## Instructions of create OAuth permission Google and configure project.

- Access **Google Developer Console** and create a *Project*
- Access **Credentials** 
    - Access **Configurate Display of consentiment**                                                                                        
        - Select **User type**
            - **INTERN**
                
                Only users of specific platform.

                Ex: Only users of platform has permission to create account.
            - **EXTERN**

                All users external has permission to create a account utilizing Google OAuth
        - Insert the fields:
            - name of application
            - e-mail support
            - image of application
            - domain of application
            - link policy
            - link of term of services
            - email of developer

        - Scopo not confidentials:
            - select:
                -   "../auth/userinfo.email"
                -   "../auth/userinfo.profile"

        - Insert a users tests
        - Go to credentials and click in **Create credential** and 
        select **ID of client Oauth**, select type of application (Select Application web)

        - Select Origin of javascript authorized and URL redirects authorized 
        
        - Download ID Client and Key secret.

        - Paste ID Client in the field named **"YOUR_GOOGLE_CLIENT_ID"**