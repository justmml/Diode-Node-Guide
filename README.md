# Diode-Node-Guide

Here is Guide, how to deploy Diode Node in few minutes.
Additionally I'll add, that in that guide I will use Asia as region.

1. We need a place, where to host VPS to deploy node. After market deep analize, I've found that one of the best solution is to have VPS at LightNode (lightnode.com)
1a. Plus, that we can pay not directly by card, but also using PayPal account

1b. After Recharging accout we will get +5$ as bonus, hooray!

1c. Location variety is really awesome ![изображение](https://github.com/user-attachments/assets/cda667a2-2d95-49e5-b927-5aa0fb8991b1)

1d. Lets choose location, Ubuntu as OS and preferable instance stats. Also choose Password, to login via ssh.

1e. Push submit to deploy VPS.

1d. After few minutes we will get working VPS server.

2. Let's login using Terminal. If you are using Windows click Win + R, and enter cmd + Enter.

Than enter ```ssh root@<your_ip_address>```

Print ```yes``` when you will be asked to add address to the list of known hosts.

Now we need to update server. Print ```sudo apt update && sudo apt upgrade -y``` and wait until finish

Next step, we are installing diode node using command ```sudo snap install diode-node```. Wait until finish.

Last step is to use command ```diode-node.info```. There we can get our dashboard address. There we need to copy our Address and register it Diode Collab application using Registrar bot. Write him message ```register node <node_address>```

Thats all, congrats!
