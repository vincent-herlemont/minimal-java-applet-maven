minimal-java-maven
==================

A Minimal Java built with Maven project.

# Passkey = "abcd1234"
keytool -genkey -alias minimal -keyalg RSA -keystore src/main/resources/minimal-keystore.jks -keysize 2048 -dname "CN=minimal, OU=development, O=minimal, L=City, S=MN, C=US" -validity 3650
keytool -selfcert -alias minimal -keystore src/main/resources/minimal-keystore.jks
