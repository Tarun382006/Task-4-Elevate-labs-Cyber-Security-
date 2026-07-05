In this task, I learnt how to open a windows defender(advanced settings), analyze the existing rules, creating new rules, testing new rules, and also how to delete the rules. I am happy that I learnt these new stuff today.

Commands that I used:
  Test-NetConnection localhost -Port 23   -  To test the port using poweshell
  "wf.msc" in the windows run(windows Key + r)  -  To open the Windows defender advanced settings

Summary:
  Windows Firewall filters incoming and outgoing network traffic based on predefined rules. These rules can allow or block specific ports, protocols, applications, or IP addresses.
  I opened Windows Defender Firewall with Advanced Security and viewed the existing inbound firewall rules. I created a new inbound rule to block TCP traffic on port 23(Telnet). After applying the rule, I tested the port using PowerShell with the Test-NetConnection command. The firewall prevented traffic on the blocked port as expected. Finally, I removed the test rule to restore the firewall to its original configuration.

I have attached the screenshots of each step. Thank you.
