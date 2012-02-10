AIR-Helloworld is a simple AIR application written with FlexMojos 4.1-beta. 

This project creates an AIR installation file, that can be installed onto a computer with an existing Adobe AIR runtime, and will take the name "Hello World." The application simply loads the SWF file this project generates, which projects a system window with the white on black label "Hello, WORLD".  I have used Marvin Froeder's (@velo) default archetype as the basis for this project.

NOTE: This application is signed by a self-generated 2048-RSA keyfile "src/main/resources/sign.p12" created with the "adt" binary in the Adobe AIR SDK. I used the following command to generate this "sample" keyfile:

adt -certificate -cn SelfSign -ou SC -o "Sistemas Complejo, ECOSUR" -c MX 2048-RSA sign.p12 secret

