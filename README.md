## Steps Performed
1. **Checked Current Firewall Rules**  
   - Windows: `wf.msc` → Inbound/Outbound rules

2. **Created a Blocking Rule**  
   - Example: Blocked Telnet on port 23 (TCP)  
   - Windows: New Rule → Port → TCP 23 → Block the connection

3. **Tested the Rule**  
   - Windows: `Test-NetConnection -ComputerName localhost -Port 23`
   - Verified the connection was refused.

4. **Removed the Rule**  
   - Windows: Deleted the inbound rule

## Screenshots
All evidence of the above steps (before, during, and after configuration) is stored in the **`screenshots/`** folder.
