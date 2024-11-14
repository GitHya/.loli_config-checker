# .loli_config-checker

# Important Notes:
This tool does not log any user data or actions.
It performs local checks only, and makes use of the VirusTotal API for additional security checks.
You must provide a valid VirusTotal API key to enable the VirusTotal scanning functionality this is optional.

# Sample Output:
Once you run the tool, you may see output like this: 
```
[INFO] Scanning file test.loli for malicious patterns...
[SAFE] No malicious patterns found.
```

Or, if a potentially harmful pattern is found:
```
[WARNING] Malicious pattern detected in file: test.loli
The file contains a command that could terminate processes: taskkill /f /im malicious_process.exe
[INFO] You can check the file on VirusTotal: https://www.virustotal.com/url/scan-id
```

# Customization
You can modify the malicious patterns in the malicious_patterns.txt file to include additional suspicious behaviors that you want to flag.
The tool currently supports a wide range of malicious patterns, but you can expand the list as per your needs.
If you are having false-positives (this will possibly be almost alot of times) it means you possibly use a Openbullet bruteforce configs that connect thru HTTP removing the pattern may resolve the issue.

Contributions
Feel free to contribute by submitting issues or pull requests. All contributions are welcome, but please ensure that they adhere to the code of conduct and license terms.

Enjoy using Loli_Checker 1.0!
