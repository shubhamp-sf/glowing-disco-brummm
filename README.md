# glowing-disco-brummm

<table>
<thead>
    <th>Name</th>
    <th>Required</th>
    <th>Description</th>
    <th>Default Value</th>
  </thead>
  <tbody>
      <tr>
        <td>NODE_ENV</td>
        <td>Y</td>
        <td>Node environment value, i.e. `dev`, `test`, `prod</td>
        <td></td>
      </tr>
      <tr>
        <td>LOG_LEVEL</td>
        <td>Y</td>
        <td>Log level value, i.e. `error`, `warn`, `info`, `verbose`, `debug`</td>
        <td></td>
      </tr>
      <tr>
        <td>DB_HOST</td>
        <td>Y</td>
        <td>Hostname for the database server.</td>
        <td></td>
      </tr>
      <tr>
        <td>DB_PORT</td>
        <td>Y</td>
        <td>Port for the database server.</td>
        <td></td>
      </tr>
      <tr>
        <td>DB_USER</td>
        <td>Y</td>
        <td>User for the database.</td>
        <td></td>
      </tr>
      <tr>
        <td>DB_PASSWORD</td>
        <td>Y</td>
        <td>Password for the database user.</td>
        <td></td>
      </tr>
      <tr>
        <td>DB_DATABASE</td>
        <td>Y</td>
        <td>Database to connect to on the database server.</td>
        <td></td>
      </tr>
      <tr>
        <td>DB_SCHEMA</td>
        <td>Y</td>
        <td>Database schema used for the data source. In PostgreSQL, this will be `public` unless a schema is made explicitly for the service.</td>
        <td></td>
      </tr>
      <tr>
        <td>REDIS_HOST</td>
        <td>Y</td>
        <td>Hostname of the Redis server.</td>
        <td></td>
      </tr>
      <tr>
        <td>REDIS_PORT</td>
        <td>Y</td>
        <td>Port to connect to the Redis server over.</td>
        <td></td>
      </tr>
      <tr>
        <td>REDIS_URL</td>
        <td>Y</td>
      <td>Fully composed URL for Redis connection. Used instead of other settings if set.</td>
        <td></td>
      </tr>
      <tr>
        <td>REDIS_PASSWORD</td>
        <td>Y</td>
        <td>Password for Redis if authentication is enabled.</td>
        <td></td>
      </tr>
      <tr>
        <td>REDIS_DATABASE</td>
        <td>Y</td>
        <td>Database within Redis to connect to.</td>
        <td></td>
      </tr>
      <tr>
        <td>JWT_PRIVATE_KEY</td>
        <td>Y</td>
        <td>Asymmetric signing key of the JWT token.</td>
        <td></td>
      </tr>
      <tr>
        <td>JWT_PUBLIC_KEY</td>
        <td>Y</td>
        <td>Verifying signed JWT Token.</td>
        <td></td>
      </tr>
      <tr>
        <td>JWT_SECRET</td>
        <td>Y</td>
        <td>Symmetric signing key of the JWT token.</td>
        <td></td>
      </tr>
      <tr>
        <td>JWT_ISSUER</td>
        <td>Y</td>
        <td>Issuer of the JWT token.</td>
        <td></td>
      </tr>
      <tr>
        <td>USER_TEMP_PASSWORD</td>
        <td>N</td>
        <td>Temporary password that can be used during development.</td>
        <td></td>
      </tr>
      <tr>
        <td>GOOGLE_AUTH_URL</td>
        <td>N</td>
        <td>Google OAuth2.0 authorization URL if authentication strategy is set to Google</td>
        <td></td>
      </tr>
      <tr>
        <td>GOOGLE_AUTH_CLIENT_ID</td>
        <td>N</td>
        <td>Google client ID for the service</td>
        <td></td>
      </tr>
      <tr>
        <td>GOOGLE_AUTH_CLIENT_SECRET</td>
        <td>N</td>
        <td>Google client secret for the service</td>
        <td></td>
      </tr>
      <tr>
        <td>GOOGLE_AUTH_TOKEN_URL</td>
        <td>N</td>
        <td>Google OAuth2.0 authorization URL if authentication strategy is set to Google</td>
        <td></td>
      </tr>
      <tr>
        <td>GOOGLE_AUTH_CALLBACK_URL</td>
        <td>N</td>
        <td>Google callback URL for the client configuration in Google</td>
        <td></td>
      </tr>
      <tr>
        <td>FORGOT_PASSWORD_LINK_EXPIRY</td>
        <td>N</td>
        <td>Expiration period of temporary password in seconds. 1800 seconds (30minutes) is the default.</td>
        <td>1800</td>
      </tr>
      <tr>
        <td>KEYCLOAK_HOST</td>
        <td>N</td>
        <td>Hostname of the Keycloak instance</td>
        <td></td>
      </tr>
      <tr>
        <td>KEYCLOAK_REALM</td>
        <td>N</td>
        <td>Realm (tenant) in Keycloak</td>
        <td></td>
      </tr>
      <tr>
        <td>KEYCLOAK_CLIENT_ID</td>
        <td>N</td>
        <td>Keycloak client ID for the service</td>
        <td></td>
      </tr>
      <tr>
        <td>KEYCLOAK_CLIENT_SECRET</td>
        <td>N</td>
        <td>Keycloak client secret for the service</td>
        <td></td>
      </tr>
      <tr>
        <td>KEYCLOAK_CALLBACK_URL</td>
        <td>N</td>
        <td>Keycloak callback URL for the client configuration in Google</td>
        <td></td>
      </tr>
      <tr>
        <td>HTTPS_PROXY</td>
        <td>N</td>
        <td>Https proxy url for keycloak auth</td>
        <td></td>
      </tr>
  </tbody>
</table>
