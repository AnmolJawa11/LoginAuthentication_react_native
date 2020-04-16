# LoginAuthentication_react_native
Provides a boiler plate code for login authentication for react native apps


#Steps to get the native app working

npm install
npm install expo-cli --global
expo start

# Configurations
modify the following configurations at config.js
 
export const AUTH_CLIENT_ID = "<Auth0 client id>";
export const AUTH_DOMAIN = "<Auth0 domain>";
export const ID_TOKEN_KEY = "todo-id-token";
export const NONCE_KEY = "todo-nonce";
export const GRAPHQL_ENDPOINT = "<Hasura graphql host id>";
export const AUTH_NAMESPACE = "https://user";
