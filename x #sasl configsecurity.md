```
#sasl config
security.protocol=SASL_SSL
ssl.truststore.location=/opt/jdk1.8.0_301/jre/lib/security/cacerts
ssl.truststore.password=changeit
sasl.login.callback.handler.class=Oauth2ClientAuthenticateCallbackHandler
sasl.mechanism=OAUTHBEARER
sasl.jaas.config=org.apache.kafka.common.security.oauthbearer.OAuthBearerLoginModule required;




producer.security.protocol=SASL_SSL
producer.ssl.truststore.location=/opt/jdk1.8.0_301/jre/lib/security/cacerts
producer.ssl.truststore.password=changeit
producer.sasl.login.callback.handler.class=.security.Oauth2ClientAuthenticateCallbackHandler
producer.sasl.mechanism=OAUTHBEARER
producer.sasl.jaas.config=org.apache.kafka.common.security.oauthbearer.OAuthBearerLoginModule required;
```

