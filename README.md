# Invoke-PortScan
PowerShell port scanning script

I wanted to make a native PowerShell way to test for open ports. This should work on PowerShell 2.0 and above (maybe 1.0, I haven't tried) I fixed it up to make it "Releasable".

Usage examples:

Invoke-PortScan -IsNetScan -PortList 22,80,8080

Invoke-PortScan -targets 192.168.1.1 -Mode top
