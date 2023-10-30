# Creating-a-backdoor-with-SET
## AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:
1.Install kali linux either in partition or virtual box or in live mode

2.Investigate on the various categories of tools as follows:

3.Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers.

The command sudo setoolkit in the prompt gives menu with set prompt:
![270236271-72911488-bd84-487d-b87b-fb13a107dd1e](https://github.com/durga46/creating-a-backdoor-with-SET/assets/75235704/cb704612-6a91-432d-afec-f613a6342220)



It displays the following menu and select 2 for Website Attack Vectors:
![270236316-0c19e322-a942-4cc1-99ed-b8455da43abf](https://github.com/durga46/creating-a-backdoor-with-SET/assets/75235704/b6f00f6e-ab4a-4e2e-b04f-ab2a672273a7)



The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![270236381-9548d003-27a3-4509-bd8d-b38967e27fc3](https://github.com/durga46/creating-a-backdoor-with-SET/assets/75235704/6eb5f3ce-76fc-4d3b-957e-ed391abba6ad)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![270236422-a6760b9d-8632-47ce-b295-9699e54f3a33](https://github.com/durga46/creating-a-backdoor-with-SET/assets/75235704/60605ca2-06d5-4291-8798-969648bdaf5a)



It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![270236453-ab2f001d-d317-48cd-acb5-9de51c191fdc](https://github.com/durga46/creating-a-backdoor-with-SET/assets/75235704/65fe2deb-63a0-4fa1-8cca-eaa803955e6e)



It shows the following screen in which the option Google can be selected:
![270236495-7c15a2f5-9da0-49cf-a269-d57e411f8539](https://github.com/durga46/creating-a-backdoor-with-SET/assets/75235704/b3454e92-2528-490f-ac75-3e157beb242d)



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![270236526-fc3120cc-0342-4a95-b2a6-d1951daf3219](https://github.com/durga46/creating-a-backdoor-with-SET/assets/75235704/d901f7ac-c896-4fdc-8e3c-c4eecb53daf7)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
![270236586-1fb0bc90-0220-4dde-9aae-2cabc3873291](https://github.com/durga46/creating-a-backdoor-with-SET/assets/75235704/b91a1ba2-a12b-4ba1-9692-67f2bc9067b3)



SET logs the information regarding the Google credentials:
![270236619-9457e41a-31e2-48a7-88d0-7c71afb30367](https://github.com/durga46/creating-a-backdoor-with-SET/assets/75235704/d2dfa4dd-b6cd-4452-b802-ad97ff14ef04)



SET logs the information in the xml file under /root/.set directory:
![270236672-3c288818-d232-4d31-b09f-a1db311cbd94](https://github.com/durga46/creating-a-backdoor-with-SET/assets/75235704/edc3a333-5728-45f6-9da5-d9c98ecd1ddf)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is examined successfully
