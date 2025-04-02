
# Pentes - AttackSim Framework
AttackSim Framework is an advanced penetration testing simulation tool based on the MITRE ATT&CK Framework. This tool is designed for educational purposes to demonstrate various penetration testing techniques without actually performing attacks..




## Disclaimer

**This tool is for educational purposes only.** Use responsibly and only on systems you have permission to test. The tool simulates penetration testing techniques but does not actually perform any attacks

## Features

AttackSim Framework simulates the following MITRE ATT&CK tactics:

1. **Reconnaissance** - Information gathering techniques
2. **Execution** - Techniques for executing code
3. **Persistence** - Maintaining access to systems
4. **Privilege Escalation** - Gaining higher-level permissions
5. **Defense Evasion** - Avoiding detection
6. **Credential Access** - Stealing credentials
7. **Discovery** - Exploring the environment
8. **Lateral Movement** - Moving through the environment
9. **Collection** - Gathering data of interest
10. **Exfiltration** - Stealing data
11. **Command and Control** - Communicating with compromised systems
## Installation

```bash
# Clone the repository
git clone https://github.com/Aamir017/penter

# Navigate to the directory

# Install required packages
pip install colorama argparse
```

## Command Line Arguments

- --target : Target IP address or hostname (default: 127.0.0.1)
- --port : Target port (default: 8080)
- --all : Run all modules
- --recon : Run reconnaissance module
- --execution : Run execution module
- --persistence : Run persistence module
- --privilege : Run privilege escalation module
- --defense : Run defense evasion module
- --credential : Run credential access module
- --discovery : Run discovery module
- --lateral : Run lateral movement module
- --collection : Run collection module
- --exfiltration : Run exfiltration module
- --c2 : Run command and control module
## Examples

Run a specific module:
```
python pentest_tool.py --target 192.168.1.1 --recon
```

Run multiple modules:
```
python pentest_tool.py --target 192.168.1.1 --recon --discovery --credential
```

Run all modules:
```
python pentest_tool.py --target 192.168.1.1 --all
```


## Output

The tool provides detailed output for each technique, including:

- Command examples
- PowerShell scripts
- Explanations of techniques
- Simulated attack paths
## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.




## License

This project is licensed under the MIT License - see the LICENSE file for details.

