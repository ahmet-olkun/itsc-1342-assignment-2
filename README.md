# ITSC 1342 - Assignment 2: Port Analyzer

Author: Ahmet Olkun

`code/solution.py` classifies a network packet using its port and size in bytes.
Ports 80 and 443 are standard web traffic. For other ports, packets larger than
1500 bytes or smaller than 64 bytes are suspicious; other sizes are normal
internal traffic.

Run the provided tests from the repository folder:

```powershell
python .\tests\test_solution.py
```

Test output is saved in `tests/test_output.txt`. The `screenshots` folder is for
the screenshot showing the solution code and successful test execution.
