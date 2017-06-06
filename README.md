# project1
project1 is my first attempt at deploying a dynamic c2 enviroment.

Phase one: Choose and include a method of securely administrating a c2 enviroment. 
Solution: Deploy striesand server. Striesand allows for multiple ways of connecting with the purpose of bypassing censorship, this method should prove valuable during pentesting.

Phase two: Include a method of auto deploying empire 2.0+ and metasploit. lockdown administrative ssh access so that only the striesand server can directly access and administrate.

Phase three: deploy a nginx redirection server. should corrospond to https://github.com/bluscreenofjeff/Red-Team-Infrastructure-Wiki methods of deploying a secure redirecting service.

Phase four: built script to auto generate  empire and metasploit payloads for various tasks; phishing payloads, ducky, ect

Phase five: build script to auto generate payploads on enviroment change as well as send current bots an updated command to change redirectors. IE, new redirector site generated.

Phase six: auto recreate payloads based on some task... like user initiated, virus-total found it, every 5 mins?, ect

Phase beyond: build-in features and ideas from other pentesters, incorp new tools, expand futher into the Red-Team-Infrastruture methods and recommendations.

