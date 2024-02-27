<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1 - Install all the needed programs fully needed for osTicket to run.
- Item 2 - Search on your remote desktop browser "127.0.0.1 to get loopback. this is to make sure IIS is install and configured correctly.
- Item 3 - Open and run IIS as administration, and register PHP with IIS. Then most importantly from experience is to restart server!
- Item 4 - In IIS, navigate down the drop line, Sites-default-then osTicket. then select Browse *.80 after that osTicket should begin to load.
- Item 5 - just be courious and see what are some of the things you can do in regards to whether you are assiging tickets or creating them.
<h2>Configuration Steps</h2>

<p>
  
![download IIS](https://github.com/Randrade1995/osTicket-install-config-/assets/161271930/85d432c7-607a-47a0-9cef-0fe5c359a49e)


</p>
<p>
A lot of programs are needed to start off but eventually once you get the idea what to do with each, it becomes easier. making every program is install correctly is very important because you will not know if something is wrong until it is too late or a lot of time went by.
</p>
<br />

<p>

![TEST IIS INSTALLATION](https://github.com/Randrade1995/osTicket-install-config-/assets/161271930/1ff49011-dd3a-4ae9-8762-1db7c8838b70)


</p>
<p>
The good thing about being able to do a loopback on your browser is to make sure IIS is installed correctly. This is basically the only check point from this section on.
</p>
<br />

<p>


![ENABLE PHP VERSION](https://github.com/Randrade1995/osTicket-install-config-/assets/161271930/b9396421-6cf2-45a5-a5e0-fb2ca04576f9)


</p>
<p>

Any changes made to IIS requires a restart or stopping of the program. This does not mean you are actually closing the program. on the right side of the screen is a restart or stop button that basically refreshes the program.
</p>
<br />



![os ticket install home page](https://github.com/Randrade1995/osTicket-install-config-/assets/161271930/d0398f43-8584-49b2-8aca-00d7ff68627d)


I was able to just navigate around the program and get use to it. learn how System admins assigns tickets or roles. It gave me a better understanding of the program and how important it is. espicailly for SLA agreements!



![roles](https://github.com/Randrade1995/osTicket-install-config-/assets/161271930/01e7286e-c0c3-4eff-90bc-083306d9fd8d)









![department](https://github.com/Randrade1995/osTicket-install-config-/assets/161271930/9d8b4834-a4a3-4f6d-b810-7563d60f20e0)




